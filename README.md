<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Eaglercraft 1.8.8 Browser</title>
  <style>
    /* ===== GLOBAL ===== */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: "Poppins", "Segoe UI", sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #eee;
      line-height: 1.7;
      overflow-x: hidden;
    }

    h1, h2 {
      font-weight: 700;
      letter-spacing: 1px;
    }

    h2 {
      margin-bottom: 1rem;
      color: #00d4ff;
    }

    p, li {
      font-size: 1.05rem;
    }

    main {
      max-width: 900px;
      margin: auto;
      padding: 2rem;
    }

    /* ===== HEADER ===== */
    header {
      background: linear-gradient(120deg, #0072ff, #00c6ff);
      padding: 3rem 1rem;
      text-align: center;
      color: white;
      border-bottom-left-radius: 40px;
      border-bottom-right-radius: 40px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.3);
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
      animation: fadeInDown 1.2s ease;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    /* ===== SECTIONS ===== */
    section {
      background: rgba(255, 255, 255, 0.07);
      padding: 2rem;
      border-radius: 15px;
      margin: 2rem 0;
      backdrop-filter: blur(10px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.25);
      transition: transform 0.3s ease;
    }

    section:hover {
      transform: translateY(-6px);
    }

    ul {
      padding-left: 1.5rem;
    }

    code {
      background: rgba(255,255,255,0.15);
      padding: 3px 6px;
      border-radius: 5px;
      font-family: monospace;
      color: #00eaff;
    }

    /* ===== LINKS ===== */
    a {
      color: #00eaff;
      font-weight: 600;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    a:hover {
      color: #ff7eb3;
      text-decoration: underline;
    }

    /* ===== BUTTON ===== */
    .btn {
      display: inline-block;
      padding: 0.9rem 2rem;
      margin-top: 1rem;
      font-size: 1.1rem;
      font-weight: bold;
      border-radius: 50px;
      color: white;
      background: linear-gradient(45deg, #00d2ff, #3a7bd5);
      box-shadow: 0 5px 15px rgba(0,0,0,0.3);
      text-transform: uppercase;
      letter-spacing: 1px;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .btn:hover {
      transform: scale(1.07);
      box-shadow: 0 8px 20px rgba(0,0,0,0.45);
      background: linear-gradient(45deg, #3a7bd5, #00d2ff);
    }

    /* ===== FOOTER ===== */
    footer {
      text-align: center;
      padding: 1.5rem;
      background: rgba(0,0,0,0.4);
      border-top: 1px solid rgba(255,255,255,0.1);
      font-size: 0.9rem;
      color: #ccc;
      margin-top: 3rem;
    }

    /* ===== ANIMATIONS ===== */
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-40px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <header>
    <h1>Eaglercraft 1.8.8 Browser</h1>
    <p><b>Play Minecraft 1.8.8 in your browser – multiplayer worlds, skins, settings & more!</b></p>
  </header>

  <main>
    <section>
      <h2>About</h2>
      <p>
        Explore villages, mineshafts, dungeons, caves, ravines, and unique biomes. 
        The Nether and End are also available. Commands work the same as Minecraft.  
        <b>Note:</b> Singleplayer is only supported in the 1.5.2 version.
      </p>
    </section>

    <section>
      <h2>How to Launch</h2>
      <ul>
        <li>Download the ZIP file.</li>
        <li>Extract it in your files.</li>
        <li>Find <code>eaglercraft.1.8.8.html</code>.</li>
        <li>Open it in your browser and let it load.</li>
      </ul>
      <a href="#" class="btn">Play Now</a>
    </section>

    <section>
      <h2>Servers</h2>
      <p>
        Visit <a href="https://web.archive.org/web/20230205110931/https://docs.google.com/document/d/1PhUJSb0ojMyhv1Fs8bmVqwANBkySOgdyfRinJto3xnE/edit" target="_blank">this server list</a> 
        (archived). <b>I do not own or edit this document.</b>
      </p>
    </section>

    <section>
      <h2>Important Notes</h2>
      <p>
        When creating a new world, you may see a black screen or spawn underground. 
        <b>Just wait 1–5 minutes</b> — it will fix itself. The game may lag at first but 
        usually smooths out after 5–10 minutes.  
        Remember: this is an older version of Minecraft, so not all new features are available.
      </p>
    </section>
  </main>

  <footer>
    <p><b>Disclaimer:</b> I do not own Eaglercraft and am not associated with it. 
    This is just a fullscreen browser port for convenience.</p>
  </footer>

</body>
</html>
