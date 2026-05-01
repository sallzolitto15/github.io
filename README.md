<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Space Jam Fan Zone 🏀</title>

  <!--BEGIN QUALTRICS WEBSITE FEEDBACK SNIPPET-->

<script type='text/javascript'>

(function(){var g=function(g){

this.go=function(){var a=document.createElement("script");a.type="text/javascript";a.src=g;document.body&&document.body.appendChild(a)};

this.start=function(){var t=this;"complete"!==document.readyState?window.addEventListener?window.addEventListener("load",function(){t.go()},!1):window.attachEvent&&window.attachEvent("onload",function(){t.go()}):t.go()};};

try{(new g("https://zn3rwu5knx2dqx04k-ugamsandbox.siteintercept.qualtrics.com/SIE/?Q_ZID=ZN_3Rwu5knX2Dqx04k")).start()}catch(i){}})();

</script><div id='ZN_3Rwu5knX2Dqx04k'><!--DO NOT REMOVE-CONTENTS PLACED HERE--></div>

<!--END WEBSITE FEEDBACK SNIPPET-->

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Boogaloo&family=Permanent+Marker&family=VT323&family=Rubik:wght@400;700;900&display=swap" rel="stylesheet" />

  <style>
    :root {
      --jam-red:    #e8001a;
      --jam-blue:   #0032a0;
      --jam-yellow: #ffd600;
      --jam-black:  #0a0a0a;
      --jam-white:  #f5f0e8;
      --jam-orange: #ff6a00;
      --jam-teal:   #00b4d8;
      --star-color: #ffd600;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; }

    body {
      background-color: var(--jam-black);
      color: var(--jam-white);
      font-family: 'Rubik', sans-serif;
      overflow-x: hidden;
      cursor: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='32' height='32' viewBox='0 0 32 32'><circle cx='16' cy='16' r='14' fill='%23e8001a' stroke='%23000' stroke-width='2'/><path d='M16 2 Q22 10 22 16 Q22 22 16 30 Q10 22 10 16 Q10 10 16 2Z' fill='%23000'/><path d='M2 16 Q10 10 16 10 Q22 10 30 16 Q22 22 16 22 Q10 22 2 16Z' fill='%23000'/></svg>"), auto;
    }

    /* ── STAR FIELD BACKGROUND ── */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background-image:
        radial-gradient(1px 1px at 10% 20%, white 0%, transparent 100%),
        radial-gradient(1px 1px at 30% 80%, white 0%, transparent 100%),
        radial-gradient(2px 2px at 50% 10%, var(--star-color) 0%, transparent 100%),
        radial-gradient(1px 1px at 70% 60%, white 0%, transparent 100%),
        radial-gradient(2px 2px at 85% 30%, white 0%, transparent 100%),
        radial-gradient(1px 1px at 15% 50%, var(--star-color) 0%, transparent 100%),
        radial-gradient(1px 1px at 55% 75%, white 0%, transparent 100%),
        radial-gradient(1px 1px at 90% 90%, var(--star-color) 0%, transparent 100%),
        radial-gradient(1px 1px at 40% 40%, white 0%, transparent 100%),
        radial-gradient(2px 2px at 25% 95%, white 0%, transparent 100%);
      pointer-events: none;
      z-index: 0;
    }

    /* ── SCANLINES OVERLAY ── */
    body::after {
      content: '';
      position: fixed;
      inset: 0;
      background: repeating-linear-gradient(
        0deg,
        transparent,
        transparent 2px,
        rgba(0,0,0,0.07) 2px,
        rgba(0,0,0,0.07) 4px
      );
      pointer-events: none;
      z-index: 999;
    }

    /* ── MARQUEE ── */
    .marquee-bar {
      background: var(--jam-red);
      border-top: 3px solid var(--jam-yellow);
      border-bottom: 3px solid var(--jam-yellow);
      padding: 6px 0;
      overflow: hidden;
      white-space: nowrap;
      position: relative;
      z-index: 10;
    }
    .marquee-inner {
      display: inline-block;
      animation: marquee 18s linear infinite;
      font-family: 'VT323', monospace;
      font-size: 1.2rem;
      letter-spacing: 0.12em;
      color: var(--jam-yellow);
    }
    @keyframes marquee {
      from { transform: translateX(100vw); }
      to   { transform: translateX(-100%); }
    }

    /* ── HERO ── */
    .hero {
      position: relative;
      z-index: 1;
      text-align: center;
      padding: 60px 20px 40px;
      background: radial-gradient(ellipse at 50% 0%, #0032a066 0%, transparent 70%);
    }

    .hero-eyebrow {
      font-family: 'VT323', monospace;
      font-size: 1.4rem;
      color: var(--jam-teal);
      letter-spacing: 0.3em;
      text-transform: uppercase;
      margin-bottom: 8px;
      animation: blink 1.4s step-end infinite;
    }
    @keyframes blink { 50% { opacity: 0; } }

    .hero-title {
      font-family: 'Permanent Marker', cursive;
      font-size: clamp(3rem, 10vw, 7rem);
      line-height: 1;
      color: var(--jam-yellow);
      text-shadow:
        4px 4px 0 var(--jam-red),
        8px 8px 0 var(--jam-blue),
        -2px -2px 20px rgba(255,214,0,0.4);
      animation: titleWobble 3s ease-in-out infinite;
      margin-bottom: 12px;
    }
    @keyframes titleWobble {
      0%, 100% { transform: rotate(-1deg) scale(1); }
      50%       { transform: rotate(1deg) scale(1.02); }
    }

    .hero-sub {
      font-family: 'Boogaloo', cursive;
      font-size: clamp(1.1rem, 3vw, 1.6rem);
      color: var(--jam-white);
      letter-spacing: 0.05em;
      margin-bottom: 32px;
      opacity: 0.9;
    }

    .ball-bounce {
      font-size: 5rem;
      display: inline-block;
      animation: bounce 0.7s ease-in-out infinite alternate;
      cursor: pointer;
      transition: transform 0.1s;
      user-select: none;
    }
    .ball-bounce:active { transform: scale(0.8) translateY(10px); }
    @keyframes bounce {
      from { transform: translateY(0) rotate(0deg); }
      to   { transform: translateY(-24px) rotate(20deg); }
    }

    /* ── NAV ── */
    nav {
      position: relative;
      z-index: 10;
      display: flex;
      justify-content: center;
      gap: 6px;
      flex-wrap: wrap;
      padding: 16px 20px;
      background: rgba(0,0,0,0.6);
      border-top: 2px solid var(--jam-blue);
      border-bottom: 2px solid var(--jam-blue);
    }
    nav a {
      font-family: 'Boogaloo', cursive;
      font-size: 1rem;
      color: var(--jam-yellow);
      text-decoration: none;
      padding: 6px 16px;
      border: 2px solid var(--jam-yellow);
      border-radius: 4px;
      transition: background 0.15s, color 0.15s, transform 0.15s;
      letter-spacing: 0.05em;
    }
    nav a:hover {
      background: var(--jam-yellow);
      color: var(--jam-black);
      transform: translateY(-2px) rotate(-1deg);
    }

    /* ── SECTIONS ── */
    section {
      position: relative;
      z-index: 1;
      max-width: 1100px;
      margin: 0 auto;
      padding: 60px 24px;
    }

    .section-title {
      font-family: 'Permanent Marker', cursive;
      font-size: clamp(1.8rem, 5vw, 3rem);
      color: var(--jam-yellow);
      text-shadow: 3px 3px 0 var(--jam-red);
      margin-bottom: 32px;
      display: flex;
      align-items: center;
      gap: 12px;
    }

    /* ── DIVIDER ── */
    .divider {
      border: none;
      border-top: 3px dashed var(--jam-blue);
      margin: 0 auto;
      max-width: 900px;
      opacity: 0.5;
    }

    /* ── ROSTER CARDS ── */
    .roster-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 20px;
    }

    .player-card {
      background: linear-gradient(135deg, #0032a0 0%, #001560 100%);
      border: 3px solid var(--jam-yellow);
      border-radius: 8px;
      padding: 24px 16px;
      text-align: center;
      transition: transform 0.2s, box-shadow 0.2s;
      cursor: pointer;
      position: relative;
      overflow: hidden;
    }
    .player-card::before {
      content: '';
      position: absolute;
      top: -50%;
      left: -50%;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle, rgba(255,214,0,0.08) 0%, transparent 60%);
      pointer-events: none;
    }
    .player-card:hover {
      transform: translateY(-6px) rotate(-1deg);
      box-shadow: 0 12px 32px rgba(255,214,0,0.25);
    }
    .player-card:active {
      transform: scale(0.96);
    }
    .player-emoji { font-size: 3rem; display: block; margin-bottom: 8px; }
    .player-name {
      font-family: 'Permanent Marker', cursive;
      font-size: 1.1rem;
      color: var(--jam-yellow);
      margin-bottom: 4px;
    }
    .player-pos {
      font-family: 'VT323', monospace;
      font-size: 0.95rem;
      color: var(--jam-teal);
      letter-spacing: 0.1em;
    }

    /* ── BROKEN BUTTON SECTION (rage click bait) ── */
    .rage-section {
      background: linear-gradient(135deg, #1a0000, #0a0a0a);
      border: 3px solid var(--jam-red);
      border-radius: 12px;
      padding: 40px;
      text-align: center;
      margin: 0 24px;
      max-width: 900px;
      margin-left: auto;
      margin-right: auto;
      position: relative;
      z-index: 1;
    }
    .rage-label {
      font-family: 'VT323', monospace;
      font-size: 0.9rem;
      color: var(--jam-red);
      letter-spacing: 0.3em;
      text-transform: uppercase;
      margin-bottom: 8px;
      opacity: 0.7;
    }
    .rage-title {
      font-family: 'Permanent Marker', cursive;
      font-size: clamp(1.4rem, 4vw, 2rem);
      color: var(--jam-white);
      margin-bottom: 12px;
    }
    .rage-desc {
      font-size: 0.95rem;
      color: rgba(245,240,232,0.7);
      margin-bottom: 28px;
      line-height: 1.6;
    }
    .btn-broken {
      display: inline-block;
      font-family: 'Boogaloo', cursive;
      font-size: 1.2rem;
      padding: 14px 36px;
      background: var(--jam-red);
      color: var(--jam-white);
      border: 3px solid var(--jam-yellow);
      border-radius: 6px;
      cursor: pointer;
      letter-spacing: 0.05em;
      transition: transform 0.1s;
      position: relative;
    }
    .btn-broken:hover { opacity: 0.9; }
    .btn-broken:active { transform: scale(0.97); }
    .btn-broken.wiggle { animation: wiggle 0.4s ease; }
    @keyframes wiggle {
      0%,100% { transform: translateX(0); }
      25%      { transform: translateX(-6px) rotate(-2deg); }
      75%      { transform: translateX(6px) rotate(2deg); }
    }
    .click-counter {
      margin-top: 16px;
      font-family: 'VT323', monospace;
      font-size: 1.3rem;
      color: var(--jam-yellow);
      min-height: 1.5rem;
    }

    /* ── HEATMAP SECTION ── */
    .heatmap-section {
      max-width: 1100px;
      margin: 0 auto;
      padding: 40px 24px;
      position: relative;
      z-index: 1;
    }
    .link-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
      gap: 12px;
    }
    .hm-link {
      display: block;
      font-family: 'Boogaloo', cursive;
      font-size: 1rem;
      text-align: center;
      padding: 14px 10px;
      background: rgba(0,50,160,0.3);
      border: 2px solid var(--jam-blue);
      border-radius: 6px;
      color: var(--jam-white);
      text-decoration: none;
      transition: background 0.2s, border-color 0.2s, transform 0.15s;
      cursor: pointer;
    }
    .hm-link:hover {
      background: rgba(0,50,160,0.7);
      border-color: var(--jam-teal);
      transform: scale(1.04);
      color: var(--jam-yellow);
    }

    /* ── SCOREBOARD ── */
    .scoreboard {
      background: #000;
      border: 4px solid var(--jam-yellow);
      border-radius: 10px;
      padding: 32px;
      font-family: 'VT323', monospace;
      font-size: clamp(1.2rem, 3vw, 1.8rem);
      text-align: center;
      box-shadow: 0 0 30px rgba(255,214,0,0.2), inset 0 0 20px rgba(0,0,0,0.8);
    }
    .score-row {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .score-team { color: var(--jam-teal); letter-spacing: 0.1em; }
    .score-num {
      font-size: clamp(2.5rem, 8vw, 5rem);
      color: var(--jam-yellow);
      text-shadow: 0 0 20px rgba(255,214,0,0.6);
      line-height: 1;
    }
    .score-vs { color: var(--jam-red); font-size: 1.5rem; }
    .score-period {
      margin-top: 12px;
      color: rgba(245,240,232,0.5);
      font-size: 1rem;
      letter-spacing: 0.2em;
      animation: blink 1.4s step-end infinite;
    }

    /* ── GUESTBOOK ── */
    .guestbook {
      background: rgba(0,50,160,0.15);
      border: 3px solid var(--jam-blue);
      border-radius: 10px;
      padding: 32px;
    }
    .guestbook textarea {
      width: 100%;
      background: #000;
      border: 2px solid var(--jam-yellow);
      border-radius: 6px;
      color: var(--jam-yellow);
      font-family: 'VT323', monospace;
      font-size: 1.2rem;
      padding: 12px;
      resize: vertical;
      min-height: 100px;
      outline: none;
      margin-bottom: 12px;
    }
    .guestbook textarea::placeholder { color: rgba(255,214,0,0.35); }
    .guestbook textarea:focus { border-color: var(--jam-teal); box-shadow: 0 0 12px rgba(0,180,216,0.3); }
    .btn-submit {
      font-family: 'Boogaloo', cursive;
      font-size: 1.1rem;
      padding: 10px 28px;
      background: var(--jam-blue);
      color: var(--jam-yellow);
      border: 2px solid var(--jam-yellow);
      border-radius: 6px;
      cursor: pointer;
      transition: background 0.2s, transform 0.15s;
    }
    .btn-submit:hover {
      background: var(--jam-yellow);
      color: var(--jam-blue);
      transform: translateY(-2px);
    }
    .guestbook-entries {
      margin-top: 24px;
      display: flex;
      flex-direction: column;
      gap: 12px;
    }
    .entry {
      background: rgba(0,0,0,0.5);
      border-left: 4px solid var(--jam-red);
      padding: 10px 14px;
      font-family: 'VT323', monospace;
      font-size: 1.1rem;
      color: var(--jam-white);
      border-radius: 0 6px 6px 0;
    }
    .entry-meta { font-size: 0.85rem; color: var(--jam-teal); margin-bottom: 4px; }

    /* ── FOOTER ── */
    footer {
      position: relative;
      z-index: 1;
      text-align: center;
      padding: 40px 20px;
      background: rgba(0,0,0,0.8);
      border-top: 3px solid var(--jam-red);
      font-family: 'VT323', monospace;
      color: rgba(245,240,232,0.4);
      font-size: 1rem;
      letter-spacing: 0.1em;
    }
    footer a { color: var(--jam-yellow); text-decoration: none; }

    /* ── FLOATING BALLS ── */
    .floater {
      position: fixed;
      font-size: 2rem;
      pointer-events: none;
      z-index: 998;
      opacity: 0;
      animation: floatUp 4s ease-out forwards;
    }
    @keyframes floatUp {
      0%   { opacity: 1; transform: translateY(0) rotate(0deg); }
      100% { opacity: 0; transform: translateY(-200px) rotate(360deg); }
    }

    /* ── QUALTRICS NOTE ── */
    .q-badge {
      display: inline-block;
      background: rgba(0,180,216,0.15);
      border: 1px solid var(--jam-teal);
      border-radius: 20px;
      padding: 4px 14px;
      font-family: 'VT323', monospace;
      font-size: 1rem;
      color: var(--jam-teal);
      letter-spacing: 0.1em;
      margin-bottom: 8px;
    }
  </style>
</head>
<body>

  <!-- MARQUEE -->
  <div class="marquee-bar">
    <span class="marquee-inner">
      🏀 WELCOME TO THE JAM &nbsp;★&nbsp; TUNE SQUAD VS MONSTARS &nbsp;★&nbsp; MICHAEL JORDAN IS BACK &nbsp;★&nbsp; LOLA BUNNY FOREVER &nbsp;★&nbsp; 1996 &nbsp;★&nbsp; THAT'S WHAT I SAY &nbsp;★&nbsp; COME ON AND SLAM &nbsp;★&nbsp; WELCOME TO THE JAM &nbsp;★&nbsp; BUGS BUNNY IS GOATED &nbsp;★&nbsp;
    </span>
  </div>

  <!-- HERO -->
  <header class="hero">
    <div class="hero-eyebrow">★ OFFICIAL FAN ZONE ★ EST. 1996 ★</div>
    <h1 class="hero-title">SPACE JAM</h1>
    <p class="hero-sub">The greatest movie ever made. No further questions.</p>
    <div class="ball-bounce" id="heroBall" title="Click me!">🏀</div>
  </header>

  <!-- NAV -->
  <nav>
    <a href="#roster">🐰 Roster</a>
    <a href="#scoreboard">📊 Scoreboard</a>
    <a href="#links">🔗 Links</a>
    <a href="#feedback">💬 Feedback</a>
    <a href="#guestbook">📝 Guestbook</a>
  </nav>

  <!-- ROSTER -->
  <section id="roster">
    <h2 class="section-title">🐰 Tune Squad Roster</h2>
    <div class="roster-grid">
      <div class="player-card">
        <span class="player-emoji">🐰</span>
        <div class="player-name">Bugs Bunny</div>
        <div class="player-pos">PG · #1</div>
      </div>
      <div class="player-card">
        <span class="player-emoji">🦆</span>
        <div class="player-name">Daffy Duck</div>
        <div class="player-pos">SG · #2</div>
      </div>
      <div class="player-card">
        <span class="player-emoji">👩‍🦰</span>
        <div class="player-name">Lola Bunny</div>
        <div class="player-pos">SF · #10</div>
      </div>
      <div class="player-card">
        <span class="player-emoji">🐦</span>
        <div class="player-name">Tweety Bird</div>
        <div class="player-pos">PF · #3</div>
      </div>
      <div class="player-card">
        <span class="player-emoji">🥊</span>
        <div class="player-name">Taz</div>
        <div class="player-pos">C · #0</div>
      </div>
      <div class="player-card">
        <span class="player-emoji">🏀</span>
        <div class="player-name">Michael Jordan</div>
        <div class="player-pos">COACH · #23</div>
      </div>
    </div>
  </section>

  <hr class="divider" />

  <!-- SCOREBOARD -->
  <section id="scoreboard">
    <h2 class="section-title">📊 Final Score</h2>
    <div class="scoreboard">
      <div class="score-row">
        <div>
          <div class="score-team">TUNE SQUAD</div>
          <div class="score-num">78</div>
        </div>
        <div class="score-vs">VS</div>
        <div>
          <div class="score-team">MONSTARS</div>
          <div class="score-num">77</div>
        </div>
      </div>
      <div class="score-period">● FINAL · MORON MOUNTAIN ARENA · 1996</div>
    </div>
  </section>

  <hr class="divider" />

  <!-- RAGE CLICK BAIT -->
  <div class="rage-section" id="feedback">
    <div class="rage-label">⚠ Qualtrics DXA · Rage Click Demo</div>
    <h2 class="rage-title">Get Your FREE Space Jam Poster!</h2>
    <p class="rage-desc">
      Click the button below to claim your limited edition 1996 Space Jam commemorative poster.<br/>
      <em style="color: var(--jam-red); font-style:normal;">This button is intentionally broken to trigger rage click detection. 🎯</em>
    </p>
    <button class="btn-broken" id="brokenBtn">🏀 CLAIM FREE POSTER</button>
    <div class="click-counter" id="clickCounter"></div>
  </div>

  <!-- HEATMAP LINKS -->
  <div class="heatmap-section" id="links">
    <h2 class="section-title">🔗 Explore the Fan Zone</h2>
    <p style="margin-bottom:20px; color:rgba(245,240,232,0.6); font-size:0.95rem;">
      🗺 Click around — these links help demonstrate <strong style="color:var(--jam-teal)">Qualtrics heatmap tracking</strong>.
    </p>
    <div class="link-grid">
      <a class="hm-link" href="#roster">🐰 Meet the Squad</a>
      <a class="hm-link" href="#scoreboard">🏆 Final Score</a>
      <a class="hm-link" href="#" onclick="return false;">🎬 Watch Trailer</a>
      <a class="hm-link" href="#" onclick="return false;">🛒 Merch Store</a>
      <a class="hm-link" href="#" onclick="return false;">📸 Photo Gallery</a>
      <a class="hm-link" href="#" onclick="return false;">🎵 Soundtrack</a>
      <a class="hm-link" href="#" onclick="return false;">📰 Movie News</a>
      <a class="hm-link" href="#" onclick="return false;">🧢 Fan Art</a>
      <a class="hm-link" href="#" onclick="return false;">🎮 Mini Game</a>
      <a class="hm-link" href="#guestbook">📝 Guestbook</a>
    </div>
  </div>

  <hr class="divider" />

  <!-- GUESTBOOK -->
  <section id="guestbook">
    <h2 class="section-title">📝 Fan Guestbook</h2>
    <div class="q-badge">Session Replay Active Zone</div>
    <div class="guestbook">
      <p style="margin-bottom:16px; color:rgba(245,240,232,0.7); font-size:0.95rem;">
        Leave your mark, Tune Squad fan. Session replay is watching 👀
      </p>
      <textarea id="guestInput" placeholder="Leave a message for the Tune Squad..."></textarea>
      <button class="btn-submit" id="submitEntry">✍️ Sign Guestbook</button>
      <div class="guestbook-entries" id="entriesList">
        <div class="entry">
          <div class="entry-meta">SpaceJamFan99 · 12/25/1996</div>
          BEST MOVIE EVER. Bugs Bunny for MVP!!
        </div>
        <div class="entry">
          <div class="entry-meta">TuneSquadForever · 01/01/1997</div>
          Lola Bunny is everything. That's all.
        </div>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>🏀 SPACE JAM FAN ZONE · NOT AFFILIATED WITH WARNER BROS · MADE WITH ❤️ AND QUALTRICS DXA</p>
    <p style="margin-top:8px;">
      <span style="color:var(--jam-teal)">Session Replay</span> ·
      <span style="color:var(--jam-red)">Rage Clicks</span> ·
      <span style="color:var(--jam-yellow)">Heatmaps</span> ·
      All powered by Qualtrics DXA (placeholder — add your snippet!)
    </p>
  </footer>

  <script>
    // ── BOUNCING BALL FLOATERS ──
    function spawnBall(x, y) {
      const el = document.createElement('div');
      el.className = 'floater';
      el.textContent = '🏀';
      el.style.left = x + 'px';
      el.style.top  = y + 'px';
      document.body.appendChild(el);
      setTimeout(() => el.remove(), 4000);
    }

    document.getElementById('heroBall').addEventListener('click', function(e) {
      for (let i = 0; i < 5; i++) {
        setTimeout(() => spawnBall(
          e.clientX + (Math.random() - 0.5) * 80,
          e.clientY + window.scrollY + (Math.random() - 0.5) * 40
        ), i * 80);
      }
    });

    // ── BROKEN BUTTON (Rage Click Demo) ──
    let clickCount = 0;
    const brokenBtn = document.getElementById('brokenBtn');
    const counter   = document.getElementById('clickCounter');
    const msgs = [
      "Hmm, try again...",
      "Almost...",
      "Loading poster... just kidding 😈",
      "Still nope.",
      "Your frustration is being recorded 📊",
      "Qualtrics DXA sees you rage clicking 👀",
      "Click count: " // appended below
    ];
    brokenBtn.addEventListener('click', function() {
      clickCount++;
      brokenBtn.classList.remove('wiggle');
      void brokenBtn.offsetWidth; // reflow to restart animation
      brokenBtn.classList.add('wiggle');
      const msg = clickCount >= 6
        ? `Rage clicks detected: ${clickCount} 🔥`
        : msgs[clickCount - 1] || `Click #${clickCount}`;
      counter.textContent = msg;
    });

    // ── GUESTBOOK ──
    document.getElementById('submitEntry').addEventListener('click', function() {
      const input = document.getElementById('guestInput');
      const val = input.value.trim();
      if (!val) return;
      const entry = document.createElement('div');
      entry.className = 'entry';
      const now = new Date();
      entry.innerHTML = `<div class="entry-meta">Anonymous Fan · ${now.toLocaleDateString()}</div>${val}`;
      document.getElementById('entriesList').prepend(entry);
      input.value = '';
    });

    // ── PLAYER CARD CLICK FLOATERS ──
    document.querySelectorAll('.player-card').forEach(card => {
      card.addEventListener('click', function(e) {
        spawnBall(e.clientX, e.clientY + window.scrollY);
      });
    });
  </script>

</body>
</html>
