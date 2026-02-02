<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boutique de Sacs Tunisie</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #ffffff;
            color: #333;
        }

        header {
            text-align: center;
            padding: 25px 15px;
            background-color: #fcfcfc;
            border-bottom: 1px solid #eee;
        }

        header h1 {
            margin: 0;
            font-size: 24px;
        }

        header p {
            color: #777;
            font-size: 14px;
        }

        .container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 15px;
            padding: 15px;
            max-width: 1100px;
            margin: auto;
        }

        .product {
            border: 1px solid #eee;
            border-radius: 10px;
            padding: 12px;
            text-align: center;
            background-color: #fafafa;
        }

        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
        }

        .product h3 {
            margin: 12px 0 5px;
            font-size: 18px;
        }

        .price {
            font-size: 17px;
            font-weight: bold;
            color: #c97b63;
            margin: 8px 0;
        }

        .product button {
            width: 100%;
            padding: 12px;
            border: none;
            background-color: #333;
            color: white;
            cursor: pointer;
            border-radius: 6px;
            font-size: 15px;
        }

        .product button:hover {
            background-color: #555;
        }

        /* Floating social buttons */
        .social-buttons {
            position: fixed;
            bottom: 20px;
            right: 20px;
            display: flex;
            flex-direction: column;
            gap: 12px;
            z-index: 999;
        }

        .social-buttons a {
            width: 55px;
            height: 55px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-decoration: none;
            font-size: 22px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }

        .whatsapp {
            background-color: #25D366;
        }

        .instagram {
            background: radial-gradient(circle at 30% 30%, #feda75, #d62976, #962fbf, #4f5bd5);
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 20px;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>Boutique de Sacs Faits Main</h1>
    <p>Contactez-nous sur WhatsApp ou Instagram</p>
</header>

<div class="container">

    <div class="product">
        <img src="https://ibb.co/xq8VGSw0/400x300">
        <h3>Sac en cuir naturel</h3>
        <p class="price">120 TND</p>
        <button>Commander</button>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/400x300">
        <h3>Sac en tissu brodé</h3>
        <p class="price">65 TND</p>
        <button>Commander</button>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/400x300">
        <h3>Sac bohème</h3>
        <p class="price">85 TND</p>
        <button>Commander</button>
    </div>

</div>

<!-- Floating WhatsApp & Instagram buttons -->
<div class="social-buttons">
    <a class="whatsapp" href="https://wa.me/21690295149" target="_blank">💬</a>
    <a class="facebook" href="https://www.facebook.com/profile.php?id=61587474565580" target="_blank">📸</a>
</div>

</body>
</html>
