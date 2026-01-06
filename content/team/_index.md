+++
[paige.pages]
disable_collections = true
disable_pages = true
disable_sections = true
+++
<style>
  /* Target the navigation links in the menu */
  .nav-link {
      font-size: 1.25rem !important; /* Makes the text larger (adjust as needed) */
      padding-left: 20px !important;  /* Adds horizontal spacing between links */
      padding-right: 20px !important;
      font-weight: 500;               /* Optional: makes the text slightly bolder */
  }
        a {
      color: #326CF4;  /* typical default link blue */
  }
  body {
      color: #000000 !important;
      background-color: #ffffff !important;
  }
  /* Override any dark mode rules */
  @media (prefers-color-scheme: dark) {
      body, h1, h2, h3, h4 {
          color: #000000 !important;
          background-color: #ffffff !important;
      }
    a {
      color: #326CF4;  /* typical default link blue */
  }
  }


.nav-link, 
.navbar-nav a, 
.paige-header-nav a {
    text-decoration: none !important;
}
  /* This forces the style directly into the HTML head */
  a {
    text-decoration: none !important;
  }
</style>

<style>
  /* Global Link Style */
  a {
    text-decoration: none !important;
  }

  .team-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    text-align: center;
    font-family: sans-serif;
  }

  @media (min-width: 900px) {
    .team-grid {
      grid-template-columns: repeat(4, 1fr);
    }
  }

  .team-member {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-decoration: none !important; /* Ensure the whole block doesn't underline */
  }

  /* Image styling */
  .team-member img {
    width: 100%;
    max-width: 250px;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    border-radius: 8px;
    margin-bottom: 10px;
    transition: transform 0.2s ease;
  }

  .team-member:hover img {
    transform: scale(1.03);
  }

  .name-link {
    font-weight: bold;
    color: #333;
    margin-top: 5px;
    display: block;
  }

  /* --- HOVER SWAP LOGIC --- */
  .info-container {
    font-size: 0.9em;
    color: #666;
    height: 1.2em; /* Prevents layout jumping */
    position: relative;
    width: 100%;
  }

  .email-address {
    display: none; /* Hidden by default */
    color: #007bff;
    font-family: monospace;
  }

  /* When the team-member div is hovered, swap the title for the email */
  .team-member:hover .title {
    display: none;
  }
  
  .team-member:hover .email-address {
    display: inline-block;
  }
</style>

<img src="/images/banner.png" alt="Landscape" style="width:100%;" />

<br>
<br>
<h3>Team</h3>
<div class="team-grid">
  
  <div class="team-member">
    <a href="https://akarsh-prabhakara.github.io">
      <img src="/images/akarsh.png" alt="Akarsh Prabhakara">
    </a>
    <a href="https://akarsh-prabhakara.github.io" class="name-link">Akarsh Prabhakara</a>
    <div class="info-container">
      <span class="title">Assistant Professor</span>
      <span class="email-address">akarsh@cs.wisc.edu</span>
    </div>
  </div>

  <div class="team-member">
    <a href="/">
      <img src="/images/xxc.png" alt="Xincheng Xie">
    </a>
    <a href="/" class="name-link">Xincheng Xie</a>
    <div class="info-container">
      <span class="title">Ph.D. Student</span>
      <span class="email-address">xxc@cs.wisc.edu</span>
    </div>
  </div>

  <div class="team-member">
    <a href="/">
      <img src="/images/brian.png" alt="Brian Zheng">
    </a>
    <a href="/" class="name-link">Brian Zheng</a>
    <div class="info-container">
      <span class="title">Ph.D. Student</span>
      <span class="email-address">zzheng94@wisc.edu</span>
    </div>
  </div>

  <div class="team-member">
    <a href="/">
      <img src="/images/hongyang.png" alt="Hongyang Li">
    </a>
    <a href="/" class="name-link">Hongyang Li</a>
    <div class="info-container">
      <span class="title">Ph.D. Student</span>
      <span class="email-address">hli2269@wisc.edu</span>
    </div>
  </div>

</div>