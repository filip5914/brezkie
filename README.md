<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sklep Sportowy</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background-color: #fff;
      color: #111;
    }

    header {
      background-color: #000;
      color: #fff;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 24px;
      letter-spacing: 2px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 20px;
      font-weight: bold;
    }

    .hero {
      background: url('https://static.nike.com/a/images/f_auto/dpr_1.0,cs_srgb/w_1440,c_limit/bd0e0306-5639-4f9a-91ae-62d3f4f01453/nike-just-do-it.jpg') center/cover no-repeat;
      height: 80vh;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
      text-align: center;
    }

    .hero h2 {
      font-size: 48px;
    }

    .products {
      padding: 60px 40px;
    }

    .products h3 {
      font-size: 28px;
      margin-bottom: 20px;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .product {
      border: 1px solid #ddd;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      transition: 0.3s;
    }

    .product:hover {
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
    }

    .product img {
      max-width: 100%;
      border-radius: 5px;
    }

    .product h4 {
      margin-top: 10px;
      font-size: 18px;
    }

    .product p {
      color: #555;
    }

    footer {
      background-color: #111;
      color: #aaa;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>SportShop</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Produkty</a>
      <a href="#">Kontakt</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Nowa Kolekcja Butów Sportowych</h2>
  </section>

  <section class="products">
    <h3>Nasze Bestsellery</h3>
    <div class="product-grid">
      <div class="product">
        <img src="https://static.nike.com/a/images/t_prod_ss/w_960,c_limit,f_auto/d7c0c0e1-dffa-4872-aec6-560d5a2d0f3f/air-max-90.jpg" alt="Nike Air Max 90" />
        <h4>Nike Air Max 90</h4>
        <p>499,00 zł</p>
      </div>
      <div class="product">
        <img src="https://static.nike.com/a/images/t_prod_ss/w_960,c_limit,f_auto/518c39d3-cfa5-4c02-88a0-6529b8126baf/air-force-1.jpg" alt="Nike Air Force 1" />
        <h4>Nike Air Force 1</h4>
        <p>449,00 zł</p>
      </div>
      <div class="product">
        <img src="https://static.nike.com/a/images/t_prod_ss/w_960,c_limit,f_auto/34df3e92-76e5-49ab-a6c7-f16264796c8f/pegasus-40.jpg" alt="Nike Pegasus 40" />
        <h4>Nike Pegasus 40</h4>
        <p>599,00 zł</p>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 SportShop. Wszelkie prawa zastrzeżone.
  </footer>

</body>
</html>
