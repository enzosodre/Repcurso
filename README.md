# Repcurso
Software about petz

Integrantes: Enzo Sodre, Felipe de Macedo, Kaio Oliveira.


<!DOCTYPE html>
<html>
<head>
    <title>Loja de Produtos Pet</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .header {
            padding: 20px;
            text-align: center;
            background: #f7f7f7;
        }
        .topnav {
            overflow: hidden;
            background-color: #333;
        }
        .topnav a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        .topnav a:hover {
            background-color: #ddd;
            color: black;
        }
        .product {
            display: inline-block;
            width: 200px;
            height: 300px;
            padding: 20px;
            margin: 20px;
            background-color: #f2f2f2;
            text-align: center;
        }
    </style>
</head>
<body>

<div class="header">
    <h1>Loja de Produtos Pet</h1>
</div>

<div class="topnav">
    <a href="#">Início</a>
    <a href="#">Produtos</a>
    <a href="#">Contato</a>
</div>

<div class="products">
    <div class="product">
        <h2>Pet Cama</h2>
        <img src="pet_bed.jpg" alt="Pet Cama" style="width:100%;">
        <p>Descrição: Pet Cama com ar de fragrância e lã sintética para o conforto do seu pet.</p>
        <p>Preço: R$ 299,99</p>
    </div>
    <div class="product">
        <h2>Pet Cadeira</h2>
        <img src="pet_chair.jpg" alt="Pet Cadeira" style="width:100%;">
        <p>Descrição: Pet Cadeira com design elegante e durável para o seu pet amar.</p>
        <p>Preço: R$ 199,99</p>
    </div>
    <div class="product">
        <h2>Pet Aréa de Brincadeira</h2>
        <img src="pet_playground.jpg" alt="Pet Aréa de Brincadeira" style="width:100%;">
        <p>Descrição: Pet Aréa de Brincadeira com pista sintética para a diversão e o exercício do seu pet.</p>
        <p>Preço: R$ 499,99</p>
    </div>
</div>

</body>
</html>
