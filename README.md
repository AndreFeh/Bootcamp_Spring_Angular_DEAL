<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Movies For Me</title>
    <link rel="stylesheet" href="styles/main.css">
    <script src="src/main.js" defer></script>
    <script src="src/CardDestaque.js" defer></script>
</head>
<body>
    <!-- NAV BAR = Barra do Topo -->
    <nav class="navbar">
        <ul>
            <li><a class="page-selec" href= "index.html">HOME</a></li>
            <li><a href="page1.html">PAGE 1</a></li>
            <li><a href="page2.html">PAGE 2</a></li>
        </ul>
    </nav>

    <!-- Conteúdo Principal -->
    <main class="content">
        <div class="layout-left">
            <p>Hello</p>
        </div>
        <div class="layout-center">
            <h1>PAGINA PRINCIPAL</h1>
            <P>Hello World</P>
                <div class="destaque">
                    <card-destaque
                    dtq-img="assets/another.jpg"
                    dtq-alt="Another"
                    nome="Another"
                    categoria="Suspence"
                    link-anime="page2.html"
                    ></card-destaque>
                    
                    <card-destaque
                    dtq-img="assets\Dragon Ball Z Dokkan Battle.jpg"
                    dtq-alt="Dragon Ball Z Dokkan Battle"
                    nome="Dragon Ball Z"
                    categoria="Shounen"
                    ></card-destaque>
        
                    <card-destaque
                    dtq-img="assets\guilty crown.jpg"
                    dtq-alt="Guilty Crown"
                    nome="Guilty Crown"
                    categoria="Ação"
                    ></card-destaque>
        
                    <card-destaque
                    dtq-img="assets\naruto shippuden.png"
                    dtq-alt="Naruto Shippuden"
                    nome="Naruto Shippuden"
                    categoria="Shounen, Ação, Ninja"
                    ></card-destaque>
        
                    <card-destaque
                    dtq-img="assets\pokemon.jpg"
                    dtq-alt="Pokémon"
                    nome="Pokémon"
                    categoria="Aventura"
                    ></card-destaque>
        
                    <card-destaque
                    dtq-img="assets\tokyo ghoul.jpg"
                    dtq-alt="Tokyo Ghoul"
                    nome="Tokyo Ghoul"
                    categoria="Suspence, Sci-Fy"
                    ></card-destaque>
        
                </div>

        </div>
        <div class="layout-right">
            <p>Hello</p>
        </div>
    
    </main>
    
    <!--FOOTER Barra de Baixo-->
    <footer class="footer">
        <p>FOOTER</p>
    </footer>
</body>
</html>