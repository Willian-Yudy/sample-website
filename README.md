<!DOCTYPE html>
<html lang="en-US">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Chá na Casa do Tea</title>
    <link rel="stylesheet" href="styles.css"> <!-- Certifique-se de criar um arquivo CSS separado para estilos -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #f8f8f8;
            padding: 10px 0;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo img {
            height: 50px;
        }
        nav {
            flex-grow: 1;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .search-bar {
            display: flex;
            align-items: center;
        }
        .search-bar input {
            padding: 5px;
            font-size: 16px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .icons {
            display: flex;
            align-items: center;
        }
        .icons a {
            text-decoration: none;
            color: #333;
            margin-left: 15px;
            font-size: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <a href="#"><img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fpt.vecteezy.com%2Farte-vetorial%2F370242-logotipo-da-folha-verde-do-cha-ecologia-natureza-elemento-vetoriais-icone-simbolo-caligrafia-bio-bio-vegano-mao-ilustracoes-desenhadas&psig=AOvVaw2jubWwUM6sbHDx_RJ5YFBA&ust=1719535576844000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCIjGpa7H-oYDFQAAAAAdAAAAABAE" alt="Logo da Loja de Chá"></a> <!-- Certifique-se de ter uma imagem de logotipo -->
            </div>
            <nav>
                <ul>
                    <li><a href="#">Início</a></li>
                    <li><a href="#">Sobre Nós</a></li>
                    <li><a href="#">Loja</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">Contato</a></li>
                </ul>
            </nav>
            <div class="search-bar">
                <input type="text" placeholder="Buscar chás...">
            </div>
            <div class="icons">
                <a href="#"><i class="fas fa-user"></i></a> <!-- Ícone de login -->
                <a href="#"><i class="fas fa-shopping-cart"></i></a> <!-- Ícone de carrinho de compras -->
            </div>
        </div>
    </header>

    <!-- Certifique-se de incluir o Font Awesome para ícones -->
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</body>
</html>
