 html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Schmuck Shop</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">✨ SchmuckShop</div>
        <nav>
            <ul>
                <li><a href="#home">Startseite</a></li>
                <li><a href="#products">Produkte</a></li>
                <li><a href="#about">Über uns</a></li>
                <li><a href="#contact">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Edler Schmuck für jeden Anlass</h1>
        <p>Entdecke einzigartige Designs und handgefertigte Schmuckstücke.</p>
        <a href="#products" class="btn">Jetzt shoppen</a>
    </section>

    <section id="products">
        <h2>Unsere Kollektion</h2>
        <div class="product-grid">
            <div class="product">
                <img src="ring.jpg" alt="Goldener Ring">
                <h3>Goldener Ring</h3>
                <p>Preis: €120</p>
                <button>In den Warenkorb</button>
            </div>
            <div class="product">
                <img src="necklace.jpg" alt="Silberne Halskette">
                <h3>Silberne Halskette</h3>
                <p>Preis: €95</p>
                <button>In den Warenkorb</button>
            </div>
            <div class="product">
                <img src="bracelet.jpg" alt="Diamant Armband">
                <h3>Diamant Armband</h3>
                <p>Preis: €150</p>
                <button>In den Warenkorb</button>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>Über uns</h2>
        <p>Wir sind ein Familienunternehmen, das seit über 10 Jahren mit Leidenschaft Schmuck entwirft. Unsere Produkte stehen für Qualität und Einzigartigkeit.</p>
    </section>

    <section id="contact">
        <h2>Kontakt</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">E-Mail:<
