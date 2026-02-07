<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Manu 💖 Kinna</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(180deg, #0f0c29, #302b63, #24243e);
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
    }

    .card {
      width: 100%;
      max-width: 420px;
      height: 100%;
      padding: 25px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      text-align: center;
    }

    .heart {
      font-size: 48px;
      animation: pulse 1.2s infinite;
      margin-bottom: 10px;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.3); }
      100% { transform: scale(1); }
    }

    h1 {
      font-size: 26px;
      color: #ff7eb3;
      margin-bottom: 10px;
    }

    p {
      font-size: 16px;
      line-height: 1.7;
      margin: 12px 0;
    }

    .funny {
      background: rgba(255, 126, 179, 0.15);
      border: 1px solid rgba(255, 126, 179, 0.3);
      padding: 14px;
      border-radius: 18px;
      font-style: italic;
    }

    .proposal {
      background: linear-gradient(135deg, #ff416c, #ff4b2b);
      padding: 18px;
      border-radius: 25px;
      font-size: 17px;
      font-weight: bold;
      box-shadow: 0 0 25px rgba(255,75,107,0.6);
      margin-top: 10px;
    }

    button {
      background: transparent;
      border: 2px solid #ff7eb3;
      color: #ff7eb3;
      padding: 14px;
      border-radius: 30px;
      font-size: 16px;
      cursor: pointer;
      margin-top: 15px;
    }

    button:hover {
      background: #ff7eb3;
      color: #000;
    }

    .footer {
      margin-top: 15px;
      font-weight: bold;
      color: #ffb3d9;
    }

    audio {
      display: none;
    }
  </style>
</head>
<body>

  <!-- Romantic Background Music -->
  <audio id="bgMusic" loop>
    <!-- Replace with your favorite Telugu/romantic mp3 if you want -->
    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-2.mp3" type="audio/mpeg">
  </audio>

  <div class="card">

    <div>
      <div class="heart">💖</div>
      <h1>Hey Manu 🌙</h1>

      <p>
        Ee night lo ee page open chesav ante…  
        naa thoughts lo already place fix ayyav 😌
      </p>

      <div class="funny">
        Nee smile chusthe  
        naa overthinking kuda “bye ra” ani vellipothadi 😂  
        <br><br>
        Nuvvu pakkana unte  
        naa life dark mode lo kuda full brightness 💡❤️
      </div>

      <p>
        You are my calm in chaos,  
        naa midnight thought 💭,  
        naa sleep miss ayye sweet reason 😜
      </p>

      <p>
        Simple ga Telugu lo cheppali ante:<br>
        <b>“Nuvvu lekunda naa heart offline.”</b>
      </p>

      <div class="proposal">
        Manu 💕  
        Ee chandamama sakshi ga 🌙  
        <br><br>
        Will you be my Valentine?  
        <br>
        Not just today…  
        But every version of tomorrow 💍
      </div>
    </div>

    <div>
      <button onclick="playMusic()">🌙 Play Night Love Mode</button>

      <div class="footer">
        With all my heart 💖<br>
        — KINNA
      </div>
    </div>

  </div>

  <script>
    function playMusic() {
      document.getElementById("bgMusic").play();
    }
  </script>

</body>
</html>
