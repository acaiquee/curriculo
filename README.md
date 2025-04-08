# Apresentação Pessoal
Apresentação pessoal - André Caíque 


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>André Caíque - Portfólio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background: linear-gradient(90deg, #0078d7, #f9f9f9);
            color: #fff;
            text-align: center;
            padding: 2rem 1rem;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.2rem;
        }

        nav {
            background: #005bb5;
            padding: 0.5rem 1rem;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
        }

        nav ul li {
            margin: 0 1rem;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #f4f4f9;
        }

        section {
            padding: 1.5rem;
            margin: 1rem auto;
            max8wid8h: 800px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #0078d7;
            margin-bottom: 1rem;
            text-align: center;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            margin-bottom: 0.5rem;
        }
.highlight {
    font-weight: bold;
    color: #0078d7;
}

        a {
            color: #0078d7;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
footer {
            text-align: center;
            padding: 1rem 0;
            background: #0078d7;
            color: #fff;
            margin-top: 2rem;
        }
        .btn {
            display: inline-block;
            padding: 0.8rem 1.5rem;
            background: #0078d7;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 1rem;
            transition: background 0.3s ease;
        }

        .btn:hover {
            background: #005bb5;
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background: #0078d7;
            color: #fff;
            margin-top: 2rem;
        }

        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }

            nav ul li {
                margin: 0.5rem 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div style="display: flex; align-items: center; justify-content: center; gap: 1rem;">
            <img src="perfil.jpg" alt="Foto de Perfil" style="width: 100px; height: 100px; border-radius: 50%; object-fit: cover;">
            <div>
                <h1>André Caíque Leite Silva</h1>
                <p> Gestor de Negócios | Estudante de Analise e Desenvolvimento de Sistemas </p>
            </div>
        </div>
    </header>
    <nav>
        <ul>
            <li><a href="#contato">Contato</a></li>
            <li><a href="#resumo">Resumo</a></li>
            <li><a href="#experiencia">Experiência</a></li>
            <li><a href="#projetos">Projetos</a></li>
            <li><a href="#habilidades">Habilidades</a></li>
        </ul>
    </nav>
    <section id="contato">
        <h2>Contato</h2>
        <p><span class="highlight">Email:</span> <a href="mailto:andrecaiquels@gmail.com">andrecaiquels@gmail.com</a></p>
        <p><span class="highlight">WhatsApp:</span> <a href="https://wa.me/5583981783286" target="_blank">(83) 9 8178-3286</a></p>
        <p><span class="highlight">Localização:</span> Manaíra, João Pessoa</p>
    </section>
    <section id="resumo">
        <h2>Resumo Profissional</h2>
        <p>Profissional com experiência em gestão de negócios, marketing e desenvolvimento. Apaixonado por tecnologia e inovação, buscando oportunidades para crescimento contínuo.</p>
        <a href="curriculo.pdf" class="btn" download>Baixar Currículo</a>
    </section>
    <section id="experiencia">
        <h2>Experiência Profissional</h2>
        <ul>
            <li><span class="highlight">Manaçaí Delivery</span> - Gerente de Loja | Nov 2024 - Fev 2025</li>
            <li><span class="highlight">Manga Rosa Arte Bar</span> - Gerente | Abr 2021 - Nov 2023</li>
            <li><span class="highlight">Bar 54</span> - Gerente | Jun 2017 - Jan 2019</li>
        </ul>
    </section>
    <section id="projetos">
        <h2>Projetos e Certificações</h2>
        <ul>
            <li><span class="highlight">Entec - Escritório de negócios </span> - </li>
            <li><span class="highlight">Certificação sistema Linx-Menew</span> - Criada no Figma e implementada com HTML/CSS</li>
            <li><span class="highlight">Aplicativo de Controle Financeiro</span> - Desenvolvido em C</li>
        </ul>
    </section>
    <section id="habilidades">
        <h2>Habilidades</h2>
        <ul>
            <li>Banco de Dados | MySQL</li>
            <li>Programação | Python, C</li>
            <li>UX/UI | Figma, Bubble</li>
            <li>Marketing Digital | Estratégias de Venda</li>
            <li>Gestão Financeira | Fluxo de Caixa</li>
        </ul>
    </section>
    <footer>
        <p>&copy; 2025 André Caíque. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
