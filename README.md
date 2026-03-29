# madhuricheetiAppscpriteassi

<!DOCTYPE html>
<html>
<head>
  <title>PLP Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header class="header">
  <h2>My Store</h2>
</header>

<div class="container">

  <!-- Sidebar -->
  <aside class="sidebar">
    <h3>Filters</h3>
    <p>Category</p>
    <button onclick="filterCategory('electronics')">Electronics</button>
    <button onclick="filterCategory('jewelery')">Jewelry</button>
    <button onclick="getProducts()">All</button>
  </aside>

  <!-- Products -->
  <main class="products" id="products"></main>

</div>

<script src="script.js"></script>
</body>
</html>
