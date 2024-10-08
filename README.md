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

@@ -9,7 +15,7 @@

    <section>
        <div class="chamada-texto">
            <h1>ATRAVÉS DO ARANHAVERSO SUPERA O PRIMEIRO FILME?</h1>
            <h1>ATRAVÉS DO ARANHAVERSO</h1>
            <p>#homem-aranha</p>
        </div>

‎styles.css
+14
-5
Original file line number	Diff line number	Diff line change
@@ -2,6 +2,7 @@ body {
    color: white;
    background: black;
    margin: 0px;
    font-family: "Chakra Petch", sans-serif;
}

header {
@@ -12,13 +13,21 @@ header {
}

section {
	background: rgb(184,156,213);
	padding-bottom: 80px;
	padding-top: 80px;
	display: flex;
	justify-content: center;
    background: rgb(184, 156, 213);
    padding-bottom: 80px;
    padding-top: 80px;
    display: flex;
    justify-content: center;
}

.chamada-texto {
    margin-right: 5%;
}
h1 {
    font-size: 40px;
}
p {
    font-size: 20px;
}
