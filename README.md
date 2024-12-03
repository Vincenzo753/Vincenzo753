<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Acquista abbigliamento elegante e moderno per uomo e donna">
    <title>Negozio di Abbigliamento</title>
    <style>
        /* Reset base */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        /* Logo - V e M incrociati */
        .logo {
            font-size: 40px;
            font-weight: bold;
            text-transform: uppercase;
            color: white;
            display: inline-block;
            background: linear-gradient(45deg, #d4af37, #fff);
            padding: 10px 20px;
            border-radius: 10px;
        }

        /* Header e navigazione */
        header {
            background-color: #222;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header nav {
            margin-top: 20px;
        }

        header nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
            text-transform: uppercase;
        }

        header nav a:hover {
            border-bottom: 2px solid #d4af37;
        }

        /* Sezione principale */
        .main-section {
            text-align: center;
            padding: 50px 0;
            background-color: #222;
            color: white;
        }

        .main-section h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .main-section p {
            font-size: 18px;
            max-width: 600px;
            margin: 0 auto 30px;
        }

        /* Categorie e immagini */
        .category-container {
            display: flex;
            justify-content: center;
            margin-top: 30px;
        }

        .category {
            background: #d4af37;
            color: white;
            border-radius: 10px;
            padding: 30px;
            margin: 0 20px;
            width: 200px;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .category:hover {
            background: #b68e2f;
        }

        .category h3 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        /* Footer */
        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }

        footer a {
            color: #d4af37;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <!-- Logo -->
        <div class="logo">V&M</div>
        <nav>
            <a href="#">Home</a>
            <a href="#uomo">Uomo</a>
            <a href="#donna">Donna</a>
        </nav>
    </header>

    <section class="main-section">
        <h2>Benvenuti nel nostro Negozio di Abbigliamento</h2>
        <p>Scopri la nostra collezione di abbigliamento moderno ed elegante per uomo e donna. Qualità e stile in ogni capo.</p>
        <div class="category-container">
            <div class="category" id="uomo">
                <h3>Uomo</h3>
                <p>Esplora la nostra selezione per uomo, con capi eleganti per ogni occasione.</p>
            </div>
            <div class="category" id="donna">
                <h3>Donna</h3>
                <p>Scopri i capi più trendy per donna, per un look sofisticato e alla moda.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Negozio di Abbigliamento | <a href="#">Contattaci</a></p>
    </footer>
</body>
</html>
