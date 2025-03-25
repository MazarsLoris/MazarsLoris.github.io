<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Data Analyst</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #222, #777);
            color: #fff;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }
        header {
            background-color: rgba(50, 50, 50, 0.9);
            padding: 1rem 0;
        }
        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            font-size: 1.5rem;
            font-weight: 600;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        nav ul li a:hover {
            color: #ddd;
        }
        main section {
            margin: 40px 0;
            padding: 40px;
            background-color: rgba(200, 200, 200, 0.1);
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        #about .content {
            text-align: center;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
        }
        .projects-section {
            background-color: #f4f4f4;
            color: #333;
        }
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .project {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .project-link {
            display: inline-block;
            margin-top: 10px;
            color: #007bff;
            text-decoration: none;
        }
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            gap: 15px;
        }
        .skill {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background-color: #fff;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .skill img {
            width: 50px;
            height: 50px;
            margin-bottom: 5px;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        .contact-form input, .contact-form textarea {
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .social-links {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .social-links a {
            margin: 0 15px;
        }
        .social-links img {
            width: 40px;
            height: 40px;
            transition: transform 0.3s ease;
        }
        .social-links img:hover {
            transform: scale(1.1);
        }
        footer {
            background-color: rgba(50, 50, 50, 0.9);
            padding: 20px 0;
            text-align: center;
        }
        .burger {
            display: none;
            cursor: pointer;
        }
        .burger div {
            width: 25px;
            height: 3px;
            background-color: white;
            margin: 5px;
            transition: all 0.3s ease;
        }
        @media screen and (max-width: 768px) {
            .nav-links {
                position: absolute;
                right: 0px;
                height: 92vh;
                top: 8vh;
                background-color: rgba(50, 50, 50, 0.9);
                display: flex;
                flex-direction: column;
                align-items: center;
                width: 100%;
                transform: translateX(100%);
                transition: transform 0.5s ease-in;
            }
            nav ul li {
                margin: 20px 0;
            }
            .burger {
                display: block;
            }
        }
        .nav-active {
            transform: translateX(0%);
        }
        .toggle .line1 {
            transform: rotate(-45deg) translate(-5px, 6px);
        }
        .toggle .line2 {
            opacity: 0;
        }
        .toggle .line3 {
            transform: rotate(45deg) translate(-5px, -6px);
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1 class="logo">Mon Portfolio</h1>
            <nav>
                <ul class="nav-links">
                    <li><a href="#about">À propos</a></li>
                    <li><a href="#projects">Projets</a></li>
                    <li><a href="#skills">Compétences</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <div class="burger">
                <div class="line1"></div>
                <div class="line2"></div>
                <div class="line3"></div>
            </div>
        </div>
    </header>
    <main>
        <section id="about" class="container">
            <div class="content">
                <h2>À propos de moi</h2>
                <p>Je suis un Data Analyst passionné par l'extraction d'insights à partir des données. Mon objectif est de transformer des données brutes en informations exploitables pour les entreprises.</p>
                <a href="#contact" class="btn">Me contacter</a>
            </div>
        </section>
        <section id="projects" class="projects-section">
            <div class="container">
                <h2>Mes Projets</h2>
                <div class="project-grid">
                    <div class="project">
                        <h3>Analyse des ventes</h3>
                        <p>Visualisation des tendances de vente avec Python.</p>
                        <a href="#" class="project-link">Voir le projet</a>
                    </div>
                    <div class="project">
                        <h3>Prédiction des prix immobiliers</h3>
                        <p>Modèle de
