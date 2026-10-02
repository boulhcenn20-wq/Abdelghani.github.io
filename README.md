<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="La Villa — Pâtisserie & Viennoiserie. Créations artisanales, gourmandes et élégantes.">
  <meta name="theme-color" content="#f7f1e5">
  <title>LA VILLA — Pâtisserie & Viennoiserie</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600;700&family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:ital,wght@500;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="announcement">Créations artisanales · Commandes sur réservation · Livraison locale</div>

  <header class="site-header" id="top">
    <a class="brand" href="#top" aria-label="La Villa accueil">
      <span class="brand-mark">V</span>
      <span>
        <strong>LA VILLA</strong>
        <small>PÂTISSERIE · VIENNOISERIE</small>
      </span>
    </a>

    <nav class="desktop-nav" aria-label="Navigation principale">
      <a href="#histoire">Notre histoire</a>
      <a href="#creations">Créations</a>
      <a href="#savoir-faire">Savoir-faire</a>
      <a href="#contact">Contact</a>
    </nav>

    <a class="nav-cta" href="#contact">Commander <span>↗</span></a>
    <button class="menu-btn" aria-label="Ouvrir le menu" aria-expanded="false">
      <span></span><span></span><span></span>
    </button>
  </header>

  <div class="mobile-menu">
    <a href="#histoire">Notre histoire</a>
    <a href="#creations">Créations</a>
    <a href="#savoir-faire">Savoir-faire</a>
    <a href="#contact">Contact</a>
  </div>

  <main>
    <section class="hero">
      <div class="hero-copy reveal">
        <p class="eyebrow"><span></span> Maison artisanale · depuis 2018</p>
        <h1>Le goût du<br><em>beau</em> et du bon.</h1>
        <p class="hero-text">Une pâtisserie contemporaine où les gestes traditionnels rencontrent une esthétique délicate. Des créations pensées pour faire durer le plaisir.</p>
        <div class="hero-actions">
          <a class="btn btn-dark" href="#creations">Découvrir nos créations <span>→</span></a>
          <a class="text-link" href="#histoire">Notre histoire <span>↗</span></a>
        </div>
        <div class="hero-note">
          <span class="seal">✦</span>
          <span>Fait avec passion<br><b>chaque matin</b></span>
        </div>
      </div>

      <div class="hero-visual reveal">
        <div class="hero-image"></div>
        <div class="floating-card">
          <span>01</span>
          <div>
            <b>La signature</b>
            <small>Créations de saison</small>
          </div>
          <i>↗</i>
        </div>
        <div class="round-stamp">ARTISAN<br>BOULANGER<br><span>✦</span></div>
      </div>
    </section>

    <section class="marquee" aria-label="Spécialités">
      <div>
        <span>PÂTISSERIE</span><i>✦</i><span>VIENNOISERIE</span><i>✦</i>
        <span>CHOCOLAT</span><i>✦</i><span>GOURMANDISE</span><i>✦</i>
        <span>PÂTISSERIE</span><i>✦</i><span>VIENNOISERIE</span><i>✦</i>
      </div>
    </section>

    <section class="story section" id="histoire">
      <div class="section-label reveal">01 — Notre histoire</div>
      <div class="story-grid">
        <div class="story-title reveal">
          <p class="eyebrow">Une maison de passion</p>
          <h2>Simplement<br><em>exceptionnel.</em></h2>
        </div>
        <div class="story-text reveal">
          <p>La Villa est née d'une envie simple : créer des pâtisseries généreuses, élégantes et profondément gourmandes.</p>
          <p>Chaque jour, notre équipe travaille des matières premières choisies avec soin pour donner vie à des textures, des parfums et des souvenirs.</p>
          <a class="text-link" href="#savoir-faire">Découvrir notre savoir-faire <span>↗</span></a>
        </div>
      </div>
    </section>

    <section class="creations section" id="creations">
      <div class="section-top reveal">
        <div>
          <div class="section-label">02 — Nos créations</div>
          <h2>Les incontournables<br><em>de La Villa.</em></h2>
        </div>
        <p>Une sélection évolutive inspirée par les saisons, la tradition et la créativité.</p>
      </div>

      <div class="product-grid">
        <article class="product-card reveal">
          <div class="product-image img-1"><span>Signature</span></div>
          <div class="product-meta"><div><h3>Le Parisien</h3><p>Chocolat · noisette · praliné</p></div><b>01</b></div>
        </article>
        <article class="product-card reveal">
          <div class="product-image img-2"><span>Nouveau</span></div>
          <div class="product-meta"><div><h3>Fleur de Vanille</h3><p>Vanille · fruits rouges · crème</p></div><b>02</b></div>
        </article>
        <article class="product-card reveal">
          <div class="product-image img-3"><span>Classique</span></div>
          <div class="product-meta"><div><h3>Le Croissant</h3><p>Beurre AOP · pâte feuilletée</p></div><b>03</b></div>
        </article>
      </div>

      <div class="center-action reveal">
        <a class="btn btn-outline" href="#contact">Voir toute la carte <span>→</span></a>
      </div>
    </section>

    <section class="manifesto" id="savoir-faire">
      <div class="manifesto-image"></div>
      <div class="manifesto-copy reveal">
        <div class="section-label">03 — Notre savoir-faire</div>
        <h2>Le temps est<br><em>notre ingrédient.</em></h2>
        <p>Fermentation lente, cuissons précises, finitions minutieuses : nous privilégions les gestes qui donnent du caractère.</p>
        <div class="stats">
          <div><strong>100%</strong><span>fait maison</span></div>
          <div><strong>7j/7</strong><span>passion & précision</span></div>
          <div><strong>01</strong><span>maison indépendante</span></div>
        </div>
      </div>
    </section>

    <section class="quote section">
      <span class="quote-mark">“</span>
      <blockquote>Une bonne pâtisserie ne se regarde pas seulement.<br><em>Elle se partage.</em></blockquote>
      <p>— La Villa</p>
    </section>

    <section class="contact section" id="contact">
      <div class="contact-box reveal">
        <div>
          <div class="section-label">04 — Parlons gourmandise</div>
          <h2>Une envie ?<br><em>Écrivez-nous.</em></h2>
          <p>Commandes, événements, gâteaux personnalisés ou simple question : notre équipe vous répond avec plaisir.</p>
        </div>
        <div class="contact-details">
          <a href="tel:+212600000000"><span>Téléphone</span> +212 6 00 00 00 00 ↗</a>
          <a href="mailto:bonjour@lavilla.ma"><span>Email</span> bonjour@lavilla.ma ↗</a>
          <a href="#" aria-label="Instagram"><span>Instagram</span> @lavilla.patisserie ↗</a>
          <a href="#" aria-label="Adresse"><span>Adresse</span> Votre adresse · Maroc ↗</a>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="footer-brand">LA VILLA<span>®</span></div>
    <div>© <span id="year"></span> La Villa. Tous droits réservés.</div>
    <a href="#top">Retour en haut ↑</a>
  </footer>

  <script src="script.js"></script>
</body>
</html>
