<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>blog pessoal</title>
    <link rel="stylesheet" href="styles.css">
</head>
<style>
/* Resetando margens e padding */
* {
    margin: 0;
    padding: 0;
}


 

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    padding: 20px;
}

header {
    background-color: #50ce54;
    color: white;
    text-align: center;
    padding: 10px 0;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    margin: 20px 0;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #4CAF50;
    color: white;
}

/* Responsividade */
@media (max-width: 768px) {
    nav ul {
        text-align: center;
        padding-top: 10px;
    }
    
    nav ul li {
        display: block;
        margin-bottom: 10px;
    }
}

.button {
  display: inline-block;
  padding: 10px 20px;
  background-color: #071408;
  color: white;
  text-align: center;
  text-decoration: none;
  border-radius: 15px;
  font-size: 16px;
}

.botao:hover {
  background-color: #45a049;
}


</style>




<body>
    <header>
        <h1>Bem-vindo ao Meu Blog</h1>
        <nav>
            <ul>
                <li><a href="#sobre">1 passo</a></li>
                <li><a href="#projetos">2 passo</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>
    <a href="pagina principal.html" class="button">Pagina principal</a>
  
    <section id="sobre">
        <h2>Sobre Mim</h2>
        <p>Olá! Eu sou um estudante de Informática de Gestão...</p>
    </section>

    <section id="projetos">
        <h2>Meus Projetos</h2>
        <p>Aqui estão alguns dos meus projetos:</p>
        <!-- Adicione links ou imagens de seus projetos --> 
    </section>
    <img src="NDIS Plan Meeting guide, Digital downloads.jpeg" alt="">

    <footer>
        <p>Contato: @email.com</p>
    </footer>
   
</body>
</html>
