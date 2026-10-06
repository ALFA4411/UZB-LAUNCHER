<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>UZB Launcher</title>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
}

body {
  background: #0b0f14;
  color: white;
  min-height: 100vh;
}

header {
  padding: 25px 20px;
  background: #121821;
  text-align: center;
}

header h1 {
  font-size: 28px;
}

header p {
  color: #8d99a8;
  margin-top: 8px;
}

.play {
  display: block;
  width: calc(100% - 40px);
  margin: 25px auto;
  padding: 18px;
  border: 0;
  border-radius: 15px;
  background: #39b54a;
  color: white;
  font-size: 20px;
  font-weight: bold;
}

.container {
  padding: 0 20px 30px;
}

.card {
  background: #151c26;
  border-radius: 15px;
  padding: 20px;
  margin-bottom: 15px;
}

.card h2 {
  font-size: 18px;
  margin-bottom: 8px;
}

.card p {
  color: #9ba5b2;
}

.grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
}

.menu {
  background: #151c26;
  border: 0;
  border-radius: 15px;
  color: white;
  padding: 20px 10px;
  font-size: 16px;
}

.menu span {
  display: block;
  font-size: 30px;
  margin-bottom: 8px;
}

button {
  cursor: pointer;
}

button:active {
  transform: scale(0.97);
}

footer {
  text-align: center;
  color: #687381;
  padding: 20px;
}
</style>
</head>

<body>

<header>
  <h1>🇺🇿 UZB LAUNCHER</h1>
  <p>Minecraft Java Launcher</p>
</header>

<button class="play" onclick="startGame()">
  ▶ O‘YINNI BOSHLASH
</button>

<div class="container">

  <div class="card">
    <h2>🎮 Tanlangan versiya</h2>
    <p id="version">Minecraft 1.20.1</p>
  </div>

  <div class="grid">

    <button class="menu" onclick="versions()">
      <span>📦</span>
      Versiyalar
    </button>

    <button class="menu" onclick="mods()">
      <span>🧩</span>
      Modlar
    </button>

    <button class="menu" onclick="account()">
      <span>👤</span>
      Akkaunt
    </button>

    <button class="menu" onclick="settings()">
      <span>⚙️</span>
      Sozlamalar
    </button>

  </div>

</div>

<footer>
  UZB Launcher © 2026
</footer>

<script>

function startGame() {
  alert("Minecraft ishga tushirish funksiyasi keyingi bosqichda qo‘shiladi.");
}

function versions() {
  alert(
    "Minecraft versiyalari:\n\n" +
    "1.12.2\n" +
    "1.16.5\n" +
    "1.18.2\n" +
    "1.19.4\n" +
    "1.20.1\n" +
    "1.21.x"
  );
}

function mods() {
  alert("🧩 Modlar bo‘limi keyingi bosqichda qo‘shiladi.");
}

function account() {
  alert("👤 Akkaunt bo‘limi keyingi bosqichda qo‘shiladi.");
}

function settings() {
  alert("⚙️ Sozlamalar bo‘limi keyingi bosqichda qo‘shiladi.");
}

</script>

</body>
</html>
