# produtox-landing
git init
git add .
git commit -m "Landing page ProdutoX"
git branch -M main
git push -u origin main

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Produto X - Revolucione sua experiência</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: #f5f6fa;
            color: #333;
        }

        header {
            background: white;
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.08);
            position: sticky;
            top: 0;
            z-index: 10;
        }

        header h1 {
            font-size: 24px;
            font-weight: bold;
            color: #2b2d42;
        }

        nav a {
            margin-left: 25px;
            text-decoration: none;
            font-weight: bold;
            color: #333;
        }

        /* HERO */
        .hero {
            height: 85vh;
            background: linear-gradient(to right, #4158d0, #c850c0, #ffcc70);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 0 20px;
        }

        .hero h2 {
            font-size: 52px;
            max-width: 900px;
        }

        .hero p {
            font-size: 20px;
            margin-top: 15px;
            max-width: 700px;
        }

        .btn-primary {
            margin-top: 25px;
            padding: 15px 30px;
            background: #222;
            color: white;
            font-size: 18px;
            border-radius: 8px;
            text-decoration: none;
            transition: 0.3s;
        }

        .btn-primary:hover {
            background: #000;
        }

        /* SEÇÃO RECURSOS */
        .section {
            padding: 80px 40px;
            text-align: center;
        }

        .section h3 {
            font-size: 34px;
            margin-bottom: 40px;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 40px;
            max-width: 1100px;
            margin: auto;
        }

        .feature-box {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        .feature-box h4 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        /* SEÇÃO DEPOIMENTOS */
        .testimonials {
            background: #fff;
            padding: 80px 40px;
        }

        .testimonials-grid {
            max-width: 900px;
            margin: auto;
            display: grid;
            gap: 30px;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
        }

        .testimonial {
            background: #f1f1f1;
            padding: 25px;
            border-radius: 10px;
            font-style: italic;
        }

        /* FORMULÁRIO */
        .form-box {
            max-width: 600px;
            margin: 50px auto;
            background: white;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.1);
        }

        input, textarea {
            width: 100%;
            padding: 14px;
            margin-top: 10px;
            border-radius: 6px;
            border: 1px solid #ccc;
            font-size: 16px;
        }

        button {
            margin-top: 20px;
            width: 100%;
            padding: 15px;
            font-size: 18px;
            background: #4158d0;
            color: white;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #3140a8;
        }

        footer {
            background: #222;
            padding: 30px;
            margin-top: 60px;
            color: white;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Produto X</h1>
        <nav>
            <a href="#features">Recursos</a>
            <a href="#depoimentos">Depoimentos</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Transforme sua experiência com o inovador Produto X</h2>
        <p>Alta performance, tecnologia avançada e a solução perfeita que sua empresa estava esperando.</p>
        <a href="#contato" class="btn-primary">Quero saber mais</a>
    </section>

    <section class="section" id="features">
        <h3>Por que escolher o Produto X?</h3>
        <div class="features">
            <div class="feature-box">
                <h4>✔ Alta Performance</h4>
                <p>Desenvolvido para entregar velocidade e eficiência.</p>
            </div>

            <div class="feature-box">
                <h4>✔ Fácil Integração</h4>
                <p>Conecta-se facilmente a qualquer sistema.</p>
            </div>

            <div class="feature-box">
                <h4>✔ Suporte Premium</h4>
                <p>Acompanhamento completo antes e depois da compra.</p>
            </div>
        </div>
    </section>

    <section class="testimonials" id="depoimentos">
        <h3>O que nossos clientes dizem</h3>
        <div class="testimonials-grid">
            <div class="testimonial">“Depois que adotamos o Produto X, nossa produtividade aumentou 80%!” — João</div>
            <div class="testimonial">“Simplesmente perfeito. Rápido, moderno e fácil de usar.” — Camila</div>
            <div class="testimonial">“Recomendo para qualquer empresa que busca inovação.” — Rafael</div>
        </div>
    </section>

    <section class="section" id="contato">
        <h3>Entre em Contato</h3>
        <div class="form-box">
            <input type="text" placeholder="Seu nome" />
            <input type="email" placeholder="Seu e-mail" />
            <textarea rows="4" placeholder="Digite sua mensagem"></textarea>
            <button>Enviar Mensagem</button>
        </div>
    </section>

    <footer>
        © 2025 Produto X — Todos os direitos reservados
    </footer>
</body>
</html>
