<div class="profile-header">
  <img src="profile-image.jpg" alt="Dinuja Dulsara Herath" class="profile-image">
  <div class="profile-info">
    <h1>Dinuja Dulsara Herath</h1>
    <p class="role">Cloud Architect</p>
    <div class="social-links">
      <a href="https://github.com/dinuja-herath" class="social-link"><i class="fab fa-github"></i></a>
      <a href="https://twitter.com/dinuja_herath" class="social-link"><i class="fab fa-twitter"></i></a>
      <a href="https://www.linkedin.com/in/dinuja-herath" class="social-link"><i class="fab fa-linkedin"></i></a>
      <a href="mailto:dinuja.herath@example.com" class="social-link"><i class="fas fa-envelope"></i></a>
    </div>
  </div>
</div>
<div class="about-me">
  <h2>About Me</h2>
  <pre><code class="language-javascript">
const DinujaHerath = {
  location: "Sri Lanka",
  education: "MBA & IT Specialist",
  roles: ["Full Stack Developer", "Cloud Architect", "AI Enthusiast"],
  currentFocus: ["Operating Systems", "Cloud Architecture", "Advanced System Design"],
  communities: {
    founder: ["E Media Solution (Pvt) Ltd"],
    member: ["AI Sri Lanka", "OpenAI Developers"]
  },
  lifePhilosophy: "Learning something new every day 🚀"
};
  </code></pre>
</div>
<div class="tech-arsenal">
  <h2>Tech Arsenal</h2>
  <div class="tech-categories">
    <div class="tech-category">
      <h3>Core Technologies</h3>
      <div class="tech-icons">
        <img src="tech-icons/javascript.svg" alt="JavaScript" title="JavaScript">
        <img src="tech-icons/python.svg" alt="Python" title="Python">
        <img src="tech-icons/csharp.svg" alt="C#" title="C#">
        <img src="tech-icons/java.svg" alt="Java" title="Java">
      </div>
    </div>
    <div class="tech-category">
      <h3>Web Technologies</h3>
      <div class="tech-icons">
        <img src="tech-icons/react.svg" alt="React" title="React">
        <img src="tech-icons/angular.svg" alt="Angular" title="Angular">
        <img src="tech-icons/vue.svg" alt="Vue.js" title="Vue.js">
        <img src="tech-icons/nodejs.svg" alt="Node.js" title="Node.js">
      </div>
    </div>
    <div class="tech-category">
      <h3>DevOps & Cloud</h3>
      <div class="tech-icons">
        <img src="tech-icons/aws.svg" alt="AWS" title="AWS">
        <img src="tech-icons/azure.svg" alt="Microsoft Azure" title="Microsoft Azure">
        <img src="tech-icons/gcp.svg" alt="Google Cloud" title="Google Cloud">
        <img src="tech-icons/docker.svg" alt="Docker" title="Docker">
      </div>
    </div>
    <div class="tech-category">
      <h3>Tools & Systems</h3>
      <div class="tech-icons">
        <img src="tech-icons/linux.svg" alt="Linux" title="Linux">
        <img src="tech-icons/git.svg" alt="Git" title="Git">
        <img src="tech-icons/vscode.svg" alt="Visual Studio Code" title="Visual Studio Code">
        <img src="tech-icons/jira.svg" alt="Jira" title="Jira">
      </div>
    </div>
  </div>
</div>
<div class="github-analytics">
  <h2>GitHub Analytics</h2>
  <div class="github-stats">
    <div class="stat-card">
      <h3>Dinuja Herath's GitHub Stats</h3>
      <ul>
        <li>Commits: 54</li>
        <li>Followers: 110</li>
        <li>Following: 38</li>
        <li>Repositories: 14</li>
      </ul>
    </div>
    <div class="stat-card">
      <h3>Most Used Languages</h3>
      <div class="language-chart">
        <canvas id="languageChart"></canvas>
      </div>
    </div>
  </div>
</div>
<div class="connect-collaborate">
  <h2>Connect & Collaborate</h2>
  <div class="social-buttons">
    <a href="https://www.linkedin.com/in/dinuja-herath" class="social-button linkedin">LinkedIn</a>
    <a href="https://twitter.com/dinuja_herath" class="social-button twitter">Twitter</a>
    <a href="https://github.com/dinuja-herath" class="social-button github">GitHub</a>
    <a href="mailto:dinuja.herath@example.com" class="social-button email">Email</a>
  </div>
  <p>Open to collaborating on Educational Tech, AI Projects, and Open Source!</p>
</div>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  // Render the language chart
  const ctx = document.getElementById('languageChart').getContext('2d');
  new Chart(ctx, {
    type: 'doughnut',
    data: {
      labels: ['JavaScript', 'Python', 'C#', 'Java', 'Other'],
      datasets: [{
        data: [45, 25, 15, 10, 5],
        backgroundColor: ['#f1c40f', '#e74c3c', '#2980b9', '#8e44ad', '#7f8c8d']
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: {
        title: {
          display: false
        }
      }
    }
  });
</script>
<style>
  /* Add your custom CSS styles here */
</style>
