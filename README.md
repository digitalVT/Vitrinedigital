<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Vitrine - Super Loja Online</title>
    <style>
        /* Estilos Globais */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #FFFFFF;
            color: #333333;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        .produto {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin: 20px;
            padding: 20px;
            display: inline-block;
            width: 250px;
            vertical-align: top;
        }
        .produto img {
            max-width: 100%;
            border-radius: 5px;
            height: 200px;
            object-fit: cover;
        }
        .btn-comprar {
            background: #4CAF50;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
            text-decoration: none;
            display: inline-block;
        }
        .secao-principal {
            display: flex;
            gap: 20px;
            margin-bottom: 30px;
        }
        .banner-vertical {
            width: 200px;
            background: linear-gradient(to bottom, #4CAF50, #81C784);
            color: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .banner-vertical img {
            width: 100%;
            border-radius: 5px;
        }
        h2 {
            text-align: center;
            margin: 30px 0;
        }
        @media (max-width: 768px) {
            .produto {
                width: 100%;
                margin: 10px 0;
            }
            .secao-principal {
                flex-direction: column;
            }
            .banner-vertical {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>🛍️ Digital Vitrine</h1>
    </header>

    <div class="container">
        <div class="secao-principal">
            <!-- Banner Vertical -->
            <div class="banner-vertical">
                <img src="img/banner-promocional.jpg" alt="ofertas por tempo limitado">
                <h3>Moda feminina!</h3>
                <p> até 50% OFF em itens selecionados</p>
            </div>

            <!-- Produtos -->
            <div id="produtos">
                <div class="produto">
                    <img src="img/vestido.jpg" alt="Vestido de Malha">
                    <h3>Vestido de Malha</h3>
                    <p>R$ 51,91</p>
                    <a href="https://s.click.aliexpress.com/e/_mNxgVEx" target="_blank" class="btn-comprar">Comprar</a>
                </div>
                
                <div class="produto">
                    <img src="img/vermelho.jpg" alt="Vestido Longo">
                    <h3>Vestido Longo</h3>
                    <p>R$ 69,90</p>
                    <a href="https://a.aliexpress.com/_msK7Bm3" target="_blank" class="btn-comprar">Comprar</a>
                </div>
            </div>
        </div>

        <h2>Produtos em Destaque</h2>
        
        <!-- Produto 1 -->
        <div class="produto">
            <img src="img/Porsche gt1.jpg" alt="Porsche GT1 RC">
            <h3>1:24 RC Porsche</h3>
            <p>R$ 66,54</p>
            <a href="https://s.click.aliexpress.com/e/_mOdX4c7" class="btn-comprar" target="_blank">Comprar no AliExpress</a>
        </div>

        <!-- Produto 2 -->
        <div class="produto">
            <img src="img/culiman.jpg" alt="Rolls Royce Cullinan">
            <h3>Rolls Royce Cullinan</h3>
            <p>R$ 44,09</p>
            <a href="https://s.click.aliexpress.com/e/_ms0yaC3" class="btn-comprar" target="_blank">Comprar no AliExpress</a>
        </div>

        <!-- Produto 3 -->
        <div class="produto">
            <img src="img/Mustang GT 500.jpg" alt="Mustang GT 500">
            <h3>1:32 Mustang GT 500</h3>
            <p>R$ 35,99</p>
            <a href="https://s.click.aliexpress.com/e/_msgb2VV" class="btn-comprar" target="_blank">Comprar no AliExpress</a>
        </div>

        <!-- Produto 4 -->
        <div class="produto">
            <img src="img/Phantom.jpg" alt="Rolls Royce Phantom">
            <h3>Rolls Royce Phantom</h3>
            <p>R$ 76,99</p>
            <a href="https://s.click.aliexpress.com/e/_ms0yaC3" class="btn-comprar" target="_blank">Comprar no AliExpress</a>
        </div>
    </div>
</body>
</html>
