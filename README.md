<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>YP BRAND — Главная</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f0f0f0;
    }
    header {
      background: #e00;
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 26px;
    }
    .banner {
      background: #111;
      color: white;
      text-align: center;
      padding: 25px;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 20px;
    }
    .product {
      background: white;
      width: 220px;
      padding: 10px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      width: 100%;
      height: 160px;
      object-fit: contain;
      margin-bottom: 10px;
    }
    .product-title {
      font-size: 14px;
      margin-bottom: 6px;
    }
    .product-price {
      font-weight: bold;
      font-size: 16px;
      color: #e00;
    }
    .buy-btn {
      margin-top: 10px;
      padding: 8px 14px;
      background: #e00;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background: #fff;
      padding: 10px 0;
      text-align: center;
      font-size: 12px;
      color: #777;
      position: fixed;
      width: 100%;
      bottom: 0;
      border-top: 1px solid #ddd;
    }
  </style>
</head>
<body>
  <header>YP BRAND</header>

  <div class="banner">
    <h2>Добро пожаловать в YP BRAND</h2>
    <p>Лучшие товары, реальные кнопки и работающий сайт</p>
  </div>

  <div class="products">
    <div class="product">
      <img src="https://jbl.com/on/demandware.static/-/Sites-masterCatalog_Harman/default/dw5e7d37e3/JBL_FLIP6_BL_001_dvHAMaster.png" alt="JBL Flip 6">
      <div class="product-title">Колонка JBL Flip 6</div>
      <div class="product-price">8990 ₽</div>
      <button class="buy-btn">Купить</button>
    </div>
    <div class="product">
      <img src="https://static.amazfit.com/cn/website-front/global/product/gts4-mini/black/1.png" alt="Amazfit GTS 4 Mini">
      <div class="product-title">Умные часы Amazfit GTS 4 Mini</div>
      <div class="product-price">8990 ₽</div>
      <button class="buy-btn">Купить</button>
    </div>
  </div>

  <footer>
    &copy; 2025 YP BRAND. Все права защищены.
  </footer>
</body>
</html>
