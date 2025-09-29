# ecoshop.com
TIENDA ONLINE
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>TrendHunt360 - Tu tienda de tendencias</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f4f4f4; margin: 0; padding: 0; }
    header { background: #222; color: #fff; padding: 20px; text-align: center; }
    .product { background: #fff; margin: 20px; padding: 20px; border-radius: 8px; box-shadow: 0 0 10px #ccc; }
    .product img { max-width: 100%; height: auto; }
    .price { font-size: 1.2em; color: #333; }
    .button { background: #ff9900; color: #fff; padding: 10px 15px; text-decoration: none; border-radius: 5px; display: inline-block; margin-top: 10px; }
  </style>
</head>
<body>

<header>
  <h1>TrendHunt360</h1>
  <p>Descubre productos de Amazon con estilo</p>
</header>

<div class="product">
  <h2>Echo Dot (5ª generación)</h2>
  <img src="https://images-na.ssl-images-amazon.com/images/I/61u48FEs3eL._AC_SL1000_.jpg" alt="Echo Dot">
  <p class="price">Precio Amazon: €59.99</p>
  <p class="price">Tu margen: €65.99 (10% extra)</p>
  <a class="button" href="https://www.amazon.es/dp/B09B8V1LZ3?tag=TU-CODIGO-AFILIADO" target="_blank">Comprar en Amazon</a>
</div>

<script>
  // Ejemplo de cálculo automático del margen
  const basePrice = 59.99;
  const margin = basePrice * 1.10;
  document.querySelectorAll('.price')[1].textContent = `Tu margen: €${margin.toFixed(2)} (10% extra)`;
</script>

</body>
</html>

