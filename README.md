<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Ma Présentation</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        nav {
            background-color: #444;
            text-align: center;
            padding: 10px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        section {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }

        h2 {
            color: #333;
            border-bottom: 1px solid #ccc;
            padding-bottom: 5px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
        }

        .gallery img {
            width: 100px;
            height: auto;
            margin: 10px;
        }
    </style>
</head>
<body>

    <!-- En-tête -->
    <header>
        <h1>Bienvenue sur ma page personnelle</h1>
        <p>Créée en HTML simple</p>
    </header>

    <!-- Menu de navigation -->
    <nav>
        <a href="#presentation">Présentation</a>
        <a href="#passions">Passions</a>
        <a href="#projets">Projets</a>
        <a href="#galerie">Galerie</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Présentation -->
    <section id="presentation">
        <h2>Qui suis-je ?</h2>
        <p>Bonjour ! Je m'appelle Jean Dupont.</p>
        <p>Je suis étudiant en informatique et passionné par le développement web.</p>
        <p>Je vis en France et j'aime apprendre de nouvelles choses chaque jour.</p>
    </section>

    <!-- Passions -->
    <section id="passions">
        <h2>Mes passions</h2>
        <ul>
            <li>Programmation web (HTML, CSS, JavaScript)</li>
            <li>Création de jeux vidéo</li>
            <li>Lecture de science-fiction</li>
            <li>Musique électronique</li>
            <li>Photographie amateur</li>
        </ul>
    </section>

    <!-- Projets -->
    <section id="projets">
        <h2>Mes projets</h2>
        <p>Voici quelques projets sur lesquels j’ai travaillé récemment :</p>
        <ol>
            <li>Un site de recettes de cuisine en HTML/CSS</li>
            <li>Un jeu de plateforme simple en JavaScript</li>
            <li>Un portfolio personnel pour montrer mes créations</li>
        </ol>
    </section>

    <!-- Galerie -->
    <section id="galerie">
        <h2>Galerie d’images</h2>
        <div class="gallery">
            <img src="image1.jpg" alt="Projet 1">
            <img src="image2.jpg" alt="Projet 2">
            <img src="image3.jpg" alt="Projet 3">
        </div>
        <p>(Images fictives — à personnaliser avec tes propres images)</p>
    </section>

    <!-- Contact -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Tu peux me contacter par email : <a href="mailto:jean.dupont@email.com">jean.dupont@email.com</a></p>
        <p>Ou me suivre sur les réseaux sociaux :</p>
        <ul>
            <li><a href="#">Twitter</a></li>
            <li><a href="#">LinkedIn</a></li>
            <li><a href="#">GitHub</a></li>
        </ul>
    </section>

    <!-- Pied de page -->
    <footer>
        <p>&copy; 2025 Jean Dupont - Tous droits réservés.</p>
    </footer>

</body>
</html>
