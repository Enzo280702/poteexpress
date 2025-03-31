# <!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>PoteExpress - Livraison entre Potes</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f7f7f7; }
    header { background: #2b8a3e; color: white; padding: 20px; text-align: center; }
    .hero { padding: 40px 20px; text-align: center; background: white; }
    .hero h1 { font-size: 2.5em; margin-bottom: 10px; }
    .hero p { font-size: 1.2em; margin-bottom: 20px; }
    .btn { background: #2b8a3e; color: white; padding: 15px 25px; border: none; font-size: 1em; cursor: pointer; margin: 10px; text-decoration: none; display: inline-block; border-radius: 5px; }
    .counter { background: #e0ffe5; padding: 20px; text-align: center; font-size: 1.2em; }
    .values, .form-section { padding: 30px 20px; text-align: center; }
    .form-section input, .form-section button { padding: 10px; margin: 10px; font-size: 1em; }
    footer { background: #2b8a3e; color: white; text-align: center; padding: 15px; margin-top: 40px; }
  </style>
</head>
<body>
  <header>
    <h1>PoteExpress</h1>
    <p>Livraison partout en France, entre potes. Moins cher, plus proche, plus humain.</p>
  </header>

  <div class="hero">
    <h1>Livrez vos colis entre potes</h1>
    <p>Envoyez ou livrez un colis facilement, humainement et à petit prix !</p>
    <a href="#form" class="btn">Je veux envoyer un colis</a>
    <a href="#form" class="btn">Je veux livrer un colis</a>
  </div>

  <div class="counter">
    <p><strong>+18 000</strong> colis déjà livrés • <strong>+12 000</strong> utilisateurs inscrits</p>
    <p>Lancement officiel dans : <strong>3 jours, 12h, 43min</strong></p>
  </div>

  <div class="values">
    <h2>Pourquoi PoteExpress ?</h2>
    <p>✅ Écologique – pas de trajet inutile</p>
    <p>✅ Humain – chaque colis est une rencontre</p>
    <p>✅ Moins cher que La Poste</p>
  </div>

  <div id="form" class="form-section">
    <h2>Préinscris-toi maintenant</h2>
    <input type="text" placeholder="Nom" />
    <input type="email" placeholder="Email" />
    <button class="btn">S'inscrire</button>
  </div>

  <footer>
    &copy; 2025 PoteExpress. Tous droits réservés.
  </footer>
</body>
</html>
