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
            scroll-behavior: smooth;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }
        header {
            background-color: rgba(50, 50, 50, 0.9);
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
            color: #ddd;
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
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }
        .fade-in.show {
            opacity: 1;
            transform: translateY(0);
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
            nav ul {
                display: none;
                flex-direction: column;
                background-color: rgba(50, 50, 50, 0.9);
                position: absolute;
                right: 0;
                top: 60px;
                width: 100%;
                text-align: center;
            }
            nav ul.active {
                display: flex;
            }
            .burger {
                display: block;
            }
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
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <div class="burger" onclick="toggleMenu()">
                <div class="line1"></div>
                <div class="line2"></div>
                <div class="line3"></div>
            </div>
        </div>
    </header>
    <main>
        <section id="about" class="container fade-in">
            <h2>À propos de moi</h2>
            <p>Je suis un Data Analyst passionné par l'analyse de données et la création de solutions basées sur les insights.</p>
            <a href="#contact" class="btn">Me contacter</a>
        </section>
        <section id="projects" class="container fade-in">
            <h2>Mes Projets</h2>
            <p>Découvrez mes réalisations et études de cas.</p>
        </section>
        <section id="contact" class="container fade-in">
            <h2>Contact</h2>
            <p>Envoyez-moi un message et discutons de vos projets !</p>
        </section>
    </main>
    <script>
        function toggleMenu() {
            const nav = document.querySelector('.nav-links');
            nav.classList.toggle('active');
        }
        document.addEventListener("DOMContentLoaded", function() {
            const elements = document.querySelectorAll(".fade-in");
            const observer = new IntersectionObserver(entries => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add("show");
                    }
                });
            }, { threshold: 0.2 });
            elements.forEach(element => {
                observer.observe(element);
            });
        });
    </script>
</body>
</html>
