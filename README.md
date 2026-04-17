<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Easy Yoga</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        /* HERO SECTION */
        .hero {
            height: 100vh;
            background: url("poza1.jpg") center/cover no-repeat;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            position: relative;
        }

        .hero::after {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.4);
        }

        .hero-content {
            position: relative;
            z-index: 1;
        }

        .hero h1 {
            font-size: 60px;
            margin: 0;
        }

        .hero p {
            font-size: 20px;
            margin: 15px 0;
        }

        .hero button {
            padding: 12px 25px;
            border: none;
            border-radius: 10px;
            background: #25D366;
            color: white;
            font-size: 16px;
            cursor: pointer;
        }

        /* CONTENT */
        .container {
            max-width: 1000px;
            margin: auto;
            padding: 20px;
        }

        .card {
            background: white;
            margin: 25px 0;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
        }

        .card img {
            width: 100%;
        }

        .card-content {
            padding: 20px;
        }

        .social {
            text-align: center;
            margin: 40px 0;
        }

        .social a {
            display: inline-block;
            margin: 10px;
            padding: 12px 20px;
            border-radius: 10px;
            text-decoration: none;
            color: white;
            font-weight: bold;
        }

        .whatsapp { background: #25D366; }
        .tiktok { background: black; }
        .instagram { background: #E1306C; }

        footer {
            text-align: center;
            padding: 20px;
            background: #2193b0;
            color: white;
        }
    </style>
</head>
<body>

<!-- HERO -->
<div class="hero">
    <div class="hero-content">
        <h1>EASY YOGA 🧘</h1>
        <p>Liniște • Natură • Energie</p>
        <button onclick="window.open('https://wa.me/37369404887')">
            Scrie pe WhatsApp
        </button>
    </div>
</div>

<!-- CONTENT -->
<div class="container">

    <div class="card">
        <img src="poza2.jpg">
        <div class="card-content">
            <h2>Echilibru</h2>
            <p>Respirația aduce calm și energie.</p>
        </div>
    </div>

    <div class="card">
        <img src="poza3.jpg">
        <div class="card-content">
            <h2>Armonie</h2>
            <p>Trăiește prezentul și bucură-te.</p>
        </div>
    </div>

    <div class="social">
        <h2>Contact</h2>

        <a class="whatsapp" href="https://wa.me/37369404887" target="_blank">
            WhatsApp
        </a>

        <a class="tiktok" href="https://www.tiktok.com/@easy_yoga33" target="_blank">
            TikTok
        </a>

        <a class="instagram" href="https://www.instagram.com/easy_yoga33" target="_blank">
            Instagram
        </a>
    </div>

</div>

<footer>
    <p>© 2026 Easy Yoga</p>
</footer>

</body>
</html>
