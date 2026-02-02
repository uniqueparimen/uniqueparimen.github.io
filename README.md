<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma Collection de Sacs Artisanaux</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8; /* Fond légèrement gris pour un contraste doux */
            color: #333;
        }

        header {
            text-align: center;
            padding: 40px 20px;
            background-color: #fff;
            border-bottom: 1px solid #eee;
            margin-bottom: 30px;
        }

        header h1 {
            font-size: 2.5em;
            color: #222;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.1em;
            color: #555;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* 3 colonnes flexibles */
            gap: 30px; /* Espace entre les cartes */
            padding: 0 20px;
        }

        .sac-card {
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08); /* Ombre plus douce */
            overflow: hidden;
            text-align: center;
            transition: transform 0.2s ease-in-out;
            display: flex; /* Utilisation de flexbox pour aligner le contenu */
            flex-direction: column;
        }

        .sac-card:hover {
            transform: translateY(-5px);
        }

        .sac-card img {
            width: 100%;
            height: 280px; /* Hauteur fixe pour toutes les images */
            object-fit: cover; /* Recadre les images pour remplir l'espace */
            border-bottom: 1px solid #eee;
        }

        .info {
            padding: 15px;
            flex-grow: 1; /* Permet à l'info de prendre l'espace restant */
            display: flex;
            flex-direction: column;
            justify-content: space-between; /* Espace les éléments verticalement */
        }

        .info h3 {
            font-size: 1.2em;
            margin: 10px 0 5px 0;
            color: #333;
        }

        .info p.categorie { /* Style pour les catégories si tu veux les ajouter */
            font-size: 0.9em;
            color: #888;
            margin-bottom: 10px;
        }

        .prix {
            font-size: 1.3em;
            font-weight: bold;
            color: #e67e22; /* Couleur orange pour le prix */
            margin: 10px 0 15px 0;
        }

        .btn-whatsapp {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            background-color: #25D366; /* Vert WhatsApp */
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s ease;
            border: none;
            cursor: pointer;
            margin-top: auto; /* Pousse le bouton vers le bas */
        }

        .btn-whatsapp:hover {
            background-color: #128C7E;
        }

        .btn-whatsapp .icon {
            margin-right: 8px;
            width: 18px;
            height: 18px;
            vertical-align: middle;
        }
    </style>
</head>
<body>

<header>
    <h1>MA COLLECTION DE SACS</h1>
    <p>Trouvez le compagnon idéal pour votre quotidien</p>
</header>

