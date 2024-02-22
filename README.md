<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Equipe Alura Start</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
</head>
body {
    font-family: 'Poppins', sans-serif;
}
<section class="escola">
        <div class="escola-div-conteudo">
            <h2 class="escola-titulo">Sobre a Escola</h2>
            <p class="escola-texto-um">A Escola Alura foi fundada em 2010 e tem como objetivo ensinar Pensamento Computacional, através do ensino de  Programação.</p>
            <p class="escola-texto-dois">A turma mais estudiosa e famosa é a Segunda Série A. Nós somos super unidos e a turma favorita por todos os professores e professoras que nos ajudam!</p>
        </div>
        <img class="escola-imagem" src="Formula-bro.png" alt="Professora no quadro">
    </section>
    <section class="estudante">
        
    </section>
<section class=”estudante”>
    <h2 class=”estudante-titulo”>Quem são nossos estudantes</h2>
</section>
<section class=”estudantes”>
    <h2 class=”estudante-titulo”>Quem são nossos estudantes</h2>
    <img class=”estudante-imagem” src=”Marcelo.jpeg” alt=”foto do marcelo”>
</section>
<section class=”estudantes”>
    <h2 class=”estudante-titulo”>Quem são nossos estudantes</h2>
    <img class=”estudante-imagem” src=”Marcelo.jpeg” alt=”foto do marcelo”>
    <h3 class=”estudante-nome”>Marcelo</h3>
</section>
.estudante-imagem{
    width: 120px;
}
<section class="estudante">
        <h2 class="estudante-titulo">Quem são nossos estudantes?</h2>
        <img class="estudante-imagem" src="Marcelo.jpeg" alt="foto do marcelo">
        <h3 class="estudante-nome">Marcelo</h3>
        <img class="estudante-icone" src="github.png" alt="icone github">
        <img class="estudante-icone" src="linkedin.png" alt="icone linkedin">
        <img class="estudante-icone" src="instagram.png" alt="icone instagram">
</section>
.estudante-div{
    text-align: center;
    padding: 16px 0;
}
<section class="estudante">
    <h2 class="estudante-titulo">Quem são nossos estudantes?</h2>
    <div class="estudante-div">
        <img class="estudante-imagem" src="Marcelo.jpeg" alt="foto do marcelo">
        <h3 class="estudante-nome">Marcelo</h3>
        <img class="estudante-icone" src="github.png" alt="icone github">
        <img class="estudante-icone" src="linkedin.png" alt="icone linkedin">
        <img class="estudante-icone" src="instagram.png" alt="icone instagram">
    </div>
    <div class="estudante-div">
        <img class="estudante-imagem" src="Marcelo.jpeg" alt="foto do marcelo">
        <h3 class="estudante-nome">Marcelo</h3>
        <img class="estudante-icone" src="github.png" alt="icone github">
        <img class="estudante-icone" src="linkedin.png" alt="icone linkedin">
        <img class="estudante-icone" src="instagram.png" alt="icone instagram">
    </div>
</section>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Equipe Alura Start</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
</head>

<body>
    <header class="cabecalho">
        <img class="cabecalho-imagem" src="alurastart logo.png" alt="logo da alura start">
        <ul class="cabecalho-lista">
            <li class="cabecalho-lista-item">Escola</li>
            <li class="cabecalho-lista-item">Estudante</li>
        </ul>
    </header>
    <section class="escola">
        <div class="escola-div-conteudo">
            <h2 class="escola-titulo">Sobre a Escola</h2>
            <p class="escola-texto-um">A Escola Alura foi fundada em 2010 e tem como objetivo ensinar Pensamento
                Computacional, através do ensino de Programação.</p>
            <p class="escola-texto-dois">A turma mais estudiosa e famosa é a Segunda Série A. Nós somos super unidos e a
                turma favorita por todos os professores e professoras que nos ajudam!</p>
        </div>
        <img class="escola-imagem" src="Formula-bro.png" alt="imagem que representa uma professora em sala de aula">
    </section>
    <section class="estudante">
        <h2 class="estudante-titulo">Quem são nossos estudantes?</h2>
        <div class="estudante-div">
            <img class="estudante-imagem" src="Marcelo.jpeg" alt="foto do marcelo">
            <h3 class="estudante-nome">Marcelo</h3>
            <img class="estudante-icone" src="github.png" alt="icone github">
            <img class="estudante-icone" src="linkedin.png" alt="icone linkedin">
            <img class="estudante-icone" src="instagram.png" alt="icone instagram">
        </div>
        <div class="estudante-div">
            <img class="estudante-imagem" src="Marcelo.jpeg" alt="foto do marcelo">
            <h3 class="estudante-nome">Marcelo</h3>
            <img class="estudante-icone" src="github.png" alt="icone github">
            <img class="estudante-icone" src="linkedin.png" alt="icone linkedin">
            <img class="estudante-icone" src="instagram.png" alt="icone instagram">
        </div>
    </section>
</body>

</html>
*{
    margin: 0;
    padding: 0;
}
body {
    font-family: 'Poppins', sans-serif;
}
.cabecalho {
    background-color: #424E61;
    color: white;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 24px 0;
}

.cabecalho-imagem{
    width: 10%;
}

.cabecalho-lista-item{
    display: inline-block;
    margin: 0 16px;
    font-size: 16px;
}

.escola-imagem{
    width: 25%;
}

.escola{
    background-image: linear-gradient(#424E61,#16CFF8);
    color:white;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 24px 0;
}

.escola-div-conteudo{
    width: 35%;
}


.escola-titulo{
    padding: 24px 0;
}

.estudante{
    padding: 24px 0;
}
.estudante-imagem{
    width: 120px;
}

.estudante-icone{
    width: 24px;
    padding: 4px 8px;
}

.estudante-div{
    text-align: center;
    padding: 16px 0;
}
