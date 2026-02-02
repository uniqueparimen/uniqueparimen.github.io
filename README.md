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
            justify-content: center
