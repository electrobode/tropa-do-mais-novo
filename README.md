# tropa-do-mais-novo
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Melhores Momentos do Corinthians</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Melhores Momentos do Corinthians</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Início</a></li>
                <li><a href="#momentos">Momentos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="inicio">
        <h2>Bem-vindo!</h2>
        <p>Confira os melhores momentos da história do Corinthians.</p>
    </section>
    
    <section id="momentos">
        <h2>Seleção de Melhores Momentos</h2>
        <div class="momentos-container">
            <article>
                <h3>Título do Momento 1</h3>
                <img src="imagem1.jpg" alt="Descrição do Momento 1">
                <p>Descrição detalhada do momento 1.</p>
            </article>
            <article>
                <h3>Título do Momento 2</h3>
                <img src="imagem2.jpg" alt="Descrição do Momento 2">
                <p>Descrição detalhada do momento 2.</p>
            </article>
            <article>
                <h3>Título do Momento 3</h3>
                <img src="imagem3.jpg" alt="Descrição do Momento 3">
                <p>Descrição detalhada do momento 3.</p>
            </article>
        </div>
    </section>
    
    <section id="contato">
        <h2>Contato</h2>
        <p>Entre em contato para mais informações.</p>
        <form>
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" rows="4" required></textarea>
            
            <button type="submit">Enviar</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2024 Melhores Momentos do Corinthians. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

header {
    background: #000;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 2rem;
}

.momentos-container {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
}

article {
    background: #fff;
    padding: 1rem;
    border: 1px solid #ddd;
    border-radius: 8px;
    flex: 1 1 calc(33.333% - 2rem);
}

article img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin: 0.5rem 0 0.25rem;
}

form input,
form textarea {
    padding: 0.5rem;
    margin-bottom: 1rem;
    border: 1px solid #ddd;
    border-radius: 4px;
}

form button {
    padding: 0.5rem;
    background: #333;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

form button:hover {
    background: #555;
}

footer {
    background: #000;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
}
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Melhores Momentos do Corinthians</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Melhores Momentos do Corinthians</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Início</a></li>
                <li><a href="#momentos">Momentos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="inicio">
        <h2>Bem-vindo!</h2>
        <p>Confira os melhores momentos da história do Corinthians.</p>
    </section>
    
    <section id="momentos">
        <h2>Seleção de Melhores Momentos</h2>
        <div class="momentos-container">
            <article>
                <h3>Campeonato Paulista 2017 - Final</h3>
                <img src="https://example.com/imagem1.jpg" alt="Corinthians campeão Paulista 2017">
                <p>O Corinthians venceu o Campeonato Paulista de 2017 com uma grande atuação na final contra a Ponte Preta.</p>
            </article>
            <article>
                <h3>Libertadores 2012 - Final</h3>
                <img src="https://example.com/imagem2.jpg" alt="Corinthians campeão da Libertadores 2012">
                <p>A vitória do Corinthians na final da Copa Libertadores de 2012 foi histórica, garantindo o primeiro título da competição para o clube.</p>
            </article>
            <article>
                <h3>Mundial de Clubes 2000 - Final</h3>
                <img src="https://example.com/imagem3.jpg" alt="Corinthians campeão do Mundial de Clubes 2000">
                <p>O Corinthians conquistou o Mundial de Clubes em 2000, vencendo o Vasco na final e garantindo o título mundial.</p>
            </article>
        </div>
    </section>
    
    <section id="contato">
        <h2>Contato</h2>
        <p>Entre em contato para mais informações.</p>
        <form>
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" rows="4" required></textarea>
            
            <button type="submit">Enviar</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2024 Melhores Momentos do Corinthians. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
