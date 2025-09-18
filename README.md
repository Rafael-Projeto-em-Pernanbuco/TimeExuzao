
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>TimãoExuzão</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Estilo CSS -->
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #c8facc; /* Verde claro */
            color: blue; /* Cor das letras */
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #006400; /* Verde escuro */
            padding: 20px;
            text-align: center;
            color: red;
        }

        h1 {
            margin: 0;
        }

        nav {
            background-color: red;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: blue;
            margin: 0 10px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 20px;
        }

        footer {
            background-color: #006400;
            color: white;
            text-align: center;
            padding: 10px;
        }

        .social-icons a {
            margin: 0 10px;
            font-size: 24px;
            color: blue;
            text-decoration: none;
        }

        iframe {
            width: 100%;
            border: 0;
            margin-top: 20px;
        }

        .email-form {
            margin-top: 20px;
            background-color: #f8d7da;
            padding: 15px;
            border-radius: 5px;
        }

        .email-form input[type="email"] {
            padding: 10px;
            width: 80%;
            margin-right: 10px;
        }

        .email-form input[type="submit"] {
            padding: 10px;
            background-color: #006400;
            color: white;
            border: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>TimãoExuzão</h1>
        <p>Bem-vindo ao site oficial!</p>
    </header>

    <nav>
        <a href="#">Início</a>
        <a href="#">Sobre</a>
        <a href="#">Contato</a>
    </nav>

    <section>
        <h2>Nos encontre no mapa</h2>
        <!-- Google Maps Embed -->
        <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3656.209953807206!2d-46.6565721850204!3d-23.589703384663717!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce59c93c9b0e91%3A0x602b22f2fc705f0c!2sArena%20Corinthians!5e0!3m2!1spt-BR!2sbr!4v1695063945982"
            height="300"
            allowfullscreen=""
            loading="lazy">
        </iframe>

        <h2>Traduzir esta página</h2>
        <!-- Google Tradutor -->
        <div id="google_translate_element"></div>

        <script type="text/javascript">
            function googleTranslateElementInit() {
                new google.translate.TranslateElement({pageLanguage: 'pt', layout: google.translate.TranslateElement.InlineLayout.SIMPLE}, 'google_translate_element');
            }
        </script>
        <script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

        <h2>Atendimento Online</h2>
        <!-- Simulação de Chat -->
        <iframe src="https://www.tawk.to/chat/your_chat_id/1gptid98k" height="300"></iframe>

        <h2>Nos siga nas redes sociais</h2>
        <div class="social-icons">
            <a href="https://wa.me/seunumerodetelefone" target="_blank">Whatsapp</a> |
            <a href="https://www.instagram.com/" target="_blank">Instagram</a> |
            <a href="https://www.facebook.com/" target="_blank">Facebook</a> |
            <a href="https://www.kwai.com/" target="_blank">Kwai</a> |
            <a href="https://twitter.com/" target="_blank">Twitter</a> |
            <a href="https://t.me/" target="_blank">Telegram</a> |
            <a href="https://www.tiktok.com/" target="_blank">TikTok</a>
        </div>

        <h2>Cadastre seu e-mail</h2>
        <form class="email-form" action="#" method="post">
            <input type="email" name="email" placeholder="Digite seu e-mail" required>
            <input type="submit" value="Cadastrar">
        </form>
    </section>

    <footer>
        <p>&copy; 2025 TimãoExuzão. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
