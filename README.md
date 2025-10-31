<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>QuickBeats</title>
  <style>
    body {
      background: linear-gradient(120deg, #1db954, #121212);
      color: white;
      font-family: sans-serif;
      text-align: center;
      padding: 20px;
    }
    h1 { margin-bottom: 10px; }
    audio {
      width: 90%;
      margin: 10px auto;
      display: block;
      border-radius: 12px;
    }
    .song {
      margin: 20px;
    }
  </style>
</head>
<body>
  <h1>🎧 QuickBeats Music</h1>
  <p>Enjoy the best tracks online!</p>

  <div class="song">
    <h3>Track 1 - Alone</h3>
    <audio controls>
      <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
    </audio>
  </div>

  <div class="song">
    <h3>Track 2 - Dreams</h3>
    <audio controls>
      <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-2.mp3" type="audio/mpeg">
    </audio>
  </div>
</body>
</html>
