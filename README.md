

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Notre Sélection Manga & BD</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        .manga-container {
            background-color: #fff;
            border-radius: 8px;
            margin-bottom: 20px;
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            display: flex; /* Pour un layout plus sympa */
            align-items: center; /* Centrer verticalement le contenu */
        }
        .manga-image {
            flex-shrink: 0; /* Empêche l'image de rétrécir */
            width: 80px; /* Taille de l'image */
            height: 100px; /* Taille de l'image */
            margin-right: 15px;
            border-radius: 4px;
            object-fit: cover; /* Assure que l'image couvre bien la zone */
            background-color: #e0e0e0; /* Couleur de fond si l'image ne charge pas */
        }
        .manga-info {
            flex-grow: 1; /* Permet au texte de prendre l'espace restant */
        }
        h2 {
            color: #0056b3;
            margin-top: 0;
        }
        p {
            margin-bottom: 0;
        }
        .section-title {
            text-align: center;
            margin-bottom: 30px;
            color: #d32f2f; /* Une couleur qui ressort */
        }
    </style>
</head>
<body>

    <h1 class="section-title">Nos Coups de Cœur Manga & BD !</h1>

    <div class="manga-container">
        <div class="manga-image" style="background-image: url('placeholder_naruto.jpg');"></div>
        <div class="manga-info">
            <h2>1. Naruto</h2>
            <p>Un jeune ninja rêve de devenir Hokage, le chef de son village. Suivez son parcours semé d'embûches, d'amitiés et de batailles épiques ! Prépare-toi à crier "Rasengan" !</p>
        </div>
    </div>

    <div class="manga-container">
        <div class="manga-image" style="background-image: url('placeholder_onepiece.jpg');"></div>
        <div class="manga-info">
            <h2>2. One Piece</h2>
            <p>Luffy et son équipage de pirates parcourent les mers à la recherche du légendaire trésor, le One Piece. Aventures, humour et amitié au rendez-vous ! Le trésor est réel !</p>
        </div>
    </div>

    <div class="manga-container">
        <div class="manga-image" style="background-image: url('placeholder_aot.jpg');"></div>
        <div class="manga-info">
            <h2>3. Attack on Titan (Shingeki no Kyojin)</h2>
            <p>Dans un monde où l'humanité est menacée par des géants mangeurs d'hommes, Eren Yeager se bat pour la survie de sa race. La liberté a un prix... très élevé.</p>
        </div>
    </div>

    <div class="manga-container">
        <div class="manga-image" style="background-image: url('placeholder_mha.jpg');"></div>
        <div class="manga-info">
            <h2>4. My Hero Academia (Boku no Hero Academia)</h2>
            <p>Dans un monde où presque tout le monde a des super-pouvoirs, Izuku Midoriya rêve de devenir un héros malgré son absence de pouvoirs. PLUS ULTRA !</p>
        </div>
    </div>

    <div class="manga-container">
        <div class="manga-image" style="background-image: url('placeholder_deathnote.jpg');"></div>
        <div class="manga-info">
            <h2>5. Death Note</h2>
            <p>Un lycéen découvre un carnet qui lui permet de tuer quiconque en écrivant son nom. Une lutte intellectuelle entre lui et un détective brillant s'ensuit. Lequel est le plus maléfique ?</p>
        </div>
    </div>

    <div class="manga-container">
        <div class="manga-image" style="background-image: url('placeholder_demonslayer.jpg');"></div>
        <div class="manga-info">
            <h2>6. Demon Slayer (Kimetsu no Yaiba)</h2>
            <p>Tanjiro Kamado se bat contre des démons pour sauver sa sœur et venger sa famille dans ce récit plein d'action et d'émotion. La lame du souffle de l'eau frappe fort !</p>
        </div>
    </div>

    <div class="manga-container">
        <div class="manga-image" style="background-image: url('placeholder_dragonball.jpg');"></div>
        <div class="manga-info">
            <h2>7. Dragon Ball</h2>
            <p>Les aventures de Goku depuis son enfance jusqu'à l'âge adulte, alors qu'il cherche des Dragon Balls pour exaucer ses vœux et affronter des ennemis puissants. C'est parti pour un Kamehameha !</p>
        </div>
    </div>

    <div class="manga-container">
        <div class="manga-image" style="background-image: url('placeholder_fma.jpg');"></div>
        <div class="manga-info">
            <h2>8. Fullmetal Alchemist</h2>
            <p>Deux frères utilisent l'alchimie pour tenter de ramener leur mère à la vie, mais découvrent que certains sacrifices ne valent pas le prix. L'équivalent de la douleur est la loi.</p>
        </div>
    </div>

    <div class="manga-container">
        <div class="manga-image" style="background-image: url('placeholder_sao.jpg');"></div>
        <div class="manga-info">
            <h2>9. Sword Art Online</h2>
            <p>Des joueurs se retrouvent piégés dans un jeu vidéo où mourir dans le jeu signifie mourir dans la vraie vie. Une aventure palpitante commence ! Game Over ? Pas encore !</p>
        </div>
    </div>

    <div class="manga-container">
        <div class="manga-image" style="background-image: url('placeholder_tokyoghoul.jpg');"></div>
        <div class="manga-info">
            <h2>10. Tokyo Ghoul</h2>
            <p>Ken Kaneki devient un hybride humain-goule après une rencontre fatidique. Sa lutte pour trouver sa place dans ce nouveau monde est poignante. Manger ou être mangé...</p>
        </div>
    </div>

    <div class="manga-container">
        <div class="manga-image" style="background-image: url('placeholder_jujutsu.jpg');"></div>
        <div class="manga-info">
            <h2>11. Jujutsu Kaisen</h2>
            <p>Yuji Itadori avale un objet maudit et se retrouve au cœur d'un monde de sorciers et de démons. Son combat contre le mal commence !</p>
        </div>
    </div>

    <div class="manga-container">
        <div class="manga-image" style="background-image: url('placeholder_onepunch.jpg');"></div>
        <div class="manga-info">
            <h2>12. One-Punch Man</h2>
            <p>Saitama est un héros tellement puissant qu'il bat tous ses adversaires d'un seul coup. Mais cette puissance lui vaut... l'ennui !</p>
        </div>
    </div>

    <div class="manga-container

