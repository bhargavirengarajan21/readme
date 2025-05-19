<!-- GitHub Profile README - HTML embedded version for Bhargavi Rengarajan -->

<h1 align="center">Hey, I'm <span style="color:#ff66cc;">Bhargavi Rengarajan</span> 🌸</h1>
<h3 align="center">Engineer @ Heart | Researcher @ Mind | Creator Always 🚀</h3>

<p align="center">
  <a href="https://bhargavi-r-21.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-000?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/bhargavirengarajan21" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:breng002@ucr.edu">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<hr />

<p align="center"><em>💡 I build things that make people's lives better — from full-stack products to AI tools, to just one clean line of code.</em></p>

<hr />

<h2>🔭 A Quick Story About Me</h2>

<pre>
const bhargavi = {
  currentRole: "Graduate Student @ UCR",
  previous: "Senior Software Engineer @ Mr. Cooper (FinTech)",
  interests: ["AI", "Computer Vision", "Web3", "Data Viz", "System Design"],
  funFact: "I once built a music player controlled entirely by hand gestures 🎵🖐️",
};
</pre>

<p>
I've led engineering teams, mentored new developers, and shipped user-loved products. 
Whether it's building scalable backend services or intuitive UI workflows, I approach every challenge from both a developer's and a user's perspective.
</p>

<hr />



<div style="font-family: Arial, sans-serif; max-width: 500px; margin: 0 auto;">
  <h2>👩‍💻 Tech Stack</h2>
  <div style="display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 20px;">
    <span style="background: #f7df1e; color: #000; padding: 5px 10px; border-radius: 5px;">Docker</span>
    <span style="background: #326ce5; color: #fff; padding: 5px 10px; border-radius: 5px;">Kubernetes</span>
    <span style="background: #232f3e; color: #fff; padding: 5px 10px; border-radius: 5px;">AWS</span>
    <span style="background: #24292e; color: #fff; padding: 5px 10px; border-radius: 5px;">GitHub Actions</span>
    <span style="background: #f34b7d; color: #fff; padding: 5px 10px; border-radius: 5px;">DevOps</span>
  </div>

  <h2>🔎 Search My Projects</h2>
  <input type="text" id="searchInput" placeholder="Enter keyword..." style="width: 100%; padding: 8px; margin-bottom: 10px; border-radius: 4px; border: 1px solid #ccc;">
  <ul id="projectList" style="list-style: none; padding: 0;">
    <!-- Filtered projects will appear here -->
  </ul>
</div>
<hr />

<h2>📚 Currently Learning</h2>
<ul>
  <li>LLM APIs (OpenAI, Gemini, Ollama)</li>
  <li>AI x Blockchain collab tools</li>
  <li>Systems Design Interview prep</li>
</ul>

<hr />

<h2>📈 GitHub Activity</h2>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bhargavirengarajan21&show_icons=true&theme=radical&hide=contribs&count_private=true" height="150" />
  <img src="https://streak-stats.demolab.com?user=bhargavirengarajan21&theme=radical" height="150" />
</p>

<hr />

<h2>💬 Let’s Build Something Together</h2>

<p>I’m open to:</p>
<ul>
  <li>🎨 AI + design-driven apps</li>
  <li>⚡ Fast-paced startups in Web3/media-tech</li>
  <li>🎓 Mentoring students or interns in tech</li>
</ul>

<p><b>📫 Email:</b> <a href="mailto:breng002@ucr.edu">breng002@ucr.edu</a></p>
<p><b>🌐 Portfolio:</b> <a href="https://bhargavi-r-21.vercel.app">bhargavi-r-21.vercel.app</a></p>

<script>
  // Replace with your actual project list and descriptions
  const projects = [
    { name: "docker-storage-commands", url: "https://github.com/bhargavirengarajan21/docker-storage-commands", desc: "Docker storage commands and best practices" },
    { name: "kubernetes-labs", url: "#", desc: "Kubernetes labs and tutorials" },
    { name: "aws-static-site", url: "#", desc: "Host static website on AWS S3" },
    { name: "github-actions-ci", url: "#", desc: "CI/CD pipelines using GitHub Actions" },
    { name: "devops-notes", url: "#", desc: "DevOps notes and resources" }
  ];

  function filterProjects(keyword) {
    return projects
      .filter(p => (p.name + " " + p.desc).toLowerCase().includes(keyword.toLowerCase()))
      .slice(0, 3);
  }

  document.getElementById('searchInput').addEventListener('input', function() {
    const keyword = this.value;
    const filtered = filterProjects(keyword);
    const list = document.getElementById('projectList');
    list.innerHTML = '';
    if (filtered.length === 0 && keyword) {
      list.innerHTML = '<li>No projects found.</li>';
    } else {
      filtered.forEach(p => {
        list.innerHTML += `<li><a href="${p.url}" target="_blank" style="text-decoration:none;color:#0366d6;"><strong>${p.name}</strong></a><br><small>${p.desc}</small></li>`;
      });
    }
  });
</script>
<hr />

<blockquote>
  <em>"A good product tells a story. A great engineer makes sure it's one worth listening to."</em>
</blockquote>
