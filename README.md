<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Bot Friends</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&family=Pacifico&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #ffffff;
      color: #333;
      text-align: center;
    }
    header {
      background-color: #222;
      padding: 20px;
      color: white;
    }
    header h1 {
      margin: 0;
      font-size: 3em;
      font-family: 'Pacifico', cursive;
      font-weight: 400;
      letter-spacing: 2px;
    }
    .bots-container {
      display: grid;
      grid-template-columns: repeat(3, 200px);
      grid-gap: 20px;
      justify-content: center;
      padding: 30px 10px;
    }
    .bot-card {
      background: #f0f0f0;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      cursor: pointer;
      transition: 0.3s;
      width: 200px;
      user-select: none;
    }
    .bot-card:hover {
      transform: scale(1.05);
    }
    .bot-image {
      width: 100%;
      height: 100px;
      object-fit: cover;
      border-radius: 10px 10px 0 0;
      pointer-events: none;
    }
    .bot-info {
      padding: 15px;
    }
    .bot-info h2, .bot-info p {
      font-family: 'Pacifico', cursive;
    }
    .bot-info h2 {
      margin: 10px 0 5px;
      font-size: 1.8em;
      font-weight: 400;
    }
    .bot-info p {
      margin: 0;
      font-size: 1.1em;
      color: #555;
    }
    .bot-card:nth-child(4),
    .bot-card:nth-child(5) {
      justify-self: center;
    }
    footer {
      background-color: #222;
      color: white;
      padding: 10px;
      font-size: 0.9em;
      margin-top: 30px;
    }
    @media (max-width: 660px) {
      .bots-container {
        grid-template-columns: repeat(2, 200px);
      }
      .bot-card:nth-child(4),
      .bot-card:nth-child(5) {
        justify-self: start;
      }
    }
    @media (max-width: 440px) {
      .bots-container {
        grid-template-columns: 1fr;
      }
      .bot-card {
        width: 90%;
        margin: 0 auto;
      }
    }
    .video-container {
      margin: 30px auto;
      width: 80%;
      max-width: 800px;
    }
    iframe {
      width: 100%;
      height: 450px;
      border: none;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Bot Friends</h1>
  </header>

  <div class="bots-container">
    <div class="bot-card" onclick="alert('Corajoso e destemido. Avaliação: ⭐⭐⭐⭐')">
      <img class="bot-image" src="https://dummyimage.com/200x150/ffffff/000000&text=Red+Bot" alt="Red Bot">
      <div class="bot-info">
        <h2>Red Bot</h2>
        <p>Corajoso e destemido.</p>
      </div>
    </div>
    <div class="bot-card" onclick="alert('O mais esperto do time. Avaliação: ⭐⭐⭐⭐⭐')">
      <img class="bot-image" src="https://dummyimage.com/200x150/ffffff/000000&text=Blue+Bot" alt="Blue Bot">
      <div class="bot-info">
        <h2>Blue Bot</h2>
        <p>O mais esperto do time.</p>
      </div>
    </div>
    <div class="bot-card" onclick="alert('Especialista em tecnologia. Avaliação: ⭐⭐⭐⭐')">
      <img class="bot-image" src="https://dummyimage.com/200x150/ffffff/000000&text=Purple+Bot" alt="Purple Bot">
      <div class="bot-info">
        <h2>Purple Bot</h2>
        <p>Especialista em tecnologia.</p>
      </div>
    </div>
    <div class="bot-card" onclick="alert('Sempre alegre e animada. Avaliação: ⭐⭐⭐⭐')">
      <img class="bot-image" src="https://dummyimage.com/200x150/ffffff/000000&text=Pink+Bot" alt="Pink Bot">
      <div class="bot-info">
        <h2>Pink Bot</h2>
        <p>Sempre alegre e animada.</p>
      </div>
    </div>
    <div class="bot-card" onclick="alert('O misterioso do grupo e o mais forte. Avaliação: ⭐⭐⭐⭐⭐⭐⭐⭐⭐⭐')">
      <img class="bot-image" src="https://dummyimage.com/200x150/ffffff/000000&text=Black+Bot" alt="Black Bot">
      <div class="bot-info">
        <h2>Black Bot</h2>
        <p>O misterioso do grupo e o mais forte.</p>
      </div>
    </div>
  </div>

  <div class="video-container">
    <iframe src="https://www.youtube.com/embed/O__ARsDRLyU" title="Bot Friends - Todos os Bots" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>

  <footer>
    © 2025 Xinglau Bot Friends.
  </footer>

</body>
</html>
