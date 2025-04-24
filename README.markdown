<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Little Letter</title>
  <style>
    body {
      background: linear-gradient(to bottom right, #fce4ec, #f8bbd0);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
      color: #4a4a4a;
      overflow: hidden;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
      animation: floatIn 1.5s ease-out;
    }
    .card {
      background: #ffffffcc;
      border-radius: 20px;
      padding: 2rem;
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
      width: 90%;
      max-width: 500px;
      text-align: center;
      animation: fadeIn 2s ease-in;
    }
    button {
      background-color: #f48fb1;
      color: white;
      border: none;
      padding: 0.8rem 2rem;
      border-radius: 12px;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.3s, transform 0.2s;
    }
    button:hover {
      background-color: #ec407a;
      transform: scale(1.05);
    }
    .random-message {
      margin-top: 1.5rem;
      font-style: italic;
      color: #6a1b9a;
      min-height: 60px;
      animation: fadeIn 1s ease-in-out;
    }
    @keyframes floatIn {
      0% { transform: translateY(-50px); opacity: 0; }
      100% { transform: translateY(0); opacity: 1; }
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .flowers {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      background-image: url('https://i.imgur.com/sN1zv1L.png');
      background-repeat: repeat;
      background-size: 150px;
      opacity: 0.05;
      animation: moveFlowers 60s linear infinite;
    }
    @keyframes moveFlowers {
      0% { background-position: 0 0; }
      100% { background-position: 1000px 1000px; }
    }
  </style>
</head>
<body>
  <div class="flowers"></div>
  <audio autoplay loop>
    <source src="https://dl.vgmdownloads.com/soundtracks/naruto-shippuden-original-soundtrack-1/sbfbdxnmle/2-08.%20Loneliness.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>
  <h1>رسالة صغيرة</h1>
  <div class="card">
    <button onclick="showRandomMessage()">شارك رسالة عشوائية</button>
    <div id="messageDisplay" class="random-message"></div>
  </div>  <script>
    const messages = [
      "أنت لست وحدك، حتى في اللحظات التي تبدو فارغة.",
      "Keep going, even when it feels heavy.",
      "الراحة قادمة، فقط خذ نفسًا عميقًا.",
      "You are a quiet miracle in a loud world.",
      "أنت كافٍ، تمامًا كما أنت الآن.",
      "Your softness is your power.",
      "لا بأس أن تتباطأ، المهم أن تستمر.",
      "Someone out there is glad you exist."
    ];

    function showRandomMessage() {
      const randomIndex = Math.floor(Math.random() * messages.length);
      document.getElementById('messageDisplay').innerText = messages[randomIndex];
    }
  </script></body>
</html><!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Little Letter</title>
  <style>
    body {
      background: linear-gradient(to bottom right, #fce4ec, #f8bbd0);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
      color: #4a4a4a;
      overflow: hidden;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
      animation: floatIn 1.5s ease-out;
    }
    .card {
      background: #ffffffcc;
      border-radius: 20px;
      padding: 2rem;
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
      width: 90%;
      max-width: 500px;
      text-align: center;
      animation: fadeIn 2s ease-in;
    }
    button {
      background-color: #f48fb1;
      color: white;
      border: none;
      padding: 0.8rem 2rem;
      border-radius: 12px;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.3s, transform 0.2s;
    }
    button:hover {
      background-color: #ec407a;
      transform: scale(1.05);
    }
    .random-message {
      margin-top: 1.5rem;
      font-style: italic;
      color: #6a1b9a;
      min-height: 60px;
      animation: fadeIn 1s ease-in-out;
    }
    @keyframes floatIn {
      0% { transform: translateY(-50px); opacity: 0; }
      100% { transform: translateY(0); opacity: 1; }
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .flowers {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      background-image: url('https://i.imgur.com/sN1zv1L.png');
      background-repeat: repeat;
      background-size: 150px;
      opacity: 0.05;
      animation: moveFlowers 60s linear infinite;
    }
    @keyframes moveFlowers {
      0% { background-position: 0 0; }
      100% { background-position: 1000px 1000px; }
    }
  </style>
</head>
<body>
  <div class="flowers"></div>
  <audio autoplay loop>
    <source src="https://dl.vgmdownloads.com/soundtracks/naruto-shippuden-original-soundtrack-1/sbfbdxnmle/2-08.%20Loneliness.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>
  <h1>رسالة صغيرة</h1>
  <div class="card">
    <button onclick="showRandomMessage()">شارك رسالة عشوائية</button>
    <div id="messageDisplay" class="random-message"></div>
  </div>  <script>
    const messages = [
      "أنت لست وحدك، حتى في اللحظات التي تبدو فارغة.",
      "Keep going, even when it feels heavy.",
      "الراحة قادمة، فقط خذ نفسًا عميقًا.",
      "You are a quiet miracle in a loud world.",
      "أنت كافٍ، تمامًا كما أنت الآن.",
      "Your softness is your power.",
      "لا بأس أن تتباطأ، المهم أن تستمر.",
      "Someone out there is glad you exist."
    ];

    function showRandomMessage() {
      const randomIndex = Math.floor(Math.random() * messages.length);
      document.getElementById('messageDisplay').innerText = messages[randomIndex];
    }
  </script></body>
</html>
