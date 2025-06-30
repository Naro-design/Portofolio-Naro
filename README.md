<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Genaro Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {margin: 0; padding: 0; box-sizing: border-box;}
    body {
      font-family: 'Poppins', sans-serif;
      background: #0a0a0a;
      color: #fff;
    }
    header {
      background: #111;
      padding: 1rem;
      text-align: center;
    }
    header h1 {
      font-size: 2rem;
      color: #29abe2;
    }
    header h1 span {
      font-size: 1.5rem;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1rem;
      background: #1a1a1a;
      padding: 0.5rem 0;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: 600;
    }
    .hero {
      text-align: center;
      padding: 2rem;
    }
    .hero img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 3px solid #29abe2;
      margin-bottom: 1rem;
    }
    .hero h2 {
      font-size: 1.5rem;
      margin: 1rem 0 0.5rem;
    }
    .hero p {
      color: #ccc;
    }
    section {
      padding: 2rem;
    }
    h3 {
      color: #29abe2;
      border-bottom: 2px solid #29abe2;
      margin-bottom: 1rem;
      padding-bottom: 0.5rem;
    }
    .skills .bar {
      background: #222;
      margin: 0.5rem 0;
      border-radius: 10px;
      overflow: hidden;
    }
    .skills .bar span {
      display: block;
      padding: 0.5rem;
      color: #fff;
      font-weight: bold;
    }
    .skills .fill {
      height: 20px;
      text-align: right;
      padding-right: 0.5rem;
      line-height: 20px;
    }
    .galeri {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }
    .galeri img {
      width: 100%;
      max-width: 300px;
      border-radius: 10px;
      border: 2px solid #29abe2;
    }
    .kontak a {
      display: block;
      color: #29abe2;
      margin: 0.5rem 0;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #111;
      color: #999;
    }
  </style>
</head>
<body>
  <header>
    <h1>Genaro <span>👑</span></h1>
  </header>

  <nav>
    <a href="#tentang">Tentang</a>
    <a href="#hobi">Hobi</a>
    <a href="#galeri">Galeri</a>
    <a href="#kontak">Kontak</a>
  </nav>

  <section class="hero">
    <img src="c:\Users\ASUS\Downloads\IMG-20250314-WA0002.jpg" alt="Foto Genaro">
    <h2>Hay, Saya Genaro</h2>
    <p>Mahasiswa Teknik Informatika </p>
  </section>

  <section id="tentang">
    <h3>Tentang Saya</h3>
    <p>Perkenalkan nama lengkap saya <strong>Genaro Sarneli Tangggumaraa</strong> (2123029), saya berasal dari Kawangu, lahir pada 14 November 2005. Saya kuliah di jurusan Teknik Informatika dan saat ini sedang aktif belajar mengembangkan web.</p>
  </section>

  <section id="hobi">
    <h3>Hobi Saya</h3>
    <div class="skills">
      <div class="bar"><span>Catur</span><div class="fill" style="width: 75%; background: linear-gradient(to right, #29abe2, #007bff);">15%</div></div>
      <div class="bar"><span>Sepak Bola</span><div class="fill" style="width: 65%; background: linear-gradient(to right, #8e44ad, #9b59b6);">50%</div></div>
      <div class="bar"><span>Nonton</span><div class="fill" style="width: 50%; background: linear-gradient(to right, #e74c3c, #e67e22);">20%</div></div>
      <div class="bar"><span>Memancing</span><div class="fill" style="width: 80%; background: linear-gradient(to right, #f39c12, #f1c40f);">15%</div></div>
    </div>
  </section>

  <section id="galeri">
    <h3>Galeri Saya</h3>
    <div class="galeri">
      <img src="c:\Users\ASUS\Downloads\FreeFire_04_14_2025 19_28_21.png" alt="Galeri 1">
      <img src="c:\Users\ASUS\Downloads\IMG-20250315-WA0012 (1).jpg" alt="Galeri 2">
      <img src="c:\Users\ASUS\Downloads\IMG-20250320-WA0000.jpg" alt="Galeri 3">
      <img src="c:\Users\ASUS\Downloads\Screenshot_20250329-144559_Free Fire.jpg" alt="Galeri 4">
      <img src="c:\Users\ASUS\Downloads\IMG-20241219-WA0019.jpg" alt="Galeri 5">
      
    </div>
  </section>

  <section id="kontak" class="kontak">
    <h3>Hubungi Saya</h3>
    <p>Jika Anda membutuhkan bantuan atau ingin bekerja sama, silakan hubungi saya melalui:</p>
    <a href="telp:+6281368804850">📞 0813-6880-4850</a>
    <a href="WhatsApp:+6281368804850">📞 0813-6880-4850</a>
    <a href="email:genarotanggumara@gamil.com">📧 genarotangggumra@gmail.com</a>
    <a href="https:
