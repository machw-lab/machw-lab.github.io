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
  .team-grid {
    display: grid;
    /* Responsive columns: 4 by default, adjusts based on screen width */
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    text-align: center;
    font-family: sans-serif;
  }

  /* Force exactly 4 columns on desktop screens */
  @media (min-width: 900px) {
    .team-grid {
      grid-template-columns: repeat(4, 1fr);
    }
  }

  .team-member {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .team-member img {
    width: 250px;
    height: 250px;
    max-width: 100%;
    object-fit: cover;
    border-radius: 8px;
    margin: 0 auto 10px;
    transition: transform 0.2s ease;
    display: block;
  }

  .team-member img.deglare {
    object-fit: contain;
    padding: 16px;
    background: #ffffff;
  }

  .team-member img:hover {
    transform: scale(1.03);
  }

  .name-link {
    font-weight: bold;
    text-decoration: none;
    color: #333;
    margin-top: 5px;
    display: block;
  }

  .title {
    font-size: 0.9em;
    color: #666;
  }
</style>

<img src="/images/banner.png" alt="Landscape" style="width:100%;" />

<div class="container-fluid">
    <div class="justify-content-center row">
        <div class="col col-auto col-lg-8 px-0">
            <p class="lead mb-0 text-center">Based in the Department of Computer Sciences at the University of Wisconsin–Madison, our research group, MachW Lab, is engineering the future of wireless systems. Our research is in developing high-fidelity sensing and communication technologies that seamlessly bridge the gap between the physical world and autonomous machines. Our work addresses critical challenges across robotics, automotive systems, healthcare, and human-computer interaction.
            </p>
        </div>
    </div>
</div>

---

<h3>Recent Research</h3>
<div class="team-grid">
  <div class="team-member">
    <a href="/files/umbra-sensorsj26.pdf">
      <img src="/images/umbra.jpg">
    </a>
    <a href="/" class="name-link">Millimeter wave inverse pinhole imaging</a>
    <span class="title">IEEE Sensors Journal 2026</span>
  </div>

  <div class="team-member">
    <a href="/files/polypulse-naturecomms26.pdf">
      <img src="/images/polypulse.jpg">
    </a>
    <a href="/files/polypulse-naturecomms26.pdf" class="name-link">Multi-site pulse transit time with radars</a>
    <span class="title">Nature Communications 2026</span>
  </div>

  <div class="team-member">
    <a href="/files/deglare-cvpr26.pdf" style="display:block;">
      <img src="/images/deglare.jpg" class="deglare" alt="Deglare research image">
    </a>
    <a href="/files/deglare-cvpr26.pdf" class="name-link">Solid state lidars have a glare problem, we fix it</a>
    <span class="title">CVPR 2026</span>
  </div>

  <div class="team-member">
    <a href="/files/sharp-hotmobile26.pdf">
      <img src="/images/sharp.png">
    </a>
    <a href="/files/sharp-hotmobile26.pdf" class="name-link">Privacy of raw streams in cooperative perception</a>
    <span class="title">HotMobile 2026</span>
  </div>

  <div class="team-member">
    <a href="/files/radarsim-3dv26.pdf">
      <img src="/images/radar_sim.jpg">
    </a>
    <a href="/files/radarsim-3dv26.pdf" class="name-link">Radar simulators with multimodal (radar + camera) NeRFs</a>
    <span class="title">3D Vision 2026</span>
  </div>

  <div class="team-member">
    <a href="/files/grt-iccv25.pdf">
      <img src="/images/grt.jpg">
    </a>
    <a href="/files/grt-iccv25.pdf" class="name-link">Foundational Models for mmWave Radars</a>
    <span class="title">ICCV 2025</span>
  </div>

  <div class="team-member">
    <a href="/files/metamorph-icra25.pdf">
      <img src="/images/metamorph.png">
    </a>
    <a href="/files/metamorph-icra25.pdf" class="name-link">Wireless field programming with soft robotics</a>
    <span class="title">ICRA 2025</span>
  </div>
</div>

---
<h3>News</h3>

<p>
<ul>
<li><em>May 26</em>: Umbra accepted @ IEEE Sensors Journal 26
<li><em>Mar 26</em>: Congrats to Jiangyifei, Kuang and team for PolyPulse @ Nature Communications 26
<li><em>Feb 26</em>: Congrats to Avery, Connor and team for accepted paper at CVPR 26 
<li><em>Dec 25</em>: Congrats to Bangya Liu and team for Sharp @ HotMobile 26 
<li><em>Nov 25</em>: Congrats to Sally Chen for RadarSim @ 3DV 26
<li><em>Oct 25</em>: Congrats to Tianshu Huang for GRT oral @ ICCV 25 
</ul>
</p>

---

<!-- 
To dos:

Add a project categorization folder
Add a project page for each work
Add sponsor page

 -->
