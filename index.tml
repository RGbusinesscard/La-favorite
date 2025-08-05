<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>La Favorite</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: repeating-linear-gradient(
        90deg,
        #1c1c1c,
        #1c1c1c 50px,
        #111 50px,
        #111 100px
      );
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .logo-container {
      background: transparent;
      border: 10px solid transparent;
      border-image-source: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg"></svg>'); /* aucune bordure, mais structure prête */
      padding: 40px;
      border-radius: 20px;
      text-align: center;
    }

    .logo-text {
      font-family: 'Brush Script MT', cursive;
      font-size: 48px;
      color: gold;
    }

    .subtext {
      font-family: Georgia, serif;
      font-size: 16px;
      color: #ccc;
      letter-spacing: 1px;
    }

    .frame {
      border: 6px solid black;
      border-radius: 100px;
      padding: 40px 60px;
      position: relative;
      background-color: rgba(0, 0, 0, 0.7);
      box-shadow: 0 0 20px rgba(0,0,0,0.5);
    }

    .frame::before {
      content: '';
      position: absolute;
      top: -20px;
      left: -20px;
      right: -20px;
      bottom: -20px;
      background: url('https://upload.wikimedia.org/wikipedia/commons/2/26/Ornamental_flourish.svg') center center no-repeat;
      background-size: contain;
      opacity: 0.2;
      z-index: 0;
    }

    .logo-container * {
      position: relative;
      z-index: 1;
    }
  </style>
</head>
<body>
  <div class="logo-container">
    <div class="frame">
      <div class="logo-text">La Favorite</div>
      <div class="subtext">Bijouterie & Parfumerie</div>
    </div>
  </div>
</body>
</html>
