<style>
  .uiverse-card {
    position: relative;
    width: 380px;
    padding: 24px;
    border-radius: 20px;
    background: #161b22;
    color: #fff;
    font-family: 'Segoe UI', sans-serif;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
  }
  /* Animated Uiverse Neon Conic Border */
  .uiverse-card::before {
    content: "";
    position: absolute;
    inset: -2px;
    border-radius: 22px;
    background: linear-gradient(45deg, #00f7ff, #a855f7, #ff007f, #00f7ff);
    background-size: 300% 300%;
    animation: neonBorder 6s ease infinite;
    z-index: -1;
  }
  .uiverse-card::after {
    content: "";
    position: absolute;
    inset: 2px;
    background: #161b22;
    border-radius: 18px;
    z-index: -1;
  }
  @keyframes neonBorder {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  .uiverse-header {
    display: flex;
    align-items: center;
    gap: 8px;
    margin-bottom: 16px;
  }
  .dot { width: 12px; height: 12px; border-radius: 50%; }
  .red { background: #ff5f56; }
  .yellow { background: #ffbd2e; }
  .green { background: #27c93f; }
  .uiverse-title {
    font-size: 1.4rem;
    font-weight: 700;
    background: linear-gradient(90deg, #00f7ff, #a855f7);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin: 0 0 6px 0;
  }
  .uiverse-sub {
    color: #8b949e;
    font-size: 0.9rem;
    margin-bottom: 18px;
  }
  .uiverse-socials {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  }
  .uiverse-btn {
    padding: 8px 14px;
    border-radius: 10px;
    background: #21262d;
    color: #fff;
    text-decoration: none;
    font-size: 0.85rem;
    font-weight: 600;
    border: 1px solid #30363d;
    transition: all 0.25s ease;
  }
  .uiverse-btn:hover {
    transform: translateY(-3px);
    border-color: #00f7ff;
    box-shadow: 0 0 15px rgba(0, 247, 255, 0.45);
    color: #00f7ff;
  }
</style>

<div class="uiverse-card">
  <div class="uiverse-header">
    <span class="dot red"></span>
    <span class="dot yellow"></span>
    <span class="dot green"></span>
  </div>
  <h2 class="uiverse-title">Eyad Wael</h2>
  <p class="uiverse-sub">Passionate Developer from Asyut • JS & React[cite: 1]</p>
  <div class="uiverse-socials">
    <a href="https://github.com/eyad09268" target="_blank" class="uiverse-btn">GitHub</a>
    <a href="https://codepen.io/eyad-wael" target="_blank" class="uiverse-btn">CodePen</a>
    <a href="https://instagram.com/its_eyadwael" target="_blank" class="uiverse-btn">Instagram</a>
    <a href="https://x.com/eyad09268" target="_blank" class="uiverse-btn">X</a>
    <a href="https://tiktok.com/@its_eyad_wael" target="_blank" class="uiverse-btn">TikTok</a>
    <a href="https://guns.lol/eyad09268" target="_blank" class="uiverse-btn">Guns.lol</a>
    <a href="http://eyad-wael.rf.gd/" target="_blank" class="uiverse-btn">Portfolio</a>
  </div>
</div>
