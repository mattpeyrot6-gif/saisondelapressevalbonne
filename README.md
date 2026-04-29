# saisondelapressevalbonne
Commerce familial situé à Valbonne Village, alliant presse, librairie, papeterie, confiseries et souvenirs. Ce site met en valeur une boutique de proximité chaleureuse, proposant des produits variés et de qualité au cœur du village.
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Presse & Librairie - Boutique Locale</title>
  <style>
    body { font-family: 'Segoe UI', sans-serif; margin: 0; background: #fafafa; }
    header { background: #1e2a38; color: white; padding: 30px; text-align: center; }
    nav { background: #2c3e50; padding: 15px; text-align: center; }
    nav a { color: white; margin: 0 20px; text-decoration: none; font-weight: 600; }
    nav a:hover { color: #f1c40f; }
    section { padding: 50px 20px; max-width: 1100px; margin: auto; }
    h2 { text-align: center; margin-bottom: 30px; }
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 25px; }
    .card { background: white; border-radius: 15px; overflow: hidden; box-shadow: 0 5px 15px rgba(0,0,0,0.08); transition: transform 0.3s; }
    .card:hover { transform: translateY(-5px); }
    .card img { width: 100%; height: 180px; object-fit: cover; }
    .card-content { padding: 20px; }
    .btn { display: inline-block; margin-top: 10px; padding: 10px 15px; background: #1e2a38; color: white; border-radius: 5px; text-decoration: none; }
    footer { background: #1e2a38; color: white; text-align: center; padding: 20px; }
  </style>
</head>
<body>

<header>
  <h1>Presse • Papeterie • Librairie</h1>
  <p>Votre commerce de proximité</p>
</header>

<nav>
  <a href="#librairie">Librairie</a>
  <a href="#confiseries">Confiseries</a>
  <a href="#souvenirs">Souvenirs & Cadeaux</a>
  <a href="#papeterie">Papeterie</a>
</nav>

<section id="librairie">
  <h2>Librairie</h2>
  <div class="grid">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1512820790803-83ca734da794" alt="Livres">
      <div class="card-content">
        <h3>Romans & Best-sellers</h3>
        <p>Découvrez les dernières nouveautés et grands classiques.</p>
      </div>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1524995997946-a1c2e315a42f" alt="Livres enfants">
      <div class="card-content">
        <h3>Livres jeunesse</h3>
        <p>Pour petits et grands lecteurs.</p>
      </div>
    </div>
  </div>
</section>

<section id="confiseries">
  <h2>Confiseries</h2>
  <div class="grid">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1587049352851-8d4e89133924" alt="Bonbons">
      <div class="card-content">
        <h3>Bonbons & douceurs</h3>
        <p>Une sélection gourmande pour tous les goûts.</p>
      </div>
    </div>
  </div>
</section>

<section id="souvenirs">
  <h2>Souvenirs & Cadeaux</h2>
  <div class="grid">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1607082349566-187342175e2f" alt="Souvenirs">
      <div class="card-content">
        <h3>Objets souvenirs</h3>
        <p>Ramenez un souvenir unique de votre visite.</p>
      </div>
    </div>
  </div>
</section>

<section id="papeterie">
  <h2>Papeterie</h2>
  <div class="grid">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1519681393784-d120267933ba" alt="Papeterie">
      <div class="card-content">
        <h3>Fournitures & carnets</h3>
        <p>Tout pour écrire, créer et organiser.</p>
      </div>
    </div>
  </div>
</section>

<section>
  <h2>Contact</h2>
  <p style="text-align:center;">📍 Votre ville<br>📞 01 23 45 67 89<br>✉️ contact@boutique.fr</p>
</section>

<footer>
  <p>&copy; 2026 Votre Commerce Local</p>
</footer>

</body>
</html>
