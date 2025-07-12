<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>PAGE 2</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            text-align: center;
            margin-top: 10px;
        }
        nav a {
            color: #333;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        iframe {
            width: 100%;
            height: 600px;
            border: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>Benvenuto al mio Sito</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">Chi Siamo</a>
        <a href="#menu">Menu PDF</a>
    </nav>

    <section id="home">
        <h2>Home</h2>
        <p>Questo è un sito di esempio per mostrarti come visualizzare un PDF.</p>
    </section>

    <section id="about">
        <h2>Chi Siamo</h2>
        <p>Siamo una piccola azienda che si occupa di sviluppo web.</p>
    </section>

    <section id="menu">
        <h2>Menu PDF</h2>
        <!-- PDF Embedded -->
        <iframe src="menu.pdf" title="Menu PDF"></iframe>
    </section>

    <footer>
        <p>&copy; 2025 Sito Esempio. Tutti i diritti riservati.</p>
    </footer>

</body>
</html>