<div class="container">
    
    <div class="sac-card">
        <img src="https://i.ibb.co/3zd5s0Y/Image-1.jpg" alt="Sac Brodé Naturel">
        <div class="info">
            <h3>Sac Brodé Naturel</h3>
            <p class="prix">85,000 TND</p>
            <button class="btn-whatsapp" onclick="sendWhatsApp('Sac Brodé Naturel', '85,000 TND')">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/1200px-WhatsApp.svg.png" alt="WhatsApp Icon" class="icon">
                Commander sur WhatsApp
            </button>
        </div>
    </div>

    <div class="sac-card">
        <img src="https://i.ibb.co/j3n92k1/Image-2.jpg" alt="Sac Journal Chic">
        <div class="info">
            <h3>Sac Journal Chic</h3>
            <p class="prix">93,200 TND</p>
            <button class="btn-whatsapp" onclick="sendWhatsApp('Sac Journal Chic', '93,200 TND')">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/1200px-WhatsApp.svg.png" alt="WhatsApp Icon" class="icon">
                Commander sur WhatsApp
            </button>
        </div>
    </div>

    <div class="sac-card">
        <img src="https://i.ibb.co/L5w2R3D/Image-3.jpg" alt="Sac Tressé Bohème">
        <div class="info">
            <h3>Sac Tressé Bohème</h3>
            <p class="prix">110,000 TND</p>
            <button class="btn-whatsapp" onclick="sendWhatsApp('Sac Tressé Bohème', '110,000 TND')">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/1200px-WhatsApp.svg.png" alt="WhatsApp Icon" class="icon">
                Commander sur WhatsApp
            </button>
        </div>
    </div>

    <div class="sac-card">
        <img src="https://i.ibb.co/P4725hP/Image-4.jpg" alt="Sac Urbain Géométrique">
        <div class="info">
            <h3>Sac Urbain Géométrique</h3>
            <p class="prix">93,000 TND</p>
            <button class="btn-whatsapp" onclick="sendWhatsApp('Sac Urbain Géométrique', '93,000 TND')">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/1200px-WhatsApp.svg.png" alt="WhatsApp Icon" class="icon">
                Commander sur WhatsApp
            </button>
        </div>
    </div>

    <div class="sac-card">
        <img src="https://i.ibb.co/M95N90S/Image-6.jpg" alt="Sac Paille Cuir">
        <div class="info">
            <h3>Sac Paille Cuir</h3>
            <p class="prix">120,000 TND</p>
            <button class="btn-whatsapp" onclick="sendWhatsApp('Sac Paille Cuir', '120,000 TND')">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/1200px-WhatsApp.svg.png" alt="WhatsApp Icon" class="icon">
                Commander sur WhatsApp
            </button>
        </div>
    </div>

    <div class="sac-card">
        <img src="https://i.ibb.co/n6z4k14/Image-7.jpg" alt="Sac Franges Paillettes">
        <div class="info">
            <h3>Sac Franges Paillettes</h3>
            <p class="prix">89,000 TND</p>
            <button class="btn-whatsapp" onclick="sendWhatsApp('Sac Franges Paillettes', '89,000 TND')">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/1200px-WhatsApp.svg.png" alt="WhatsApp Icon" class="icon">
                Commander sur WhatsApp
            </button>
        </div>
    </div>
    
    <div class="sac-card">
        <img src="https://i.ibb.co/3s682Xh/Image-8.jpg" alt="Sac Fleurs Bleues">
        <div class="info">
            <h3>Sac Fleurs Bleues</h3>
            <p class="prix">89,000 TND</p>
            <button class="btn-whatsapp" onclick="sendWhatsApp('Sac Fleurs Bleues', '89,000 TND')">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/1200px-WhatsApp.svg.png" alt="WhatsApp Icon" class="icon">
                Commander sur WhatsApp
            </button>
        </div>
    </div>

    <div class="sac-card">
        <img src="https://i.ibb.co/sK65Wb1/Image-9.jpg" alt="Sac Fleurs Élégant">
        <div class="info">
            <h3>Sac Fleurs Élégant</h3>
            <p class="prix">95,000 TND</p>
            <button class="btn-whatsapp" onclick="sendWhatsApp('Sac Fleurs Élégant', '95,000 TND')">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/1200px-WhatsApp.svg.png" alt="WhatsApp Icon" class="icon">
                Commander sur WhatsApp
            </button>
        </div>
    </div>

    <div class="sac-card">
        <img src="https://i.ibb.co/jH0Yd7j/Image-10.jpg" alt="Sac Floral Élégant">
        <div class="info">
            <h3>Sac Floral Élégant</h3>
            <p class="prix">99,000 TND</p>
            <button class="btn-whatsapp" onclick="sendWhatsApp('Sac Floral Élégant', '99,000 TND')">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/1200px-WhatsApp.svg.png" alt="WhatsApp Icon" class="icon">
                Commander sur WhatsApp
            </button>
        </div>
    </div>
    
    </div>

<script>
    function sendWhatsApp(nomSac, prixSac) {
        const telephone = "21690295149"; // Ton numéro de téléphone
        const message = `Bonjour ! Je suis intéressé(e) par le sac suivant :\n\n- Nom : ${nomSac}\n- Prix : ${prixSac}\n\nMerci de me donner plus de détails.`;
        
        const url = `https://wa.me/${telephone}?text=${encodeURIComponent(message)}`;
        window.open(url, '_blank');
    }
</script>

</body>
</html>
