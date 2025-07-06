# affiliate-site<!DOCTYPE html><html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>موقع منتجات أفلييت</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
      direction: rtl;
    }
    header {
      background-color: #0077cc;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .product {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      width: 300px;
      margin: 15px;
      padding: 15px;
      text-align: center;
    }
    .product img {
      width: 100%;
      border-radius: 10px;
    }
    .product h3 {
      color: #333;
    }
    .product p {
      color: #555;
    }
    .buy-button {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background-color: #28a745;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s;
    }
    .buy-button:hover {
      background-color: #218838;
    }
  </style>
</head>
<body>
  <header>
    <h1>تسوق أفضل المنتجات معنا!</h1>
  </header>  <div class="container">
    <div class="product">
      <img src="https://via.placeholder.com/300x200" alt="منتج 1">
      <h3>اسم المنتج 1</h3>
      <p>وصف قصير للمنتج الأول.</p>
      <a class="buy-button" href="https://example.com/product1" target="_blank">اشتري الآن</a>
    </div><div class="product">
  <img src="https://via.placeholder.com/300x200" alt="منتج 2">
  <h3>اسم المنتج 2</h3>
  <p>وصف قصير للمنتج الثاني.</p>
  <a class="buy-button" href="https://example.com/product2" target="_blank">اشتري الآن</a>
</div>

<div class="product">
  <img src="https://via.placeholder.com/300x200" alt="منتج 3">
  <h3>اسم المنتج 3</h3>
  <p>وصف قصير للمنتج الثالث.</p>
  <a class="buy-button" href="https://example.com/product3" target="_blank">اشتري الآن</a>
</div>

  </div>
</body>
</html>
