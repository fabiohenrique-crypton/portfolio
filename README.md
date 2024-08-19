<!DOCTYPE html>
<html lang="pt-BR">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>FH TECH - Portfólio</title>
        <style>
            * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #1e1e1e;
    color: #ffffff;
    line-height: hidden;
    overflow: hidden;
}
header {
    background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
    color: #ffffff;
    padding: 20px 0;
    text-align: center;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.3);
}
header h1 {
    font-size: 2.5rem;
    text-transform: uppercase;
    letter-spacing: 3px;
    animation: fadeInDown 1s ease-out;
}
nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding-top: 10px;
}
nav ul li {
    margin: 0 20px;
}
nav ul li a {
    color: #ffffff;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease;
}
nav ul li a:hover {
    color: #ffe259;
}
section {
    padding: 40px;
    margin: 30px auto;
    max-width: 900px;
    background-color: #2a2a2a;
    border-radius: 10px;
    box-shadow: 0px 4px 8px rgba(0,0,0, 0.2);
    transform: translateY(20px);
    animation: slideIn 1s ease-out;
}
section h2 {
    font-size: 2rem;
    border-bottom: 2px solid #6a11cb;
    padding-bottom: 10px;
    margin-bottom: 20px;
    text-transform: uppercase;
}
.projeto {
    margin-bottom: 30px;
    padding: 20px;
    border-radius: 10px;
    background: #333333;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.habilidade {
    margin-bottom: 30px;
    padding: 20px;
    border-radius: 10px;
    background: #333333;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.projeto:hover {
    transform: translateY(-10px);
    box-shadow: 0px 10px 15px rgba(0, 0, 0, 0.4);
}
.habilidade:hover {
    transform: translateY(-10px);
    box-shadow: 0px 10px 15px rgba(0, 0, 0, 0.4);
}
footer {
    text-align: center;
    padding: 15px;
    background-color: #6a11cb;
    color: #ffffff;
    margin-top: 30px;
}
footer p {
    margin: 0;
}
a {
    color: #ffe259;
    text-decoration: none;
    transition: color 0.3s ease;
}
a:hover {
    color: #ffffff;
    text-decoration: underline;
}
@keyframes fadeInDown {
    0% {
        opacity: 0;
        transform: translateY(-20px)
    }
    100% {
        opacity: 1;
        transform: translateY(0);
    }
}
@keyframes slideIn {
    0% {
        opacity: 0;
        transform: translateY(50px);
    }
}
@media (max-width: 768px) {
    header h1 {
        font-size: 2rem;
    }
    section {
        padding: 20px;
        margin: 20px auto;
    }
    nav ul {
        flex-direction: column;
    }
    nav ul li {
        margin: 10px 0;
    }
}
        </style>
    </head>
    <body>
        <header>
            <h1>FH TECH</h1>
        </header>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#projeto">Projetos</a></li>
                <li><a href="#habilidades">Habilidades</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
        <section id="sobre">
            <h2>Sobre Mim</h2>
            <p>Sou um estudante de Gestão de Tecnologia da Informação apaixonado por desenvolvimento e infraestrutura de TI. Busco constantemente me aprimorar e aplicar meus conhecimentos em projetos práticos.</p>
        </section>
        <section id="projeto">
            <h2>projetos</h2>
            <div class="projeto">
                <h3>Projeto 1: HOPE ENERGY</h3>
                <img src="" alt="logo hope">
                <p>desenvolvimento de um site com HTML e CSS, para a empresa HOPE ENERGY. Com um design simples, prático e padronizado.</p>
            </div>
        </section>
        <section id="habilidades">
            <h2>Habilidades</h2>
            <ul>
                <li>Desenvolvimento Web (HTML e CSS)</li>
                <li>Gerenciamento de Redes e infraestrutura</li>
                <li>Metodologias ágeis - Scrum </li>
                <li>Logica de Programação (python)</li>
                <li>Banco de Dados (MySQL Workbench)</li>
            </ul>
        </section>
        <section id="contato">
            <h2>Contato</h2>
            <p>E-mail: <a href="">fabio.henriqueal@outlook.com</a></p>
            <p>Linkedin: <a href="" target="_blank">Fabio Henrique</a></p>
        </section>
        <footer>
            <p>&copy; 2024 FH TECH. Todos os direitos reservados.</p>
        </footer>
    </body>
</html>
