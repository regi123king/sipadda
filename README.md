# sipadda
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SIPADDA - Sistem Informasi Pajak Daerah Digital & Analitik</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f9fc;
      color: #333;
    }
    header {
      background-color: #0066cc;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background-color: #005bb5;
      padding: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem;
    }
    .section-title {
      font-size: 1.8rem;
      color: #005bb5;
      margin-bottom: 1rem;
    }
    .feature-box {
      background-color: white;
      border-radius: 8px;
      padding: 1rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      margin-bottom: 1.5rem;
    }
    footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    .login-container {
      background-color: white;
      border-radius: 8px;
      max-width: 400px;
      margin: 2rem auto;
      padding: 2rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .login-container h2 {
      text-align: center;
      color: #005bb5;
    }
    .login-container input[type="text"],
    .login-container input[type="password"] {
      width: 100%;
      padding: 0.8rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .login-container button {
      width: 100%;
      padding: 0.8rem;
      background-color: #0066cc;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }
    .login-container button:hover {
      background-color: #004c99;
    }
    .dashboard {
      display: flex;
      flex-wrap: wrap;
      gap: 1.5rem;
      justify-content: center;
      padding: 2rem;
    }
    .card {
      background-color: white;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      width: 250px;
      text-align: center;
    }
    .card h3 {
      margin-bottom: 0.5rem;
      color: #0066cc;
    }
    .card p {
      font-size: 1.2rem;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>SIPADDA</h1>
    <p>Sistem Informasi Pajak Daerah Digital & Analitik</p>
  </header>
  <nav>
    <a href="#fitur">Fitur</a>
    <a href="#manfaat">Manfaat</a>
    <a href="#login">Login</a>
    <a href="#dashboard">Dashboard</a>
    <a href="#kontak">Kontak</a>
  </nav>
  <section id="fitur">
    <h2 class="section-title">Fitur Unggulan</h2>
    <div class="feature-box">
      <h3>Sistem Informasi Pajak Terintegrasi</h3>
      <p>e-SPTPD, e-Billing, Pembayaran Online, dan integrasi lintas dinas.</p>
    </div>
    <div class="feature-box">
      <h3>Dashboard Analitik</h3>
      <p>Monitoring real-time, prediksi tren, dan pelaporan otomatis.</p>
    </div>
    <div class="feature-box">
      <h3>Pemantauan Reklame Digital</h3>
      <p>Integrasi sensor, kamera, dan pelaporan masyarakat.</p>
    </div>
    <div class="feature-box">
      <h3>Platform OSS Daerah</h3>
      <p>Pendaftaran usaha online, pelacakan izin, dan sinkronisasi data usaha.</p>
    </div>
  </section>
  <section id="manfaat">
    <h2 class="section-title">Manfaat SIPADDA</h2>
    <ul>
      <li>Meningkatkan PAD dengan digitalisasi pajak daerah</li>
      <li>Mengurangi ketergantungan pada jenis pajak tertentu</li>
      <li>Transparansi dan efisiensi layanan publik</li>
      <li>Mendorong kerja sama publik-swasta</li>
    </ul>
  </section>
  <section id="login">
    <div class="login-container">
      <h2>Login Pengguna</h2>
      <form>
        <input type="text" placeholder="Nama Pengguna" required>
        <input type="password" placeholder="Kata Sandi" required>
        <button type="submit">Masuk</button>
      </form>
    </div>
  </section>
  <section id="dashboard">
    <h2 class="section-title">Dashboard Pengguna</h2>
    <div class="dashboard">
      <div class="card">
        <h3>Total Wajib Pajak</h3>
        <p>12.350</p>
      </div>
      <div class="card">
        <h3>Penerimaan Bulan Ini</h3>
        <p>Rp 1.275.000.000</p>
      </div>
      <div class="card">
        <h3>Reklame Aktif</h3>
        <p>284 Lokasi</p>
      </div>
      <div class="card">
        <h3>Izin Usaha Terbit</h3>
        <p>479</p>
      </div>
    </div>
  </section>
  <footer id="kontak">
    <p>&copy; 2025 SIPADDA - Dikembangkan untuk Pemerintah Daerah</p>
  </footer>
</body>
</html>
