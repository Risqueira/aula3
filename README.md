# aula3
#listas
```html
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Listas</title>
</head>

<body>
    <h1>Tipos de listas</h1>

    <ul type="square">
        <li>Java</li>
        <li>HTML</li>
        <li>CSS</li>
        <li>Java Script</li>
    </ul>
    <h2>Disiciplinas</h2>
    <ol>
        <li>portugues</li>
        <li>Matematica</li>
        <li>historia</li>
        <li>geografia</li>
        <li>ed.fisica</li>
    </ol>

</body>

</html>
```
#caixas id
```html
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Listas</title>
    <Style>
        #cx1 {
            border: 1px solid black;
            margin-top: 10px;
            padding: 20px;
            background-color: red;
            color: white;
            width: 200px;
            height: 100px;
        }
        #cx2 {
            border: 1px solid black;
            margin: 10px 10px 10px 500px;
            padding: 20px;
            background-color: blue;
            color: white;
            width: 200px;
            height: 100px;
        }
    </Style>

</head>

<body>

    <div id="cx1">
        <h1>caixa 1</h1>
    </div>

    <div id="cx2">
        <h1>caixa 2</h1>
    </div>

</body>

</html>
```
```html
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Listas</title>
    <Style>
        #cabecalho {
            width: 100vw;
            height: 30vh;
            border: 2px solid black;
        }

        #corpo {
            width: 100vw;
            height: 60vh;
            border: 2px solid black;
        }

        #rodape {
            width: 100%;
            height: 30%;
            border: 2px solid black;
        }
    </Style>mkl

</head>

<body>

    <div id="cabecalho">Titulo</div>

    <div id="corpo">corpinho
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa commodi cumque vel harum quasi porro voluptates
        saepe voluptas neque accusamus? Doloribus quo sunt hic illo voluptatum sit ut labore repellendus. Aliquam
        distinctio at maiores odit sunt sapiente, pariatur ullam veniam vero repudiandae nulla mollitia nihil ut unde
        corrupti quaerat vitae assumenda, magni cupiditate ipsa quibusdam et iusto fuga illo. Corrupti ratione
        recusandae similique ullam maxime fuga. Provident expedita, aperiam similique, deleniti labore assumenda quidem
        nulla commodi error, quos amet doloribus sequi? Laudantium, reprehenderit facere, animi esse tempora quibusdam
        voluptates, numquam sit necessitatibus obcaecati soluta. Odio modi molestiae cum atque ducimus.
    </div>

    <div id="rodape">rodape</div>


</body>

</html>
```

# curriculo html
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina modelo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="./pedra.jpg" alt="foto de perfil">
        <h2>site modelo</h2>
        <nav>
            <a href="pagina.html">home</a>
            <a href="#sobre">sobre</a>
            <a href="#projeto">projeto</a>
            <a href="#contato">contato</a>
        </nav>
    </header>

    <main>

    </main>
    <footer>

    </footer>
</body>
</html>
```
# curriculo css
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: blue;
    height: 100px;

}

header img {
    border-radius: 50%;
    width: 80px;
}

header h2 {
    color: white;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 16pt;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-radius: 20% 20% 0 0;
}

nav a {
    color: white;
    margin-left: 10px;
    text-decoration: none;
    background-color: blueviolet;
    padding: 8px;
    border-radius: 30% 30% 0 0;
}

nav a:hover {
    color: yellow;
    margin-left: 10px;
    text-decoration: none;
    background-color: red;
    padding: 8px;
    border-radius: 30% 30% 0 0;

}
```
