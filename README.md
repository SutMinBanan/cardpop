# cardpop
<!DOCTYPE html>
<html lang="da">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>CardPop.dk - Pokémon, Funko Pop & One Piece</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      margin: 0; padding: 0;
      color: #222;
    }
    header {
      background: #ffcb05;
      padding: 15px 20px;
      display: flex;
      align-items: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    header h1 {
      color: #2a75bb;
      margin: 0;
      font-size: 28px;
      letter-spacing: 2px;
    }
    nav {
      background: #2a75bb;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      font-size: 18px;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 15px;
    }
    h2 {
      color: #2a75bb;
      margin-bottom: 15px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .product-card {
      background: white;
      border-radius: 8px;
      padding: 15px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.2s ease;
    }
    .product-card:hover {
      transform: scale(1.05);
    }
    .product-card .placeholder {
      background: #ddd;
      height: 180px;
      border-radius: 5px;
      margin-bottom: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #999;
      font-size: 14px;
    }
    .product-card h3 {
      margin: 10px 0 5px;
      color: #333;
    }
    .product-card p {
      color: #555;
      font-size: 14px;
      margin: 0;
    }
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 20px 0;
      margin-top: 40px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <h1>CardPop.dk</h1>
  </header>
  <nav>
    <a href="#pokemon">Pokémon</a>
    <a href="#funkopop">Funko Pop</a>
    <a href="#onepiece">One Piece</a>
    <a href="#kontakt">Kontakt</a>
  </nav>
  <main>
    <section id="pokemon">
      <h2>Pokémon</h2>
      <div class="products">
        <div class="product-card">
          <div class="placeholder">Billede kommer snart</div>
          <h3>Pokémon Kortpakke</h3>
          <p>Den bedste pakke til samleren!</p>
        </div>
        <div class="product-card">
          <div class="placeholder">Billede kommer snart</div>
          <h3>Pokémon Figurer</h3>
          <p>Super fede figurer i høj kvalitet.</p>
        </div>
      </div>
    </section>

    <section id="funkopop" style="margin-top: 40px;">
      <h2>Funko Pop</h2>
      <div class="products">
        <div class="product-card">
          <div class="placeholder">Billede kommer snart</div>
          <h3>Funko Pop - Pikachu</h3>
          <p>Den klassiske Pikachu i Funko-stil.</p>
        </div>
        <div class="product-card">
          <div class="placeholder">Billede kommer snart</div>
          <h3>Funko Pop - Luffy</h3>
          <p>Din yndlings One Piece karakter.</p>
        </div>
      </div>
    </section>

    <section id="onepiece" style="margin-top: 40px;">
      <h2>One Piece</h2>
      <div class="products">
        <div class="product-card">
          <div class="placeholder">Billede kommer snart</div>
          <h3>One Piece Manga Volume 1</h3>
          <p>Start din eventyrrejse her!</p>
        </div>
        <div class="product-card">
          <div class="placeholder">Billede kommer snart</div>
          <h3>One Piece T-shirt</h3>
          <p>Cool design til fans.</p>
        </div>
      </div>
    </section>

    <section id="kontakt" style="margin-top: 40px;">
      <h2>Kontakt</h2>
      <p>Har du spørgsmål? Skriv til os på <a href="mailto:kontakt@cardpop.dk">kontakt@cardpop.dk</a></p>
    </section>
  </main>
  <footer>
    &copy; 2025 CardPop.dk - Alle rettigheder forbeholdes
  </footer>
</body>
</html>
