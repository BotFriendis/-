<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Bot Friends do Xinglau</title>
  <style>
    body {
      margin: 0;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background: linear-gradient(135deg, #ffccff, #ccffff);
      color: #333;
      text-align: center;
    }
    header {
      background-color: #ff99cc;
      padding: 20px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: #fff;
    }
    .bots-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 40px 20px;
    }
    .bot-card {
      background: #fff;
      border-radius: 15px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
      margin: 20px;
      width: 250px;
      transition: transform 0.3s;
      cursor: pointer;
    }
    .bot-card:hover {
      transform: scale(1.05);
    }
    .bot-image {
      width: 100%;
      border-top-left-radius: 15px;
      border-top-right-radius: 15px;
    }
    .bot-info {
      padding: 20px;
    }
    .bot-info h2 {
      margin: 0 0 10px;
      color: #ff6699;
    }
    .bot-info p {
      margin: 0;
    }
    footer {
      background-color: #ff99cc;
      color: #fff;
      padding: 10px;
      position: fixed;
      width: 100%;
      bottom: 0;
    }
    .video-section {
      margin: 40px 0;
    }
    .video-section iframe {
      width: 80%;
      max-width: 560px;
      height: 315px;
      border: none;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Conheça os Bot Friends do Xinglau!</h1>
  </header>

  <div class="bots-container">
    <div class="bot-card" onclick="showBotInfo('Red Bot', 'O líder corajoso da equipe, sempre pronto para enfrentar desafios.')">
      <img class="bot-image" src="https://via.placeholder.com/250x150/ff6666/ffffff?text=Red+Bot" alt="Red Bot">
      <div class="bot-info">
        <h2>Red Bot</h2>
        <p>O líder corajoso da equipe.</p>
      </div>
    </div>
    <div class="bot-card" onclick="showBotInfo('Blue Bot', 'O estrategista inteligente, conhecido por suas soluções criativas.')">
      <img class="bot-image" src="https://via.placeholder.com/250x150/6699ff/ffffff?text=Blue+Bot" alt="Blue Bot">
      <div class="bot-info">
        <h2>Blue Bot</h2>
        <p>O estrategista inteligente.</p>
      </div>
    </div>
    <div class="bot-card" onclick="showBotInfo('Purple Bot', 'O especialista em tecnologia, sempre com os gadgets mais avançados.')">
      <img class="bot-image" src="https://via.placeholder.com/250x150/9966cc/ffffff?text=Purple+Bot" alt="Purple Bot">
      <div class="bot-info">
        <h2>Purple Bot</h2>
        <p>O especialista em tecnologia.</p>
      </div>
    </div>
    <div class="bot-card" onclick="showBotInfo('Pink Bot', 'A otimista do grupo, trazendo alegria e motivação para todos.')">
      <img class="bot-image" src="https://via.placeholder.com/250x150/ff99cc/ffffff?text=Pink+Bot" alt="Pink Bot">
      <div class="bot-info">
        <h2>Pink Bot</h2>
        <p>A otimista do grupo.</p>
      </div>
    </div>
    <div class="bot-card" onclick="showBotInfo('Black Bot', 'O misterioso e poderoso membro da equipe, com habilidades únicas.')">
      <img class="bot-image" src="https://via.placeholder.com/250x150/000000/ffffff?text=Black+Bot" alt="Black Bot">
      <div class="bot-info">
        <h2>Black Bot</h2>
        <p>O misterioso e poderoso membro da equipe.</p>
      </div>
    </div>
  </div>

  <div class="video-section">
    <h2>Assista à aventura dos Bot Friends!</h2>
    <iframe src="https://www.youtube.com/embed/O__ARsDRLyU" allowfullscreen></iframe>
  </div>

  <footer>
    <p>© 2025 BauersXinglau. Todos os direitos reservados.</p>
  </footer>

  <script>
    function showBotInfo(name, description) {
      alert(name + ":\n" + description);
    }
  </script>

</body>
</html>
