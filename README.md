<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TRENCH WARFARE</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      font-family: 'Impact', 'Arial Black', sans-serif;
    }

    body {
      background-color: #000000; /* Solid black background */
      color: #c2b280;
    }

    header {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 2rem 1rem;
      background-color: rgba(43, 43, 43, 0.85);
      border-bottom: 2px solid #444;
      position: relative;
      z-index: 2;
    }

    .header-title {
      font-size: 5rem;  /* Bigger font size */
      font-weight: bold;
      color: #006400;  /* Dark green color */
      letter-spacing: 2px;
      text-align: center;
      text-shadow: 0 0 20px #006400, 0 0 30px #006400, 0 0 40px #006400;  /* Dark green glowing effect */
      animation: flicker 1s infinite, glow 1s ease-in-out infinite alternate;  /* Flashing and glowing effect */
    }

    @keyframes flicker {
      0%, 19%, 21%, 23%, 25%, 54%, 56%, 100% {
        opacity: 1;
      }
      20%, 24%, 55% {
        opacity: 0.5;
      }
    }

    @keyframes glow {
      0% {
        text-shadow: 0 0 20px #006400, 0 0 30px #006400, 0 0 40px #006400;
      }
      50% {
        text-shadow: 0 0 10px #006400, 0 0 15px #006400, 0 0 25px #006400;
      }
      100% {
        text-shadow: 0 0 20px #006400, 0 0 30px #006400, 0 0 40px #006400;
      }
    }

    .image-placeholder {
      width: 90%;
      max-width: 600px;
      margin: 2rem auto;
      display: flex;
      align-items: center;
      justify-content: center;
      z-index: 2;
      position: relative;
    }

    .image-placeholder img {
      width: 100%;
      height: auto;
      border: 2px solid #444;
    }

    .intro {
      max-width: 800px;
      margin: 2rem auto;
      font-size: 1.1rem;
      line-height: 1.6;
      color: #dfd9c2;
      padding: 0 1rem;
      text-align: center;
      position: relative;
      z-index: 2;
    }

    .roadmap {
      max-width: 800px;
      margin: 2rem auto;
      text-align: left;
      font-size: 1rem;
      padding: 2rem;
      background-color: rgba(34, 34, 34, 0.85);
      border: 1px solid #3a3a3a;
      border-radius: 10px;
      position: relative;
      z-index: 2;
    }

    .roadmap h2 {
      text-align: center;
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #dfd9c2;
      text-transform: uppercase;
    }

    .roadmap ul {
      list-style-type: '• ';
      padding-left: 1.5rem;
    }

    .roadmap li {
      margin-bottom: 0.8rem;
    }

    .buttons {
      display: flex;
      justify-content: center;
      gap: 1rem;
      margin: 3rem 0;
      position: relative;
      z-index: 2;
    }

    .buttons button {
      background-color: transparent;
      border: 2px solid #c2b280;
      color: #c2b280;
      font-weight: bold;
      padding: 0.75rem 1.5rem;
      font-size: 1rem;
      cursor: pointer;
      transition: 0.2s;
      letter-spacing: 1px;
    }

    .buttons button:hover {
      background-color: #c2b280;
      color: #0f0700;
    }
  </style>
</head>
<body>

  <header>
    <div class="header-title">TRENCH WARFARE</div>
  </header>

  <div class="image-placeholder">
    <img src="trench.jpg" alt="Trench Scene" />
  </div>

  <div class="intro">
    <p>
      Welcome to the call of duty — TRENCH WARFARE. No man or woman is left behind enemy lines. 
      We feel at home in the trenches, in the dark and cold. We weren’t raised in the trenches — we were born in it.
    </p>
  </div>

  <div class="roadmap">
    <h2>MISSION BRIEFING</h2>
    <ul>
      <li>Launch meme coin stealth style, no presale, no mercy. 🔫</li>
      <li>Secure liquidity on a DEX, make it untouchable. 🔫</li>
      <li>Ignite the trenches with meme warfare across socials. 🔫</li>
      <li>Drop exclusive airdrops for the OG soldiers. 🔫</li>
      <li>Unleash trench NFTs and battle-ready merch. 🔫</li>
      <li>Begin phase 2 — partnerships, raids, and domination. 🔫</li>
    </ul>
  </div>

  <div class="buttons">
    <button>PUMP FUN</button>
    <button>X</button>
    <button>DEX</button>
  </div>

</body>
</html>
