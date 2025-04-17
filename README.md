# weeelpn_portal
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Портал weeelpn</title>
  <style>
    body {
      margin: 0;
      background: black;
      color: white;
      font-family: 'Courier New', monospace;
      overflow: hidden;
    }
    .logo {
      position: absolute;
      top: 20px;
      left: 20px;
      font-size: 24px;
      opacity: 0.1;
      transform: rotate(-15deg);
    }
    iframe {
      width: 100vw;
      height: 100vh;
      filter: grayscale(100%) brightness(0.8) contrast(1.2);
    }
    audio {
      display: none;
    }
  </style>
</head>
<body>
  <div class="logo">weeelpn</div>
  <iframe src="https://www.google.com/maps" frameborder="0"></iframe>
  <audio autoplay loop>
    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
  </audio>
</body>
</html>
