<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Sito Semplice</title>
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
    </style>
</head>
<body>

    <header>
        <h1>Benvenuto al mio Sito</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">Chi Siamo</a>
        <a href="#contact">Contatti</a>
    </nav>

    <section id="home">
        <h2>Home</h2>
        <p>Questo è un sito di esempio per mostrarti come si struttura una pagina HTML semplice.</p>
    </section>

    <section id="about">
        <h2>Chi Siamo</h2>
        <p>Siamo una piccola azienda che si occupa di sviluppo web. Offriamo soluzioni innovative per i nostri clienti.</p>
    </section>

    <section id="contact">
        <h2>Contatti</h2>
        <p>Puoi contattarci via email all'indirizzo: <a href="mailto:info@example.com">info@example.com</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Sito Esempio. Tutti i diritti riservati.</p>
    </footer>

</body>
</html>
