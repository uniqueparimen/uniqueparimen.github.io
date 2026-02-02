<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma Boutique de Sacs</title>
    <style>
        /* Style général */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }

        header {
            background-color: #333;
            color: white;
            padding: 2rem;
            text-align: center;
        }

        /* Grille des produits */
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 0 20px;
        }

        /* Carte Produit */
        .sac-card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            overflow: hidden;
            transition: transform 0.3s;
            text-align: center;
        }

        .sac-card:hover {
            transform: translateY(-5px);
        }

        .sac-card img {
            width: 100%;
            height: 250px;
            object-fit: cover; /* Garde les proportions de l'image */
            background-color: #ddd;
        }

        .info {
            padding: 15px;
        }

        .info h3 {
            margin: 10px 0;
            color: #444;
        }

        .prix {
            font-size: 1.2rem;
            font-weight: bold;
            color: #e67e22;
            margin-bottom: 15px;
        }

        .btn-acheter {
            display: inline-block;
            background-color: #27ae60;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-bottom: 10px;
        }

        .btn-acheter:hover {
            background-color: #2ecc71;
        }
    </style>
</head>
<body>

<header>
    <h1>Ma Collection de Sacs</h1>
    <p>Trouvez le compagnon idéal pour votre quotidien</p>
</header>

<div class="container">
    
    <div class="sac-card">
        <img src="https://via.placeholder.com/300x250?text=Sac+à+main" alt="Sac à main">
        <div class="info">
            <h3>Sac à Main Élégant</h3>
            <p class="prix">45,00 €</p>
            <a href="#" class="btn-acheter">Ajouter au panier</a>
        </div>
    </div>

    <div class="sac-card">
        <img src="https://via.placeholder.com/300x250?text=Sac+à+dos" alt="Sac à dos">
        <div class="info">
            <h3>Sac à Dos Urbain</h3>
            <p class="prix">55,00 €</p>
            <a href="#" class="btn-acheter">Ajouter au panier</a>
        </div>
    </div>

    <div class="sac-card">
        <img src="https://via.placeholder.com/300x250?text=Sac+de+voyage" alt="Sac de voyage">
        <div class="info">
            <h3>Sac de Voyage Cuir</h3>
            <p class="prix">89,00 €</p>
            <a href="#" class="btn-acheter">Ajouter au panier</a>
        </div>
    </div>

    <div class="sac-card">
        <img src="https://via.placeholder.com/300x250?text=Pochette" alt="Pochette">
        <div class="info">
            <h3>Pochette de Soirée</h3>
            <p class="prix">29,99 €</p>
            <a href="#" class="btn-acheter">Ajouter au panier</a>
        </div>
    </div>

</div>

</body>
</html>
