<!-- 🌟 Om Kawale's Immersive GitHub Universe -->
<div align="center">

  <!-- Animated Banner with 3D Effect -->
  <img 
    src="https://readme-typing-svg.demolab.com?font=Montserrat:wght@700&size=30&duration=3000&pause=1000&color=F7A41D&center=true&vCenter=true&width=1000&lines=Welcome+to+Om+Kawale's+Digital+Workshop+%F0%9F%9A%80;Frontend+Architect+%7C+AI+Innovator+%7C+UX+Visionary;Crafting+Tomorrow's+Interfaces+Today;Where+Creativity+Meets+Technical+Excellence" 
    alt="Dynamic Introduction" 
  />

  <!-- Animated Wave -->
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=header&animation=fadeIn&fontAlignY=35&fontSize=25" />

  <!-- Quick Stats with Animated Icons -->
  <p>
    <img src="https://komarev.com/ghpvc/?username=om7035&label=PROFILE+VISITS&color=blueviolet&style=for-the-badge" alt="Profile Views" />
  </p>

  <!-- Premium Trophy Display -->
  <img src="https://github-profile-trophy.vercel.app/?username=om7035&theme=nord&column=7&no-frame=true&margin-w=15" width="100%" alt="Achievement Trophies" />

</div>

<!-- Interactive Table of Contents with Emoji Icons -->
<h2 id="navigate-my-universe">📚 Navigate My Universe</h2>
<p align="center">
  <a href="#about-me">👨‍💻 About Me</a> • 
  <a href="#expertise">🧠 Expertise</a> • 
  <a href="#tech-ecosystem">⚙️ Tech Ecosystem</a> • 
  <a href="#showcase-projects">🏆 Showcase Projects</a> • 
  <a href="#contribution-galaxy">📊 Contribution Galaxy</a> • 
  <a href="#connect">🤝 Connect</a> • 
  <a href="#beyond-code">✨ Beyond Code</a>
</p>

<!-- Light/Dark Mode Toggle -->
<div align="center" style="margin: 20px 0;">
  <label for="mode-toggle" class="mode-switch">
    <input type="checkbox" id="mode-toggle" />
    <span>🌞 Light / 🌜 Dark</span>
  </label>
</div>

<script>
  const toggle = document.getElementById('mode-toggle');
  const body = document.body;

  // Apply saved theme preference
  if (localStorage.getItem('theme') === 'dark') {
    body.classList.add('dark-mode');
    toggle.checked = true;
  }

  toggle.addEventListener('change', () => {
    if (toggle.checked) {
      body.classList.add('dark-mode');
      localStorage.setItem('theme', 'dark');
    } else {
      body.classList.remove('dark-mode');
      localStorage.setItem('theme', 'light');
    }
  });
</script>

<style>
  /* Light/Dark Mode Styling */
  body {
    background-color: #fefefe;
    color: #111;
    transition: all 0.4s ease;
    font-family: 'Montserrat', sans-serif;
  }
  body.dark-mode {
    background-color: #121212;
    color: #e0e0e0;
  }

  /* Mode Toggle Styling */
  .mode-switch {
    cursor: pointer;
    display: inline-block;
    border-radius: 10px;
    border: 1px solid #ccc;
    background-color: #f0f0f0;
    transition: all 0.3s ease;
    padding: 10px 20px;
  }
  body.dark-mode .mode-switch {
    background-color: #1f1f1f;
    border-color: #444;
  }
  .mode-switch input {
    display: none;
  }
  .mode-switch span {
    font-weight: bold;
  }

  /* Links Adapt to Theme */
  a {
    color: #0077b6;
    text-decoration: none;
    transition: color 0.3s ease;
  }
  body.dark-mode a {
    color: #90cdf4;
  }

  /* Tables and badges */
  table {
    width: 100%;
    margin: 20px 0;
    border-collapse: collapse;
  }
  td {
    padding: 10px;
    vertical-align: top;
  }
  img {
    transition: filter 0.3s ease;
  }
  body.dark-mode img {
    filter: brightness(0.95);
  }
</style>
