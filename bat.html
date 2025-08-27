
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>💓 Mon cœur pour toi</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      background: radial-gradient(circle, #ffafcc, #bde0fe);
      margin: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
    }

    h1 {
      color: white;
      text-shadow: 0 0 10px #f06292;
    }

    .heart {
      width: 120px;
      height: 100px;
      background-color: #ff4d6d;
      position: relative;
      transform: rotate(-45deg);
      animation: pulse 1.5s infinite;
      margin-top: 20px;
      cursor: pointer;
    }

    .heart::before,
    .heart::after {
      content: "";
      width: 120px;
      height: 100px;
      background-color: #ff4d6d;
      position: absolute;
      border-radius: 50%;
    }

    .heart::before {
      top: -60px;
      left: 0;
    }

    .heart::after {
      left: 60px;
      top: 0;
    }

    @keyframes pulse {
      0% { transform: scale(1) rotate(-45deg); }
      25% { transform: scale(1.1) rotate(-45deg); }
      50% { transform: scale(1.2) rotate(-45deg); }
      75% { transform: scale(1.1) rotate(-45deg); }
      100% { transform: scale(1) rotate(-45deg); }
    }

    .beats {
      margin-top: 20px;
      font-size: 1.5em;
      color: #fff;
      text-shadow: 0 0 6px #333;
    }

    canvas {
      margin-top: 30px;
      background: transparent;
    }
  </style>
</head>
<body>
  <h1>💓 Mon cœur bat pour toi</h1>
  <div class="heart"></div>
  <div class="beats">Chaque battement est pour toi 💘</div>

  <canvas id="ecg" width="600" height="100"></canvas>

  <script>
    const canvas = document.getElementById('ecg');
    const ctx = canvas.getContext('2d');

    let t = 0;
    function drawLine() {
      ctx.fillStyle = "rgba(255,255,255,0.05)";
      ctx.fillRect(0, 0, canvas.width, canvas.height);
      ctx.lineWidth = 2;
      ctx.strokeStyle = "#ff4d6d";
      ctx.beginPath();

      for (let x = 0; x < canvas.width; x++) {
        const y = 50 + Math.sin((x + t) * 0.05) * 10 + (x % 100 === 50 ? -35 : 0);
        ctx.lineTo(x, y);
      }

      ctx.stroke();
      t += 2;
      requestAnimationFrame(drawLine);
    }

    drawLine();
  </script>
</body>
</html>
