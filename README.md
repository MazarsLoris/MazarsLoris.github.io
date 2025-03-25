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
            background-color: #f0f8ff;
            color: #333;
        }
        header {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            margin: 20px;
            padding: 20px;
            background-color: #e6f7ff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .project {
            background-color: #b3e0ff;
            padding: 10px;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #004080;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mon Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">À propos</a></li>
                <li><a href="#projects">Projets</a></li>
                <li><a href="#skills">Compétences</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>   
    <section id="about">
        <h2>À propos</h2>
        <p>Je suis un Data Analyst passionné par l'analyse des données et la visualisation.</p>
    </section>
    <section id="projects">
        <h2>Projets</h2>
        <div class="project">
            <h3>Analyse des ventes</h3>
            <p>Exploration et visualisation des tendances de vente.</p>
        </div>
        <div class="project">
            <h3>Prédiction des prix</h3>
            <p>Modèle de machine learning pour prédire les prix immobiliers.</p>
        </div>
    </section>  
    <section id="skills">
        <h2>Compétences</h2>
        <ul>
            <li>Python (Pandas, NumPy, Matplotlib, Seaborn)</li>
            <li>SQL</li>
            <li>Tableau & Power BI</li>
            <li>Statistiques & Machine Learning</li>
        </ul>
    </section>   
    <section id="contact">
        <h2>Contact</h2>
        <p>Email : <a href="mailto:exemple@email.com">exemple@email.com</a></p>
        <p>GitHub : <a href="https://github.com/votreprofil" target="_blank">Mon GitHub</a></p>
    </section>   
    <footer>
        <p>&copy; 2025 Mon Portfolio</p>
    </footer>
</body>
</html>
