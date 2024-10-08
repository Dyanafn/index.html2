<html lang="pt-BR">

<head>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap"
        rel="stylesheet">
    <title>Aluraflix</title>
</head>

<body>
    <header>ALURAFLIX</header>

    <section>
    <section class="chamada">
        <div class="chamada-texto">
            <h1>ATRAVÉS DO ARANHAVERSO</h1>
            <p>#homem-aranha</p>
@@ -27,6 +27,27 @@
        </div>
    </section>

    <section class="categoria">
        <h2>Filmes e séries</h2>
        <div class="categoria-videos">
            <a href="https://www.youtube.com/watch?v=cs15QqG6Gjc">
                <img src="https://img.youtube.com/vi/cs15QqG6Gjc/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=nCmIwcycUJ8">
                <img src="https://img.youtube.com/vi/nCmIwcycUJ8/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=FvRmEapoHRc">
                <img src="https://img.youtube.com/vi/FvRmEapoHRc/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=Ipkw_hWW-Hw">
                <img src="https://img.youtube.com/vi/Ipkw_hWW-Hw/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=d4DzMNGoyis">
                <img src="https://img.youtube.com/vi/d4DzMNGoyis/maxresdefault.jpg" />
            </a>
        </div>
    </section>
</body>

</html>
‎styles.css
+16
-1
Original file line number	Diff line number	Diff line change
@@ -12,7 +12,7 @@ header {
    color: rgb(42, 122, 228);
}

section {
.chamada {
    background: rgb(184, 156, 213);
    padding-bottom: 80px;
    padding-top: 80px;
@@ -30,4 +30,19 @@ h1 {

p {
    font-size: 20px;
}
img {
    height: 200px;
}
.categoria-videos {
    display: flex;
    overflow-x: auto;
    gap: 10px;
}
.categoria {
    padding-left: 20px;
    padding-right: 20px;
}
