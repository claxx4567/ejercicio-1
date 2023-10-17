# Ejercicio1.html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">
  <!--CSS-->
    <title>Título de la página</title>
</head>
  <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
  <!--JS-->
<body>
<div class="container">
  <div class="row">
    <div class="col">
      First in DOM, no order applied
      <img src="https://previews.123rf.com/images/bahtiarmaulana/bahtiarmaulana2204/bahtiarmaulana220400040/185159316-rebanada-de-dibujos-animados-de-pizza-ilustraci%C3%B3n-de-dibujos-animados-vectoriales-im%C3%A1genes.jpg" class="img-thumbnail" alt="...">
    </div>
    <div class="col order-12">
      Second in DOM, with a larger order
      <img src="https://previews.123rf.com/images/bahtiarmaulana/bahtiarmaulana2204/bahtiarmaulana220400040/185159316-rebanada-de-dibujos-animados-de-pizza-ilustraci%C3%B3n-de-dibujos-animados-vectoriales-im%C3%A1genes.jpg" class="img-thumbnail" alt="...">
    </div>
    <div class="col order-1">
      Third in DOM, with an order of 1
      <img src="https://previews.123rf.com/images/bahtiarmaulana/bahtiarmaulana2204/bahtiarmaulana220400040/185159316-rebanada-de-dibujos-animados-de-pizza-ilustraci%C3%B3n-de-dibujos-animados-vectoriales-im%C3%A1genes.jpg" class="img-thumbnail" alt="...">
    </div>
  </div>
</div>
</body>
</html>
