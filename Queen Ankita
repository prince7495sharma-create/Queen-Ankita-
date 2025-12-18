<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>New Year Gift</title>

  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #1c1c1c, #3b2f1c);
      font-family: Arial, sans-serif;
      overflow: hidden;
    }

    .gift-box {
      width: 220px;
      height: 220px;
      background: #d4af37;
      border-radius: 20px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.4);
      display: flex;
      justify-content: center;
      align-items: center;
      cursor: pointer;
      animation: pulse 1.8s infinite;
      transition: transform 0.3s ease;
    }

    .gift-box:hover {
      transform: scale(1.08);
    }

    .gift-box span {
      font-size: 20px;
      font-weight: bold;
      color: #1c1c1c;
      text-align: center;
    }

    .card {
      display: none;
      background: #fff8e1;
      padding: 25px;
      border-radius: 20px;
      text-align: center;
      max-width: 320px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.4);
      animation: openCard 0.8s ease;
    }

    .card h2 {
      margin: 0 0 15px;
      color: #b8860b;
    }

    .card p {
      color: #333;
      line-height: 1.6;
      font-size: 15px;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }

    @keyframes openCard {
      from { transform: scale(0.7); opacity: 0; }
      to { transform: scale(1); opacity: 1; }
    }
  </style>
</head>

<body>

  <div class="gift-box" onclick="openGift()" id="gift">
    <span>🎁 Tap to Open 🎁</span>
  </div>

  <div class="card" id="card">
    <h2>👑 Queen Ankita 👑</h2>
    <p>
      Happy New Year 2026 sabse pehle aapko aur aapke pure pariwar 😊 ko  
      <br><br>
      Naye saal ki hardik shubhkamnaye ✨  
      <br><br>
      💖 Happy New Year 💖
    </p>
  </div>

  <script>
    function openGift() {
      document.getElementById("gift").style.display = "none";
      document.getElementById("card").style.display = "block";
    }
  </script>

</body>
</html>
