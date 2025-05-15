# <!DOCTYPE html><html lang="mn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DripSpace Store</title>
  <style>
    body {
      margin: 0;
      font-family: sans-serif;
      background-color: #fff;
      color: #000;
    }
    header {
      background-image: url('cover-sneakers.jpg');
      background-size: cover;
      background-position: center;
      text-align: center;
      padding: 80px 20px 40px;
    }
    header h1 {
      font-size: 48px;
      color: #fff;
      margin: 0;
    }
    header p {
      font-size: 18px;
      margin-top: 10px;
      color: #eee;
    }
    nav {
      display: flex;
      justify-content: space-around;
      padding: 10px;
      background-color: #f0f0f0;
      border-bottom: 1px solid #ccc;
    }
    nav a {
      color: #000;
      text-decoration: none;
      font-weight: bold;
    }
    main {
      padding: 20px;
    }
    .section-title {
      font-size: 22px;
      font-weight: bold;
      margin: 30px 0 10px;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .product {
      border: 1px solid #ccc;
      padding: 10px;
      width: 200px;
      text-align: center;
      border-radius: 10px;
    }
    .product img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 8px;
    }
    .product h3 {
      margin: 10px 0 5px;
    }
    .product .price {
      color: red;
      font-weight: bold;
    }
    .product .old-price {
      text-decoration: line-through;
      color: #888;
    }
    .product button {
      background-color: black;
      color: white;
      border: none;
      padding: 10px;
      width: 100%;
      border-radius: 6px;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #000;
      color: #fff;
      margin-top: 40px;
    }
    .admin-panel {
      padding: 20px;
      background: #f4f4f4;
    }
  </style>
</head>
<body>
  <header>
    <h1>DripSpace Store</h1>
    <p>Yo sneaker fam, welcome to the heat zone! 👟 </p>
  </header>  <nav>
    <a href="#home">Нүүр</a>
    <a href="#categories">Ангилал</a>
    <a href="#sale">Хямдрал</a>
    <a href="#profile">Профайл</a>
  </nav>  <main>
    <div class="section-title">Онцлох бараанууд</div>
    <div class="products">
      <div class="product">
        <img src="decor1.jpg" alt="Зураг 1">
        <h3>Travis scott clock </h3>
        <p class="price">149900₮ <span class="old-price"></span></p>
        <button onclick="alert('Таны данс: 123456789 - Хаан банк')">Захиалах</button>
      </div>
      <div class="product">
        <img src="decor2.jpg" alt="Зураг 2">
        <h3>SB dunk clock</h3>
        <p h3h3class="price">199900₮</p>
        <button onclick="alert('Таны данс: 123456789 - Хаан банк')">Захиалах</button>
      </div>
    </div><div class="section-title">Хямдралтай</div>
<div class="products">
  <div class="product">
    <img src="decor3.jpg" alt="Зураг 3">
    <h3> Air jordan1-12</h3>
    <p class="price">175000₮ <span 
    <button onclick="alert('Таны данс: 123456789 - Хаан банк')">Захиалах</button>
  </div>
</div>

<div class="admin-panel">
  <h2>Админ хэсэг</h2>
  <p>Шинэ бараа нэмэх, зураг солих, үнийг шинэчлэх, хямдрал тохируулах боломжтой.</p>
</div>

  </main>  <footer>
    © 2025 DripSpace Store - Бүх эрх хуулиар хамгаалагдсан.
  </footer>
</body>
</html>
