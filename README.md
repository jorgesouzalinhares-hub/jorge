<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Jogos Online Grátis</title>

<style>
body {
    margin: 0;
    font-family: Arial;
    background: #0b6623;
    color: white;
    text-align: center;
}

header {
    background: #000;
    padding: 15px;
    font-size: 22px;
}

.game {
    background: #1c1c1c;
    margin: 20px;
    padding: 20px;
    border-radius: 15px;
}

button {
    padding: 12px 25px;
    font-size: 18px;
    border: none;
    border-radius: 10px;
    background: gold;
    cursor: pointer;
}

#ad {
    background: #222;
    padding: 15px;
    margin: 20px;
    border-radius: 10px;
}
</style>
</head>

<body>

<header>🎮 Jogos Grátis Online</header>

<div id="ad">
    📢 Espaço para anúncio  
    <br><small>(Venda esse espaço)</small>
</div>

<div class="game">
    <h2>⚽ Chute ao Gol</h2>
    <p>Clique para jogar</p>
    <button onclick="jogar()">Jogar</button>
</div>

<div class="game">
    <h2>🎯 Jogo da Sorte</h2>
    <button onclick="alert('Você ganhou pontos!')">Jogar</button>
</div>

<script>
function jogar() {
    let chance = Math.random();
    if (chance > 0.5) {
        alert("GOOOL! ⚽");
    } else {
        alert("Errou 😅");
    }
}
</script>

</body>
</html>
