<html lang="id">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>ADMIN APLIKASI PREMIUM </title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;800&display=swap');
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:'Poppins', sans-serif;
    }
    body{
      background:#0a0a0a;
      color:#fff;
      overflow-x:hidden;
    }
    header{
      text-align:center;
      padding:50px 20px;
      background:linear-gradient(135deg,#0ef,#7700ff);
      -webkit-background-clip:text;
      -webkit-text-fill-color:transparent;
      animation: glow 4s infinite alternate;
      font-size:2.2rem;
      font-weight:800;
    }
    @keyframes glow {
      from {text-shadow:0 0 10px #0ef,0 0 20px #0ef;}
      to {text-shadow:0 0 20px #7700ff,0 0 40px #7700ff;}
    }
    section{
      max-width:900px;
      margin:40px auto;
      padding:20px;
      display:grid;
      gap:30px;
    }
    .card{
      background:#111;
      border-radius:20px;
      padding:30px;
      box-shadow:0 0 20px rgba(0,238,255,.2);
      transition:transform .4s, box-shadow .4s;
    }
    .card:hover{
      transform:translateY(-10px);
      box-shadow:0 0 30px rgba(119,0,255,.5);
    }
    .card h2{
      font-size:1.6rem;
      margin-bottom:15px;
      color:#0ef;
    }
    .card p{
      margin-bottom:15px;
      line-height:1.6;
    }
    a.button{
      display:inline-block;
      padding:12px 24px;
      border-radius:30px;
      text-decoration:none;
      background:linear-gradient(45deg,#0ef,#7700ff);
      color:#fff;
      font-weight:600;
      transition:background .3s, transform .3s;
    }
    a.button:hover{
      background:linear-gradient(45deg,#7700ff,#0ef);
      transform:scale(1.05);
    }
    footer{
      text-align:center;
      padding:30px;
      color:#888;
    }
    .fade-in{
      opacity:0;
      transform:translateY(20px);
      animation:fadeInUp 1s forwards;
    }
    @keyframes fadeInUp{
      to{
        opacity:1;
        transform:translateY(0);
      }
    }
  </style>
</head>
<body>
  <header>
    PROFIL ADMIN GANTENG
  </header>

  <section>
    <div class="card fade-in" style="animation-delay:0.2s">
      <h2>🎁 Donasi / Dukungan</h2>
      <p>Dukung kami melalui Sociabuzz saat live game donasi akan di tampilkan.</p>
      <a href="https://sociabuzz.com/haqibaikhati/tribe" target="_blank" class="button">Buka Sociabuzz</a>
    </div>

    <div class="card fade-in" style="animation-delay:0.4s">
      <h2>📱 Grup Jualan App Premium</h2>
      <p>Gabung ke grup WhatsApp saya untuk order aplikasi premium berbagai jenis harga nya sangat murah.</p>
      <a href="https://chat.whatsapp.com/Iu4LUcDElo06SGNKnN9Irs?mode=ems_copy_t" target="_blank" class="button">Join Grup</a>
    </div>

    <div class="card fade-in" style="animation-delay:0.6s">
      <h2>💬 Kontak Admin</h2>
      <p>Butuh bantuan atau ingin order langsung? Hubungi admin via WhatsApp.</p>
      <a href="https://wa.me/6285857898319" target="_blank" class="button">Chat Admin</a>
    </div>
  </section>

  <footer>
    © 2025 Jualan App Premium. All Rights Reserved.
  </footer>
</body>
</html>
