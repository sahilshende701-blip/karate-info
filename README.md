# karate-info

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KARATE</title>
  <style>
    /* --------- Global Styles --------- */
    body {
      font-family: Arial, sans-serif;
      background-color: #f6f8f5;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      color: #222;
    }
    header {
      background: #b10d0d;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.2em;
      letter-spacing: 1px;
    }
    nav {
      background: #222;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
      color: #ffcc00;
    }

    /* --------- Sections --------- */
    section {
      padding: 40px 15%;
      border-bottom: 1px solid #ddd;
    }
    section h2 {
      color: #b10d0d;
      text-align: center;
      margin-bottom: 20px;
    }
    section h3 {
      color: #444;
      margin-top: 20px;
    }

    /* --------- Images --------- */
    img {
      display: block;
      margin: 20px auto;
      max-width: 90%;
      height: auto;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }

    /* --------- Footer --------- */
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 20px;
    }
    footer a {
      color: #ffcc00;
      text-decoration: none;
    }
    footer a:hover {
      text-decoration: underline;
    }

    /* --------- Marquee Replacement --------- */
    .marquee {
      overflow: hidden;
      white-space: nowrap;
      box-sizing: border-box;
      animation: marquee 12s linear infinite;
      background: #fff3f3;
      padding: 10px;
      color: #b10d0d;
      font-size: 1.5em;
      font-weight: bold;
      text-align: center;
    }
    @keyframes marquee {
      0%   { transform: translateX(100%); }
      100% { transform: translateX(-100%); }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Know About Karate</h1>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#history">History</a>
    <a href="#importance">Importance</a>
    <a href="#types">Types</a>
    <a href="#use">Today’s Use</a>
    <a href="#weapons">Weapons</a>
    <a href="registration.html" target="_blank">Register</a>
  </nav>

  <!-- Marquee -->
  <div class="marquee">
    <abbr title="Introduction To Karate">Introduction To Karate</abbr>
  </div>

  <!-- History -->
  <section id="history">
    <h2>History of Karate</h2>
    <p>Karate (空手)... is a martial art developed in the Ryukyu Kingdom... </p>
    <p>It developed from the indigenous Ryukyuan martial arts (called te (手), "hand"; tī in Okinawan) under the influence of Chinese martial arts...</p>
    <img src="Karate.jpg" alt="Karate practice">
  </section>

  <!-- Importance -->
  <section id="importance">
    <h2>Importance of Karate</h2>
    <h3>1. Teaches Self-Defense</h3>
    <p>Karate builds reflexes... awareness, confidence, and physical fitness.</p>

    <h3>2. Builds Confidence</h3>
    <p>Instructors create an environment... instilling belief in one’s own ability.</p>

    <h3>3. Hones Leadership Skills</h3>
    <p>Higher belts mentor lower-ranked students... developing leadership and responsibility.</p>

    <h3>4. Develops Character</h3>
    <p>Students set goals, persevere, and build resilience in both dojo and life.</p>

    <h3>5. Encourages Self-Discipline</h3>
    <p>Progress comes only through repeated, disciplined practice.</p>

    <h3>6. Promotes Healthy Body and Weight</h3>
    <p>Regular training supports fitness and a strong lifestyle.</p>

    <h3>7. Offers Multiple Choices</h3>
    <p>Karate includes different styles such as Tae Kwon Do, Jiu Jitsu, Kumdo, etc.</p>
  </section>

  <!-- Types -->
  <section id="types">
    <h2>Types of Karate</h2>
    <ol>
      <li><b>Shotokan-Ryu</b> – Strong, linear techniques (26 kata).</li>
      <li><b>Shito-Ryu</b> – Kata-heavy style (94 kata).</li>
      <li><b>Goju-Ryu</b> – Mix of hard & soft, circular movements.</li>
      <li><b>Wado-Ryu</b> – Emphasis on harmony & evasion.</li>
      <li><b>Kyokushin-Ryu</b> – Full-contact, knockdown karate.</li>
      <li><b>Isshin-Ryu</b> – Mix of Goju-Ryu, Shorin-Ryu, Kubodo.</li>
      <li><b>Uechi-Ryu</b> – Blend of Kung-Fu & Okinawan arts.</li>
      <li><b>Shorin-Ryu</b> – Fast, hard techniques (21 kata).</li>
      <li><b>Shindo Jinen-Ryu</b> – Mix of Okinawan & Japanese styles.</li>
      <li><b>Shukokai Ryu</b> – Mix of Shito-Ryu & Goju-Ryu (44 kata).</li>
      <li><b>Gosoku Ryu</b> – Combines Shotokan & Goju-Ryu.</li>
      <li><b>Shuri-Ryu</b> – Blend of Okinawan & Chinese martial arts.</li>
      <li><b>Chito-Ryu</b> – Focus on soft techniques (15 kata).</li>
    </ol>
  </section>

  <!-- Use in Today's World -->
  <section id="use">
    <h2>Use of Karate in Today’s World</h2>
    <h3>Inclusivity</h3>
    <p>Karate welcomes all ages, abilities, and backgrounds...</p>

    <h3>Adaptability & Resilience</h3>
    <p>Karate training helps practitioners adapt to challenges and opponents...</p>

    <h3>Character Development</h3>
    <p>Karate instills discipline, respect, humility, and self-improvement...</p>
  </section>

  <!-- Weapons -->
  <section id="weapons">
    <h2>Weapons Used in Karate</h2>

    <h3>1. Nunchaku</h3>
    <img src="Nunchaku.JPG" alt="Nunchaku">
    <p>Used in Kung Fu, Kobudo, and Karate... improves quick movements and posture.</p>

    <h3>2. Sword</h3>
    <img src="sword.jpg" alt="Sword">
    <p>Used for cutting, slashing, and stabbing... dates back to Ancient Egypt.</p>

    <h3>3. Sai</h3>
    <img src="SAI.jpg" alt="Sai" height="10">
    <p>Used for stabbing, striking, and disarming... popularized through Okinawan Kobudo.</p>

    <h3>4. Stick (Bō, Jō, Arnis)</h3>
    <img src="stick.jpg" alt="Stick">
    <p>Stick-fighting is part of various martial arts using long wooden weapons.</p>
  </section>

  <!-- Footer -->
  <footer>
    <p><a href="registration.html" target="_blank">Register Now</a> to Join Karate</p>
    <p><a href="https://www.gokaidosports.in/Index.aspx" target="_blank">Purchase Martial Arts Uniforms & Equipment</a></p>
    <h3>THANK YOU</h3>
  </footer>

</body>
</html>
