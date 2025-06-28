<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>KILLUASTORE - Layanan Top Up Game Murah</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <div class="container">
      <h1>KILLUA.ID</h1>
      <nav>
        <a href="#">Beranda</a>
        <a href="#harga">Harga</a>
        <a href="#form">Top Up Sekarang</a>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <h2>Top Up Game Favoritmu dengan Harga Termurah!</h2>
      <p>Mobile Legends, Free Fire, PUBG, Valorant, dan banyak lagi.</p>
      <a href="#form" class="btn">Mulai Top Up</a>
    </div>
  </section>

  <section id="harga" class="price-list">
    <div class="container">
      <h3>Daftar Harga</h3>
      <div class="cards">
        <div class="card">
          <h4>Mobile Legends</h4>
          <p>86 Diamonds - Rp20.000</p>
          <p>172 Diamonds - Rp38.000</p>
        </div>
        <div class="card">
          <h4>Free Fire</h4>
          <p>70 Diamonds - Rp10.000</p>
          <p>140 Diamonds - Rp18.000</p>
        </div>
        <div class="card">
          <h4>PUBG Mobile</h4>
          <p>60 UC - Rp15.000</p>
          <p>120 UC - Rp29.000</p>
        </div>
      </div>
    </div>
  </section>

  <section id="form" class="form-section">
    <div class="container">
      <h3>Formulir Top Up</h3>
      <form id="topup-form">
        <label>Game</label>
        <select id="game">
          <option>Mobile Legends</option>
          <option>Free Fire</option>
          <option>PUBG Mobile</option>
        </select>

        <label>User ID</label>
        <input type="text" id="userid" placeholder="Masukkan User ID" required>

        <label>Nominal</label>
        <select id="nominal">
          <option>86 Diamonds</option>
          <option>172 Diamonds</option>
          <option>257 Diamonds</option>
        </select>

        <label>Metode Pembayaran</label>
        <select id="metode">
          <option>DANA</option>
          <option>OVO</option>
          <option>Bank Transfer</option>
        </select>

        <button type="submit">Kirim</button>
      </form>

      <div id="result" class="result"></div>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 KILLUA.ID | Jasa Top Up Game Digital</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

