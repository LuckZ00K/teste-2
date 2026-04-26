<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>COMPREJÁ - Loja de Roupas</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
    }

    header {
      background: #000;
      color: #fff;
      padding: 15px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 32px;
      letter-spacing: 2px;
    }

    nav {
      background: #222;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #ff4d4d;
    }

    .banner {
      background: url('https://via.placeholder.com/1200x400') no-repeat center;
      background-size: cover;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 28px;
      font-weight: bold;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .product {
      background: white;
      padding: 15px;
      text-align: center;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .product img {
      width: 100%;
      border-radius: 10px;
    }

    .product h3 {
      margin: 10px 0 5px;
    }

    .product p {
      color: #555;
    }

    .product button {
      background: #ff4d4d;
      border: none;
      padding: 10px;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }

    .product button:hover {
      background: #cc0000;
    }

    footer {
      background: #000;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>COMPREJÁ</h1>
  <p>Sua loja de roupas online</p>
</header>

<nav>
  <a href="#">Início</a>
  <a href="#">Masculino</a>
  <a href="#">Feminino</a>
  <a href="#">Promoções</a>
  <a href="#">Contato</a>
</nav>

<div class="banner">
  Novas Coleções Chegaram!
</div>

<section class="products">
  <div class="product">
    <img src="https://via.placeholder.com/200" alt="Produto">
    <h3>Camiseta Estilosa</h3>
    <p>R$ 59,90</p>
    <button>Comprar</button>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/200" alt="Produto">
    <h3>Jaqueta Moderna</h3>
    <p>R$ 129,90</p>
    <button>Comprar</button>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/200" alt="Produto">
    <h3>Calça Jeans</h3>
    <p>R$ 99,90</p>
    <button>Comprar</button>
  </div>
</section>

<footer>
  <p>© 2026 COMPREJÁ - Todos os direitos reservados</p>
</footer>

</body>
</html>
