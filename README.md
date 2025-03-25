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
            color: #333;
        }
        header {
            background-color: rgba(50, 50, 50, 0.9);
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
            background-color: rgba(200, 200, 200, 0.9);
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .project {
            background-color: rgba(170, 170, 170, 0.9);
            padding: 10px;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        .skills-list li {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }
        .skills-list img {
            width: 30px;
            height: 30px;
            margin-right: 10px;
        }
        .social-links {
            display: flex;
            justify-content: center;
            margin-top: 10px;
        }
        .social-links a {
            margin: 0 10px;
        }
        .social-links img {
            width: 40px;
            height: 40px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: rgba(50, 50, 50, 0.9);
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
        <ul class="skills-list">
            <li><img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" alt="Pandas"> <a href="https://pandas.pydata.org/" target="_blank">Pandas</a></li>
            <li><img src="https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg" alt="NumPy"> <a href="https://numpy.org/" target="_blank">NumPy</a></li>
            <li><img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" alt="Matplotlib"> <a href="https://matplotlib.org/" target="_blank">Matplotlib</a></li>
            <li><img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" alt="Seaborn"> <a href="https://seaborn.pydata.org/" target="_blank">Seaborn</a></li>
            <li><img src="https://upload.wikimedia.org/wikipedia/commons/8/87/Sql_data_base_with_logo.png" alt="SQL"> <a href="https://www.mysql.com/" target="_blank">SQL</a></li>
            <li><img src="https://upload.wikimedia.org/wikipedia/commons/4/45/Tableau_Logo.png" alt="Tableau"> <a href="https://www.tableau.com/" target="_blank">Tableau</a></li>
            <li><img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" alt="Power BI"> <a href="https://powerbi.microsoft.com/" target="_blank">Power BI</a></li>
        </ul>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Email : <a href="mailto:exemple@email.com">exemple@email.com</a></p>
        <div class="social-links">
            <a href="https://github.com/votreprofil" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" alt="GitHub">
            </a>
            <a href="https://www.linkedin.com/in/votreprofil" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn">
            </a>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Mon Portfolio</p>
    </footer>
</body>
</html>
