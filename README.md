# EXERCICIO
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Landing page para divulgação de produto">
    <title>Produto X - Inovação para o seu dia a dia</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="hero">
        <nav>
            <a href="#home" class="logo">ProdutoX</a>
            <ul>
                <li><a href="#features">Funcionalidades</a></li>
                <li><a href="#pricing">Preços</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
        <div class="hero-content">
            <h1>Inovação para seu cotidiano</h1>
            <p>Conheça o Produto X, a solução perfeita para melhorar sua produtividade e bem-estar.</p>
            <a href="#features" class="btn">Saiba Mais</a>
        </div>
    </header>

    <section id="features" class="features">
        <h2>Funcionalidades</h2>
        <div class="feature-list">
            <div class="feature-item">
                <h3>Funcionalidade 1</h3>
                <p>Detalhes sobre a primeira funcionalidade do produto.</p>
            </div>
            <div class="feature-item">
                <h3>Funcionalidade 2</h3>
                <p>Detalhes sobre a segunda funcionalidade do produto.</p>
            </div>
        </div>
    </section>

    <section id="pricing" class="pricing">
        <h2>Planos e Preços</h2>
        <div class="pricing-table">
            <div class="pricing-item">
                <h3>Plano Básico</h3>
                <p>R$ 29,90/mês</p>
                <a href="#" class="btn">Assine agora</a>
            </div>
            <div class="pricing-item">
                <h3>Plano Premium</h3>
                <p>R$ 59,90/mês</p>
                <a href="#" class="btn">Assine agora</a>
            </div>
        </div>
    </section>

    <footer id="contact">
        <h2>Contato</h2>
        <form>
            <input type="text" placeholder="Nome" required>
            <input type="email" placeholder="E-mail" required>
            <textarea placeholder="Mensagem" required></textarea>
            <button type="submit" class="btn">Enviar</button>
        </form>
    </footer>
</body>
</html>
