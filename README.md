# Cards
Landing Of Bybit Card

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bybit - Trading Crypto Professionnel</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Arial, sans-serif;
        }

        body {
            background-color: #0F172A;
            color: white;
        }

        .header {
            background: linear-gradient(135deg, #1E293B 0%, #0F172A 100%);
            padding: 1rem;
            text-align: center;
        }

        .hero {
            padding: 4rem 2rem;
            text-align: center;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1.5rem;
            color: #38BDF8;
        }

        .cta-button {
            display: inline-block;
            background: #2563EB;
            color: white;
            padding: 1rem 2rem;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            margin: 2rem 0;
            transition: transform 0.3s;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .cta-button:hover {
            transform: translateY(-2px);
            background: #1D4ED8;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .feature-card {
            background: #1E293B;
            padding: 2rem;
            border-radius: 12px;
            text-align: center;
        }

        .feature-card i {
            font-size: 2rem;
            color: #38BDF8;
            margin-bottom: 1rem;
        }

        footer {
            text-align: center;
            padding: 2rem;
            background: #1E293B;
            margin-top: 4rem;
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <img src="https://www.bybit.com/app/themes/bybit/assets/images/logo.svg" alt="Bybit Logo" width="120">
    </header>

    <section class="hero">
        <h1>Commencez à trader comme un pro</h1>
        <p>Rejoignez la plateforme de trading crypto n°1 avec +15 millions d'utilisateurs</p>
        
        <a href="https://www.bybit.com/invite?ref=YMZG4E" class="cta-button">
            S'inscrire Maintenant
        </a>

        <div class="features">
            <div class="feature-card">
                <i class="fas fa-coins"></i>
                <h3>Frais Ultra Bas</h3>
                <p>Frais de trading parmi les plus compétitifs du marché</p>
            </div>
            <div class="feature-card">
                <i class="fas fa-shield-alt"></i>
                <h3>Sécurité Maximale</h3>
                <p>Protection des fonds et cold wallets institutionnels</p>
            </div>
            <div class="feature-card">
                <i class="fas fa-rocket"></i>
                <h3>Leverage 100x</h3>
                <p>Possibilité de trader avec effet de levier jusqu'à 1:100</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2024 Bybit. Tous droits réservés.</p>
    </footer>
</body>
</html>
