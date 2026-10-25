
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#101010">
  <title>ZIUX MOD | Premium Store</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #0c0c0e;
      color: #f5f5f5;
    }

    header {
      padding: 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 1px solid #303034;
      background: #111113;
    }

    .logo {
      font-size: 22px;
      font-weight: 900;
      letter-spacing: 2px;
    }

    .logo span {
      color: #a7a7b0;
    }

    .status {
      color: #c7c7cf;
      font-size: 11px;
      border: 1px solid #48484e;
      border-radius: 20px;
      padding: 7px 10px;
    }

    .hero {
      padding: 65px 20px 45px;
      text-align: center;
      background:
        radial-gradient(ellipse at top, #34343b 0%, #151518 45%, #0c0c0e 80%);
    }

    .tag {
      display: inline-block;
      color: #dedee4;
      border: 1px solid #55555e;
      padding: 7px 13px;
      border-radius: 30px;
      font-size: 11px;
      letter-spacing: 2px;
      margin-bottom: 22px;
    }

    .hero h1 {
      font-size: clamp(36px, 10vw, 58px);
      font-weight: 900;
      letter-spacing: 3px;
    }

    .hero h1 span {
      color: #9999a4;
    }

    .hero p {
      color: #aaaab3;
      line-height: 1.7;
      margin: 18px auto 25px;
      max-width: 340px;
      font-size: 14px;
    }

    .button {
      display: inline-block;
      text-decoration: none;
      background: #ededf0;
      color: #111113;
      font-weight: bold;
      padding: 13px 22px;
      border-radius: 8px;
      font-size: 13px;
      transition: 0.2s;
    }

    .button:active {
      transform: scale(0.96);
    }

    .button.secondary {
      background: transparent;
      color: #ededf0;
      border: 1px solid #505058;
      margin-left: 5px;
    }

    .section {
      padding: 35px 18px;
      max-width: 850px;
      margin: auto;
    }

    .section-title {
      font-size: 21px;
      margin-bottom: 8px;
    }

    .section-desc {
      font-size: 13px;
      color: #909099;
      margin-bottom: 23px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 13px;
    }

    .product {
      border: 1px solid #333339;
      background: linear-gradient(145deg, #1c1c20, #111113);
      border-radius: 12px;
      padding: 17px 13px;
    }

    .product-icon {
      width: 43px;
      height: 43px;
      display: grid;
      place-items: center;
      border-radius: 10px;
      background: #303036;
      color: #f4f4f7;
      font-size: 22px;
      margin-bottom: 17px;
    }

    .product h3 {
      font-size: 15px;
      margin-bottom: 9px;
    }

    .product p {
      color: #9999a3;
      font-size: 12px;
      line-height: 1.6;
      min-height: 38px;
      margin-bottom: 15px;
    }

    .product .button {
      width: 100%;
      text-align: center;
      padding: 11px 5px;
      font-size: 12px;
    }

    .about {
      border: 1px solid #333339;
      background: #151518;
      padding: 22px;
      border-radius: 12px;
      line-height: 1.8;
      color: #b4b4bd;
      font-size: 13px;
    }

    .about strong {
      color: white;
    }

    footer {
      border-top: 1px solid #303034;
      text-align: center;
      padding: 25px 15px;
      color: #85858e;
      font-size: 12px;
      line-height: 2;
    }

    footer strong {
      color: #dedee4;
    }

    @media (max-width: 360px) {
      .products {
        grid-template-columns: 1fr;
      }

      .button.secondary {
        margin: 10px 0 0;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">ZIUX <span>MOD</span></div>
    <div class="status">PREMIUM STORE</div>
  </header>

  <section class="hero">
    <div class="tag">WELCOME TO MY WEBSITE</div>

    <h1>ZIUX <span>MOD</span></h1>

    <p>
      Tempat produk digital pilihan.
      Tampilan simpel, modern, dan nyaman
      digunakan langsung dari HP kamu.
    </p>

    <a href="#produk" class="button">LIHAT PRODUK</a>
    <a href="#kontak" class="button secondary">KONTAK</a>
  </section>

  <section class="section" id="produk">
    <h2 class="section-title">Produk Kami</h2>
    <p class="section-desc">
      Pilih produk yang ingin kamu tanyakan.
    </p>

    <div class="products">

      <div class="product">
        <div class="product-icon">✦</div>
        <h3>Produk Premium</h3>
        <p>Informasi produk dan harga bisa ditanyakan melalui WhatsApp.</p>
        <a class="button" href="#kontak">TANYA PRODUK</a>
      </div>

      <div class="product">
        <div class="product-icon">◈</div>
        <h3>Produk Digital</h3>
        <p>Lihat ketersediaan dan detail produk sebelum melakukan pemesanan.</p>
        <a class="button" href="#kontak">TANYA PRODUK</a>
      </div>

      <div class="product">
        <div class="product-icon">⬡</div>
        <h3>Layanan Custom</h3>
        <p>Ingin desain atau tampilan custom? Hubungi kami untuk berdiskusi.</p>
        <a class="button" href="#kontak">PESAN CUSTOM</a>
      </div>

      <div class="product">
        <div class="product-icon">✧</div>
        <h3>Produk Lainnya</h3>
        <p>Hubungi kami untuk mengetahui produk lainnya yang tersedia.</p>
        <a class="button" href="#kontak">INFO PRODUK</a>
      </div>

    </div>
  </section>

  <section class="section" id="kontak">
    <h2 class="section-title">Hubungi Kami</h2>
    <p class="section-desc">
      Tertarik dengan produk kami?
    </p>

    <div class="about">
      <strong>ZIUX MOD</strong><br>
      Terima kasih telah mengunjungi website kami.
      Klik tombol di bawah untuk bertanya tentang
      produk, harga, atau layanan custom.

      <br><br>

      <a
        class="button"
        href="https://wa.me/62XXXXXXXXXX"
        target="_blank"
        rel="noopener noreferrer">
        HUBUNGI VIA WHATSAPP
      </a>
    </div>
  </section>

  <footer>
    <strong>ZIUX MOD</strong><br>
    Premium Digital Store<br>
    © 2026 ZIUX MOD. All rights reserved.
  </footer>

</body>
</html>
