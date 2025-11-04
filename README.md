<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pink Tentacion Tienda</title>
  <style>
    :root {
      --main-color: #ff69b4;
      --accent-color: #111;
      --bg-color: #fff;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
    body { text-align: center; background: var(--bg-color); color: var(--accent-color); padding: 20px; }
    img.logo { width: 120px; border-radius: 50%; margin-bottom: 15px; }
    h1 { font-size: 1.8rem; margin-bottom: 8px; }
    p.tagline { color: #555; margin-bottom: 25px; font-size: 1rem; }
    .button {
      display: block;
      text-decoration: none;
      color: #fff;
      background: var(--main-color);
      padding: 14px;
      margin: 10px auto;
      width: 85%;
      border-radius: 8px;
      font-weight: 600;
      transition: 0.3s;
      cursor: pointer;
    }
    .button:hover { background: #e60084; }
    .category { display: none; margin-top: 20px; }
    .product { margin: 20px 0; }
    .product img { width: 85%; max-width: 350px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
    .product a { display: block; margin-top: 8px; color: var(--main-color); font-weight: 600; text-decoration: none; }
    .product a:hover { text-decoration: underline; }
    .socials a { margin: 10px; text-decoration: none; color: var(--accent-color); font-size: 1.6rem; }
    .socials a:hover { color: var(--main-color); }
    footer { font-size: 0.85rem; color: #777; margin-top: 30px; }
  </style>
</head>
<body>

  <img src="https://i.imgur.com/sltCN5x.png" alt="Pink Tentacion Tienda Logo" class="logo">
  <h1>Pink Tentacion Tienda</h1>
  <p class="tagline"> ropa de mujer ✦  lencería ✦  juguetes para parejas </p>

  <!-- Category Buttons -->
  <div>
    <div class="button" onclick="showCategory('streetwear')">👗 ropa de mujer </div>
    <div class="button" onclick="showCategory('lingerie')">💖 lencería </div>
    <div class="button" onclick="showCategory('toys')">💋  juguetes para parejas </div>
    <a href="mailto:" target="_blank" class="button">📩 Contacto</a>
  </div>

  <!-- Categories -->
  <div id="streetwear" class="category">
    <h2> ropa de mujer </h2>
    <div class="product">
      <img src="https://i.imgur.com/D3AKcXj.jpeg" alt="Streetwear 1">
      <a href="https://www.instagram.com/pinktentaciontienda?igsh=azE5djllamZzcGs4&utm_source=qr" target="_blank">DM to Purchase</a>
    </div>
    <div class="product">
      <img src="https://www.vecteezy.com/photo/52005680-elegant-blue-lingerie-set-displayed-on-white-background"alt="Streetwear 2">
      <a href="https://www.instagram.com/pinktentaciontienda?igsh=azE5djllamZzcGs4&utm_source=qr" target="_blank">DM to Purchase</a>
    </div>
  </div>

  <div id="lingerie" class="category">
    <h2> lencería </h2>
    <div class="product">
      <img src="https://i.imgur.com/E8GEghW.jpeg" alt="Lingerie 1">
      <a href="https://www.instagram.com/pinktentaciontienda?igsh=azE5djllamZzcGs4&utm_source=qr" target="_blank">DM to Purchase</a>
    </div>
    <div class="product">
      <img src="https://i.imgur.com/aRgxXzS.jpeg" alt="Lingerie 2">
      <a href="https://www.instagram.com/pinktentaciontienda?igsh=azE5djllamZzcGs4&utm_source=qr" target="_blank">DM to Purchase</a>
    </div>
  </div>

  <div id="toys" class="category">
    <h2> juguetes para parejas </h2>
    <div class="product">
      <img src="https://i.imgur.com/y6ZzWkl.jpeg" alt="Toy 1">
      <a href="https://www.instagram.com/pinktentaciontienda?igsh=azE5djllamZzcGs4&utm_source=qr" target="_blank">DM to Purchase</a>
    </div>
    <div class="product">
      <img src="https://i.imgur.com/KH3nZCq.jpeg" alt="Toy 2">
      <a href="https://www.instagram.com/pinktentaciontienda?igsh=azE5djllamZzcGs4&utm_source=qr" target="_blank">DM to Purchase</a>
    </div>
  </div>

  <!-- Socials -->
  <div class="socials">
    <a href="https://www.instagram.com/pinktentaciontienda?igsh=azE5djllamZzcGs4&utm_source=qr" target="_blank">📸 Instagram</a>
  </div>

  <footer>© 2025 Pink Tentacion Tienda. Discreet Shipping • Worldwide.</footer>

  <script>
    function showCategory(categoryId) {
      const categories = document.querySelectorAll('.category');
      categories.forEach(cat => cat.style.display = 'none');
      document.getElementById(categoryId).style.display = 'block';
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }
  </script>
</body>
</html>
