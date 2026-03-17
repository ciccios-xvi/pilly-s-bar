<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <title>Bar Pilly</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
    }
    header {
      background: url('https://images.unsplash.com/photo-1514933651103-005eec06c04b') center/cover;
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 50px;
      margin: 0;
    }
    nav {
      background: #222;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .section {
      padding: 30px;
      max-width: 800px;
      margin: auto;
    }
    .box {
      background: white;
      padding: 20px;
      margin-top: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    button {
      padding: 15px 25px;
      font-size: 16px;
      background-color: #ff9800;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #e68900;
    }
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>

<body>

<header>
  <h1>🍻 Bar Pilly</h1>
  <p>Il punto di riferimento della movida (forse)</p>
</header>

<nav>
  <a href="#menu">Menu</a>
  <a href="#chi">Chi siamo</a>
  <a href="#recensioni">Recensioni</a>
  <a href="#eventi">Eventi</a>
  <a href="#prenota">Prenota</a>
</nav>

<div class="section">

  <div class="box" id="menu">
    <h2>📋 Menu esclusivo</h2>
    <p>Spritz Premium all'aria – 12€</p>
    <p>Mojito senza menta né rum – 10€</p>
    <p>Caffè lento (servito dopo 45 min) – 4€</p>
    <p>Panino gourmet invisibile – 15€</p>
    <p>Acqua frizzante concettuale – 6€</p>
  </div>

  <div class="box" id="chi">
    <h2>👨‍🍳 Chi siamo</h2>
    <p>Il Bar Pilly nasce nel 1987, o forse nel 2003, nessuno lo sa davvero.</p>
    <p>La nostra missione è offrire un'esperienza unica, anche quando non c'è niente.</p>
  </div>

  <div class="box" id="recensioni">
    <h2>⭐ Recensioni</h2>
    <p>"Locale incredibile, non l'ho trovato ma bellissimo" – Luca</p>
    <p>"Ho ordinato acqua, mi hanno dato emozioni" – Sara</p>
    <p>"Ci tornerei se esistesse davvero" – Andrea</p>
  </div>

  <div class="box" id="eventi">
    <h2>🎉 Eventi</h2>
    <p>18 Marzo – Serata DJ Invisibile</p>
    <p>20 Marzo – Open Bar (chiuso)</p>
    <p>25 Marzo – Degustazione acqua calda</p>
  </div>

  <div class="box" id="prenota">
    <h2>📅 Prenota un tavolo</h2>
    <input type="text" placeholder="Il tuo nome"><br><br>
    <input type="number" placeholder="Numero persone"><br><br>
    <button onclick="prenota()">Prenota ora</button>
  </div>

</div>

<footer>
  <p>📍 Via Fantasia 123, Trapani</p>
  <p>© 2026 Bar Pilly</p>
</footer>

<script>
function prenota() {
  alert("Prenotazione confermata! Ti aspettiamo 🍻");
}

setTimeout(() => {
  alert("🎉 Sei stato selezionato per un drink GRATIS!");
}, 4000);

setTimeout(() => {
  alert("Ops... era uno scherzo 😄");
}, 8000);
</script>

</body>
</html>
