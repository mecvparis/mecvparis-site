<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MECV PARIS - Église Évangélique</title>
  <style>
    :root {
      --primary: #1a365d;
      --secondary: #2b6cb0;
      --accent: #d69e2e;
      --bg: #f7fafc;
      --text: #2d3748;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: Arial, sans-serif; line-height: 1.6; background-color: var(--bg); color: var(--text); }
    header { background-color: var(--primary); color: white; padding: 2rem 1rem; text-align: center; }
    header h1 { font-size: 2.2rem; margin-bottom: 0.5rem; }
    header p { font-size: 1.1rem; color: #e2e8f0; }
    nav { background-color: var(--secondary); padding: 0.8rem; text-align: center; }
    nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
    nav a:hover { text-decoration: underline; }
    .container { max-width: 1000px; margin: 2rem auto; padding: 0 1rem; }
    .card-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.5rem; margin-top: 1.5rem; }
    .card { background: white; padding: 1.5rem; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.08); }
    .card h3 { color: var(--primary); margin-bottom: 0.5rem; }
    .hero { background: white; padding: 2.5rem 1.5rem; border-radius: 8px; text-align: center; margin-bottom: 2rem; box-shadow: 0 4px 6px rgba(0,0,0,0.05); }
    .hero h2 { color: var(--primary); margin-bottom: 1rem; }
    .btn { display: inline-block; background-color: var(--accent); color: white; padding: 0.75rem 1.5rem; text-decoration: none; border-radius: 5px; font-weight: bold; margin-top: 1rem; }
    footer { background-color: var(--primary); color: white; text-align: center; padding: 1.5rem; margin-top: 3rem; }
  </style>
</head>
<body>

  <header>
    <h1>MECV PARIS</h1>
    <p>Mission Évangélique la Clé de la Victoire</p>
  </header>

  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#horaires">Nos Cultes</a>
    <a href="#contact">Contact & Accès</a>
  </nav>

  <div class="container">
    <section id="accueil" class="hero">
      <h2>Bienvenue à l'Église MECV Paris</h2>
      <p>Un lieu d'adoration, de fraternité et d'édification spirituelle. Soyez les bienvenus !</p>
    </section>

    <section id="horaires">
      <h2 style="color: var(--primary); text-align: center;">Horaires de nos Réunions</h2>
      <div class="card-grid">
        <div class="card">
          <h3>Dimanche</h3>
          <p><strong>Culte Dominical</strong></p>
          <p>14h00 – 17h00</p>
        </div>
        <div class="card">
          <h3>Lundi</h3>
          <p><strong>Temps de Prière</strong></p>
          <p>19h00 – 19h45</p>
        </div>
        <div class="card">
          <h3>Jeudi</h3>
          <p><strong>Étude & Prière</strong></p>
          <p>21h00 – 22h00</p>
        </div>
      </div>
    </section>

    <section id="contact" style="margin-top: 3rem;">
      <h2 style="color: var(--primary); text-align: center;">Contact & Localisation</h2>
      <div class="card" style="margin-top: 1.5rem; text-align: center;">
        <p><strong>Adresse :</strong> 63 Av. du Maréchal Lyautey, 78300 Poissy</p>
        <p style="margin-top: 0.5rem;"><strong>Téléphone :</strong> 07 58 40 40 38</p>
        <a href="tel:0758404038" class="btn">Appeler l'église</a>
      </div>
    </section>
  </div>

  <footer>
    <p>&copy; 2026 MECV PARIS - Tous droits réservés.</p>
  </footer>

</body>
</html>
