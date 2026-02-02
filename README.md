<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma Boutique de Sacs - Nature</title>
    <style>
        /* Arrière-plan Nature */
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            padding: 0;
            background: url('https://images.unsplash.com/photo-1441974231531-c6227db76b6e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80') no-repeat center center fixed;
            background-size: cover;
        }

        /* Effet de superposition sombre pour la lisibilité */
        .overlay {
            background: rgba(0, 0, 0, 0.4);
            min-height: 100vh;
            padding-bottom: 50px;
        }

        header {
            color: white;
            padding: 3rem;
            text-align: center;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            padding: 0 20px;
        }

        /* Cartes avec effet de transparence (Glassmorphism) */
        .sac-card {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(5px);
            border-radius: 15px;
            overflow: hidden;
            transition: transform 0.3s;
            text-align: center;
            border: 1px solid rgba(255, 255, 255, 0.3);
        }

        .sac-card:hover {
            transform: translateY(-10px);
        }

        .sac-card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .info {
            padding: 20px;
        }

        .info h3 {
            margin: 0 0 10px 0;
            color: #2d3436;
        }

        .prix {
            font-size: 1.4rem;
            font-weight: bold;
            color: #27ae60; /* Vert nature */
            margin-bottom: 20px;
        }

        .btn-acheter {
            display: block;
            background-color: #2ecc71;
            color: white;
            padding: 12px;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            transition: background 0.3s;
        }

        .btn-acheter:hover {
            background-color: #27ae60;
        }
    </style>
</head>
<body>

<div class="overlay">
    <header>
        <h1>🌿 Ma Collection Nature</h1>
        <p>L'élégance au naturel, livrée partout en Tunisie</p>
    </header>

    <div class="container">
        
        <div class="sac-card">
            <img src="https://images.unsplash.com/photo-1584917865442-de89df76afd3?auto=format&fit=crop&w=500&q=80" alt="Sac à main">
            <div class="info">
                <h3>Sac à Main Cuir</h3>
                <p class="prix">145.000 TND</p>
                <a href="#" class="btn-acheter">Commander</a>
            </div>
        </div>

        <div class="sac-card">
            <img src="https://images.unsplash.com/photo-1553062407-98eeb64c6a62?auto=format&fit=crop&w=500&q=80" alt="Sac à dos">
            <div class="info">
                <h3>Sac à Dos Aventurier</h3>
                <p class="prix">189.000 TND</p>
                <a href="#" class="btn-acheter">Commander</a>
            </div>
        </div>

        <div class="sac-card">
            <img src="https://images.unsplash.com/photo-1544816155-12df9643f363?auto=format&fit=crop&w=500&q=80" alt="Sac de voyage">
            <div class="info">
                <h3>Sac de Voyage</h3>
                <p class="prix">220.000 TND</p>
                <a href="#" class="btn-acheter">Commander</a>
            </div>
        </div>

        <div class="sac-card">
            <img src="https://images.unsplash.com/photo-1598533123413-82c51b66a8a8?auto=format&fit=crop&w=500&q=80" alt="Pochette">
            <div class="info">
                <h3>Pochette Artisanale</h3>
                <p class="prix">75.000 TND</p>
                <a href="#" class="btn-acheter">Commander</a>
            </div>
        </div>

    </div>
</div>

</body>
</html>
