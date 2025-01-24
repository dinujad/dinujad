## Hi there 👋

# Interactive GitHub README

<div class="demo-container">
  <h2>Interactive Code Snippet</h2>
  <p>Change the values and see the result:</p>
  <div class="code-editor">
    <pre><code class="language-javascript">
const a = 5;
const b = 10;
const sum = a + b;
console.log(`The sum of ${a} and ${b} is ${sum}`);
    </code></pre>
    <button class="run-code">Run Code</button>
  </div>
  <div class="output-area"></div>
</div>

<div class="demo-container">
  <h2>Interactive Data Visualization</h2>
  <canvas id="myChart"></canvas>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  // Create a simple line chart
  const ctx = document.getElementById('myChart').getContext('2d');
  const myChart = new Chart(ctx, {
    type: 'line',
    data: {
      labels: ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun'],
      datasets: [{
        label: 'Sales',
        data: [12, 19, 3, 5, 2, 3],
        backgroundColor: 'rgba(54, 162, 235, 0.2)',
        borderColor: 'rgba(54, 162, 235, 1)',
        borderWidth: 1
      }]
    },
    options: {
      scales: {
        y: {
          beginAtZero: true
        }
      }
    }
  });
</script>

<style>
  .demo-container {
    margin-bottom: 40px;
  }
  .code-editor {
    background-color: #1e1e1e;
    border-radius: 4px;
    padding: 16px;
  }
  .code-editor pre {
    margin: 0;
    color: #d4d4d4;
  }
  .run-code {
    margin-top: 8px;
  }
  .output-area {
    margin-top: 12px;
    padding: 8px;
    background-color: #f0f0f0;
    border-radius: 4px;
  }
</style>

<script>
  // Add event listener to run the code snippet
  document.querySelector('.run-code').addEventListener('click', () => {
    const codeContainer = document.querySelector('.code-editor pre code');
    const outputArea = document.querySelector('.output-area');
    try {
      const result = eval(codeContainer.textContent);
      outputArea.textContent = result;
    } catch (error) {
      outputArea.textContent = `Error: ${error.message}`;
    }
  });
</script>
