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
            text-align: center;
        }
        header .container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .logo {
            font-size: 1.5rem;
            font-weight: 600;
        }
        .slogan {
            font-size: 0.9rem;
            font-style: italic;
            color: #ddd;
            margin-top: 5px;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            margin-top: 10px;
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
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1 class="logo">Mon Portfolio</h1>
            <p class="slogan">Data Analyst : Transformez les données en décisions éclairées !</p>
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
            <p>Data Analyst passionné par l'analyse et la visualisation des données.</p>
        </section>
        <section id="projects" class="container">
            <h2>Mes Projets</h2>
            <div class="projects">
                <div class="project"><i class="fas fa-chart-bar"></i><p>Analyse des ventes avec Python</p></div>
                <div class="project"><i class="fas fa-chart-line"></i><p>Visualisation des tendances avec Power BI</p></div>
                <div class="project"><i class="fas fa-home"></i><p>Prédiction des prix immobiliers</p></div>
            </div>
        </section>
    </main>
</body>
</html>
