# Jogos-de-kaorr
Site com jogos online 
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>🎮 Jogos do Kaorr</title>
<style>
  body {
    margin: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
    color: #fff;
    text-align: center;
  }
  h1 {
    margin-top: 40px;
    font-size: 3em;
    letter-spacing: 2px;
    text-shadow: 2px 2px 8px #000;
  }
  .game-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 30px;
    padding: 40px;
    max-width: 1200px;
    margin: auto;
  }
  .game {
    background: rgba(255,255,255,0.05);
    border-radius: 15px;
    overflow: hidden;
    cursor: pointer;
    transition: transform 0.3s, box-shadow 0.3s;
  }
  .game:hover {
    transform: scale(1.05);
    box-shadow: 0 10px 20px rgba(0,0,0,0.5);
  }
  .game img {
    width: 100%;
    display: block;
  }
  .game-title {
    padding: 15px;
    font-size: 1.2em;
    font-weight: bold;
    background: rgba(0,0,0,0.4);
  }
</style>
</head>
<body>
<h1>🎮 Jogos do Kaorr</h1>

<div class="game-container">
  <div class="game" onclick="abrirJogo('https://www.crazygames.com/game/forward-assault')">
    <img src="https://images.crazygames.com/forward-assault/cover-1584697365380.png?auto=format,compress&q=75&cs=strip" alt="Assalto Espacial">
    <div class="game-title">Assalto Espacial</div>
  </div>
  <div class="game" onclick="abrirJogo('https://www.crazygames.com/game/slope')">
    <img src="https://images.crazygames.com/slope/cover-1584148303416.png?auto=format,compress&q=75&cs=strip" alt="Rampa Radical">
    <div class="game-title">Rampa Radical</div>
  </div>
  <div class="game" onclick="abrirJogo('https://www.crazygames.com/game/krunker')">
    <img src="https://images.crazygames.com/krunker/cover-1604472111781.png?auto=format,compress&q=75&cs=strip" alt="Krunker">
    <div class="game-title">Krunker</div>
  </div>
  <div class="game" onclick="abrirJogo('https://www.crazygames.com/game/rooftop-snipers')">
    <img src="https://images.crazygames.com/rooftop-snipers/cover-1585081274125.png?auto=format,compress&q=75&cs=strip" alt="Snipers no Telhado">
    <div class="game-title">Snipers no Telhado</div>
  </div>
</div>

<script>
function abrirJogo(url) {
  window.open(url, '_blank');
}
</script>
</body>
</html>
