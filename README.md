<!-- ============  STYLE  ============ -->
<style>
  :root { --bg: #121212; --card: #1e1e1e; --text: #e1e1e1; --accent: #4ade80; }
  .container { max-width: 800px; margin: 0 auto; padding: 20px; }
  .card { background: var(--card); border-radius: 16px; overflow: hidden; box-shadow: 0 8px 32px rgba(0,0,0,.3); margin-bottom: 20px; }
  .header-img { width:100%; height:180px; object-fit:cover; }
  .profile { padding:24px; text-align:center; margin-top:-60px; }
  .avatar { width:120px; height:120px; border-radius:50%; border:5px solid var(--card); box-shadow:0 8px 20px rgba(0,0,0,.4); }
  h1 { margin:16px 0 8px; font-size:28px; color:#fff; }
  .title { color:var(--accent); font-weight:600; font-size:18px; margin:4px 0; }
  .bio { color:#b3b3b3; font-size:15px; line-height:1.6; margin:16px 0; }
  .divider { height:1px; background:#333; margin:20px 0; }
  .section { padding:0 24px 20px; }
  .section-title { color:#fff; font-size:18px; font-weight:600; margin:0 0 12px; display:flex; align-items:center; gap:8px; }
  .edu { color:#fff; font-weight:600; }
  .edu-sub { color:var(--accent); font-weight:500; }
  .edu-minor { color:#aaa; font-style:italic; font-size:14px; }
  .skills { display:flex; flex-wrap:wrap; gap:10px; justify-content:center; margin:16px 0; }
  .skills img { height:42px; }
  .connect a { color:var(--accent); text-decoration:none; font-weight:500; }
  .footer { text-align:center; color:#666; font-size:13px; margin-top:30px; }
  .spotify-card { max-width:400px; border-radius:12px; overflow:hidden; box-shadow:0 8px 24px rgba(0,0,0,.4); }
</style>

<div class="container">

<!-- ============  BANNER + PROFILE  ============ -->
<div class="card">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=30&pause=1000&color=F2F2F2&center=true&vCenter=true&width=800&height=180&lines=%E0%B8%A0%E0%B8%B2%E0%B8%A9%E0%B8%B2%E0%B9%84%E0%B8%97%E0%B8%A2+%7C+ENGLISH;BANGKOK+UNIVERSITY;IT+%26+Innovation;CS+-+Data+Science+%26+Cybersecurity&background=F8F9FA00&gradient=003087,FFD700,003087"
       alt="Header" class="header-img">

  <div class="profile">
    <img src="YOUR_AVATAR_URL" alt="Charcrit" class="avatar">
    <h1>Charcrit</h1>
    <p class="title">Backend Dev • Cybersecurity Enthusiast</p>
    <p class="bio">
      I’m a Computer Science student majoring in Cyber Security @ Bangkok University.  
      Passionate about building secure systems, ethical hacking, and protecting the digital world.
    </p>
  </div>
</div>

<!-- ============  EDUCATION  ============ -->
<div class="card">
  <div class="section">
    <h2 class="section-title">Education</h2>
    <p class="edu">BANGKOK UNIVERSITY</p>
    <p class="edu-sub">School of Information Technology and Innovation</p>
    <p class="edu-minor">Computer Science - Data Science and Cybersecurity</p>
  </div>
</div>

<!-- ============  TOOLS & TECH  ============ -->
<div class="card">
  <div class="section">
    <h2 class="section-title">Tools & Technologies</h2>
    <div class="skills">
      <img src="https://skillicons.dev/icons?i=go,python,vscode,figma,postman,docker,mysql,sqlite">
    </div>
  </div>
</div>

<!-- ============  CONNECT  ============ -->
<div class="card">
  <div class="section connect">
    <h2 class="section-title">Let's Connect!</h2>
    <p><a href="mailto:Charcrith@gmail.com">Charcrith@gmail.com</a></p>
  </div>
</div>

<!-- ============  SPOTIFY CARD  ============ -->
<div align="center">
  <a href="https://github.com/kittinan/spotify-github-profile">
    <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=31xbnckh5sidm34aq5iiarqq5b5m&cover_image=true&theme=default&show_offline=true&background_color=121212&interchange=false&profanity=false&bar_color_cover=false"
         alt="Spotify Now Playing" class="spotify-card">
  </a>
</div>

<!-- ============  FOOTER  ============ -->
<div class="footer">
  <i style="color:#003087;">— Bangkok University —</i>
</div>

</div>
