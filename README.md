<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Presentación de Francisco Mazzeo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77d42a 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        .content {
            padding: 20px;
            background: #fff;
            margin-top: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            margin-top: 10px;
        }
        .center {
            text-align: center;
        }
        .github-stats {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .github-stats img {
            margin: 0 10px;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0,0,0,0.3);
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>ElMalditoNINE9</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#about">Sobre Mí</a></li>
                    <li><a href="#projects">Proyectos</a></li>
                    <li><a href="#contact">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div class="container content">
        <section id="about" class="center">
            <h1>¡Hola, soy Francisco Mazzeo! 👋</h1>
            <p>🐔🐔🐔🔪🔪</p>
        </section>
        <section id="projects" class="center">
            <h2>Proyectos</h2>
            <a href="https://github.com/anuraghazra/github-readme-stats">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ElMalditoNINE9&layout=compact&theme=blueberry" alt="Top Langs" width="100%">
            </a>
            <div class="github-stats">
                <img src="https://github-readme-stats.vercel.app/api?username=ElMalditoNINE9&show_icons=true&theme=dark" alt="GitHub Stats">
            </div>
        </section>
        <section id="contact" class="center">
            <h2>Contacto</h2>
            <p>Puedes encontrar más sobre mi carrera y mis proyectos en mi <a href="https://www.notion.so/tu-link-a-la-pagina-de-notion" target="_blank">página de Notion</a>.</p>
        </section>
    </div>
    <footer>
        <p>ElMalditoNINE9 &copy; 2024</p>
    </footer>
</body>
</html>
