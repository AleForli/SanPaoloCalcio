# Sito ufficiale del San Paolo F.C.
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>San Paolo F.C.</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #000;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .logo {
            width: 100px;
        }
        .content {
            padding: 20px;
            background: #fff;
            margin: 20px 0;
        }
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Sanp" class="logo">
        <h1>San Paolo F.C.</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#servizi">Servizi</a>
        <a href="#contatti">Contatti</a>
        <a href="#shop">Shop</a>
    </nav>
    <div class="container">
        <section id="home" class="content">
            <h2>Home</h2>
            <p>Benvenuti sul sito ufficiale del San Paolo F.C.! Qui potete trovare tutte le informazioni sulla nostra squadra, gli ultimi aggiornamenti e molto altro.</p>
        </section>
        <section id="servizi" class="content">
            <h2>Servizi</h2>
            <p>Offriamo una gamma di servizi per i nostri tifosi, inclusi biglietti per le partite, merchandising ufficiale e abbonamenti stagionali.</p>
        </section>
        <section id="contatti" class="content">
            <h2>Contatti</h2>
            <p>Per qualsiasi domanda o informazione, non esitate a contattarci all'indirizzo email: info@sanpaolofc.com o chiamateci al numero: 123-456-7890.</p>
        </section>
        <section id="shop" class="content">
            <h2>Shop</h2>
            <p>Visitate il nostro shop per acquistare le maglie ufficiali del San Paolo F.C. e altri articoli di merchandising!</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 San Paolo F.C. Tutti i diritti riservati.</p>
    </footer>
</body>
</html>

