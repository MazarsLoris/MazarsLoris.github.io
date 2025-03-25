<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Data Analyst</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: #1e1e1e;
            color: #fff;
            scroll-behavior: smooth;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }
        header {
            background-color: #222;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
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
            color: #007bff;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #0056b3;
        }
        .skills, .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .skill, .project {
            background: #333;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            width: 180px;
        }
        .skill i, .project i {
            font-size: 40px;
            margin-bottom: 10px;
        }
        .social-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }
        .social-links a {
            color: white;
            font-size: 30px;
            transition: color 0.3s;
        }
        .social-links a:hover {
            color: #007bff;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1 class="logo">Mon Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="#about">À propos</a></li>
                    <li><a href="#projects">Projets</a></li>
                    <li><a href="#skills">Compétences</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <main>
        <section id="about" class="container">
            <h2>À propos de moi</h2>
            <p><a href="https://github.com/MazarsLoris/Human-Resources-">Projet Human Ressources/a>.</p>
        </section>
        <section id="projects" class="container">
            <h2>Mes Projets</h2>
            <div class="projects">
                <div class="project"><i class="fas fa-chart-bar"></i><p>Analyse des ventes avec Python</p></div>
                <div class="project"><i class="fas fa-chart-line"></i><p>Visualisation des tendances avec Power BI</p></div>
                <div class="project"><i class="fas fa-home"></i><p>Prédiction des prix immobiliers</p></div>
            </div>
        </section>
        <section id="skills" class="container">
            <h2>Compétences</h2>
            <div class="skills">
                <div class="skill"><i class="fab fa-python"></i><p>Python (Pandas, NumPy, Matplotlib)</p></div>
                <div class="skill"><i class="fab fa-r-project"></i><p>R (ggplot2, dplyr, tidyr)</p></div>
                <div class="skill"><i class="fas fa-database"></i><p>SQL</p></div>
                <div class="skill"><i class="fas fa-chart-line"></i><p>Power BI</p></div>
                <div class="skill"><i class="fas fa-table"></i><p>Excel</p></div>
                <div class="skill"><i class="fas fa-chart-pie"></i><p>SAS</p></div>
            </div>
        </section>
        <section id="contact" class="container">
            <h2>Contact</h2>
            <div class="social-links">
                <a href="https://github.com" target="_blank"><i class="fab fa-github"></i></a>
                <a href="https://linkedin.com" target="_blank"><i class="fab fa-linkedin"></i></a>
            </div>
        </section>
    </main>
</body>
</html>
