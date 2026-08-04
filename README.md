<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amadou Kane — Tissus & Élégance</title>
    <style>
        :root {
            --bg-black: #0d0d0d;
            --card-black: #1a1a1a;
            --gold: #d4af37;
            --gold-light: #f3e5ab;
            --white: #ffffff;
            --gray: #b3b3b3;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-black);
            color: var(--white);
            line-height: 1.6;
        }

        header {
            background-color: var(--card-black);
            border-bottom: 2px solid var(--gold);
            padding: 20px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header h1 {
            color: var(--gold);
            font-size: 1.5rem;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        header p {
            color: var(--gray);
            font-size: 0.9rem;
            margin-top: 5px;
        }

        .hero {
            padding: 40px 20px;
            text-align: center;
            background: linear-gradient(rgba(13,13,13,0.9), rgba(13,13,13,0.9)), url('images/image_20.png') center/cover;
        }

        .hero h2 {
            color: var(--gold-light);
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        .hero p {
            color: var(--gray);
            font-size: 1rem;
            max-width: 600px;
            margin: 0 auto 20px auto;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .section-title {
            color: var(--gold);
            text-align: center;
            margin: 40px 0 20px 0;
            font-size: 1.5rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            border-bottom: 1px solid var(--gold);
            display: inline-block;
            padding-bottom: 5px;
        }

        .center-title {
            text-align: center;
        }

        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .product-card {
            background-color: var(--card-black);
            border: 1px solid #333;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s, border-color 0.3s;
        }

        .product-card:hover {
            border-color: var(--gold);
            transform: translateY(-5px);
        }

        .product-image {
            width: 100%;
            height: 300px;
            object-fit: cover;
            border-bottom: 1px solid #333;
        }

        .product-info {
            padding: 15px;
        }

        .product-category {
            color: var(--gold);
            font-size: 0.8rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 5px;
        }

        .product-name {
            font-size: 1.1rem;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .product-price {
            color: var(--gold-light);
            font-size: 1.2rem;
            font-weight: bold;
            margin-bottom: 15px;
        }

        .whatsapp-btn {
            display: block;
            width: 100%;
            background-color: #25d366;
            color: white;
            text-align: center;
            padding: 12px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            font-size: 0.95rem;
            transition: background 0.3s;
        }

        .whatsapp-btn:hover {
            background-color: #1ebe5d;
        }

        footer {
            background-color: var(--card-black);
            border-top: 2px solid var(--gold);
            text-align: center;
            padding: 30px 20px;
            color: var(--gray);
            font-size: 0.9rem;
        }

        footer p {
            margin-bottom: 10px;
        }

        footer span {
            color: var(--gold);
        }
    </style>
</head>
<body>

    <header>
        <h1>Amadou Kane</h1>
        <p>Tissus & Élégance — Dakar, Sénégal</p>
    </header>

    <section class="hero">
        <h2>L'Excellence du Tissu à Dakar</h2>
        <p>Découvrez notre collection exclusive de Gezner Super Magnum et de somptueux Tissus Brodés de prestige.</p>
    </section>

    <div class="container">
        
        <!-- SECTION 1 : GEZNER SUPER MAGNUM -->
        <div class="center-title">
            <h3 class="section-title">Gezner Super Magnum</h3>
        </div>

        <div class="products-grid">
            <div class="product-card">
                <img src="images/image_20.png" alt="Gezner Bleu Ciel" class="product-image">
                <div class="product-info">
                    <div class="product-category">Gezner Super Magnum</div>
                    <div class="product-name">Motif Géométrique Bleu Ciel</div>
                    <div class="product-price">Sur Demande</div>
                    <a href="https://wa.me/221776569673?text=Bonjour,%20je%20suis%20intéressé%20par%20le%20Gezner%20Bleu%20Ciel." class="whatsapp-btn" target="_blank">Commander sur WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/image_21.png" alt="Gezner Jaune Or" class="product-image">
                <div class="product-info">
                    <div class="product-category">Gezner Super Magnum</div>
                    <div class="product-name">Motif Floral Jaune Or</div>
                    <div class="product-price">Sur Demande</div>
                    <a href="https://wa.me/221776569673?text=Bonjour,%20je%20suis%20intéressé%20par%20le%20Gezner%20Jaune%20Or." class="whatsapp-btn" target="_blank">Commander sur WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/image_22.png" alt="Gezner Corail" class="product-image">
                <div class="product-info">
                    <div class="product-category">Gezner Super Magnum</div>
                    <div class="product-name">Grandes Fleurs Corail</div>
                    <div class="product-price">Sur Demande</div>
                    <a href="https://wa.me/221776569673?text=Bonjour,%20je%20suis%20intéressé%20par%20le%20Gezner%20Corail." class="whatsapp-btn" target="_blank">Commander sur WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/image_23.png" alt="Gezner Magenta" class="product-image">
                <div class="product-info">
                    <div class="product-category">Gezner Super Magnum</div>
                    <div class="product-name">Étoiles & Fleurs Magenta</div>
                    <div class="product-price">Sur Demande</div>
                    <a href="https://wa.me/221776569673?text=Bonjour,%20je%20suis%20intéressé%20par%20le%20Gezner%20Magenta." class="whatsapp-btn" target="_blank">Commander sur WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/image_24.png" alt="Gezner Gris Anthracite" class="product-image">
                <div class="product-info">
                    <div class="product-category">Gezner Super Magnum</div>
                    <div class="product-name">Floral Gris Anthracite</div>
                    <div class="product-price">Sur Demande</div>
                    <a href="https://wa.me/221776569673?text=Bonjour,%20je%20suis%20intéressé%20par%20le%20Gezner%20Gris%20Anthracite." class="whatsapp-btn" target="_blank">Commander sur WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/image_25.png" alt="Gezner Blanc Pur" class="product-image">
                <div class="product-info">
                    <div class="product-category">Gezner Super Magnum</div>
                    <div class="product-name">Texturé Blanc Pur</div>
                    <div class="product-price">Sur Demande</div>
                    <a href="https://wa.me/221776569673?text=Bonjour,%20je%20suis%20intéressé%20par%20le%20Gezner%20Blanc%20Pur." class="whatsapp-btn" target="_blank">Commander sur WhatsApp</a>
                </div>
            </div>
        </div>

        <!-- SECTION 2 : TISSUS BRODÉS -->
        <div class="center-title">
            <h3 class="section-title">Tissus Brodés de Prestige</h3>
        </div>

        <div class="products-grid">
            <div class="product-card">
                <img src="images/brode_violet.png" alt="Brodé Violet" class="product-image">
                <div class="product-info">
                    <div class="product-category">Tissu Brodé</div>
                    <div class="product-name">Dentelle Brodée Violette & Bleue</div>
                    <div class="product-price">Sur Demande</div>
                    <a href="https://wa.me/221776569673?text=Bonjour,%20je%20suis%20intéressé%20par%20le%20tissu%20brodé%20Violet." class="whatsapp-btn" target="_blank">Commander sur WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/brode_rouge.png" alt="Brodé Rouge" class="product-image">
                <div class="product-info">
                    <div class="product-category">Tissu Brodé</div>
                    <div class="product-name">Dentelle Brodée Rouge Éclatant</div>
                    <div class="product-price">Sur Demande</div>
                    <a href="https://wa.me/221776569673?text=Bonjour,%20je%20suis%20intéressé%20par%20le%20tissu%20brodé%20Rouge." class="whatsapp-btn" target="_blank">Commander sur WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/brode_bleu.png" alt="Brodé Bleu Clair" class="product-image">
                <div class="product-info">
                    <div class="product-category">Tissu Brodé</div>
                    <div class="product-name">Dentelle Brodée Bleu Clair</div>
                    <div class="product-price">Sur Demande</div>
                    <a href="https://wa.me/221776569673?text=Bonjour,%20je%20suis%20intéressé%20par%20le%20tissu%20brodé%20Bleu%20Clair." class="whatsapp-btn" target="_blank">Commander sur WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/brode_fuchsia.png" alt="Brodé Fuchsia" class="product-image">
                <div class="product-info">
                    <div class="product-category">Tissu Brodé</div>
                    <div class="product-name">Dentelle Brodée Rose Fuchsia</div>
                    <div class="product-price">Sur Demande</div>
                    <a href="https://wa.me/221776569673?text=Bonjour,%20je%20suis%20intéressé%20par%20le%20tissu%20brodé%20Fuchsia." class="whatsapp-btn" target="_blank">Commander sur WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/brode_noir_vert.png" alt="Brodé Noir & Vert" class="product-image">
                <div class="product-info">
                    <div class="product-category">Tissu Brodé</div>
                    <div class="product-name">Dentelle Brodée Noir & Vert</div>
                    <div class="product-price">Sur Demande</div>
                    <a href="https://wa.me/221776569673?text=Bonjour,%20je%20suis%20intéressé%20par%20le%20tissu%20brodé%20Noir%20et%20Vert." class="whatsapp-btn" target="_blank">Commander sur WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/brode_rose_poudre.png" alt="Brodé Rose Poudré" class="product-image">
                <div class="product-info">
                    <div class="product-category">Tissu Brodé</div>
                    <div class="product-name">Dentelle Brodée Rose Poudré</div>
                    <div class="product-price">Sur Demande</div>
                    <a href="https://wa.me/221776569673?text=Bonjour,%20je%20suis%20intéressé%20par%20le%20tissu%20brodé%20Rose%20Poudré." class="whatsapp-btn" target="_blank">Commander sur WhatsApp</a>
                </div>
            </div>
        </div>

    </div>

    <footer>
        <p>Boutique <span>Amadou Kane</span> — Dakar, Sénégal</p>
        <p>Contact WhatsApp : +221 77 656 96 73</p>
    </footer>

</body>
</html>
