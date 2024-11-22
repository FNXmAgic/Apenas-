<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Show Nacional - Rio Negro e Solimões</title>
    <style>
        /* Estilos para o cabeçalho */
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        /* Estilos para o menu de navegação */
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        /* Estilos para o banner */
        .banner img {
            width: 100%;
            height: auto;
            padding-top: 20px;
            /* Margem superior */
        }

        /* Estilos para o contêiner de vídeos */
        .videos-container {
            display: flex;
            justify-content: space-between;
            gap: 10px;
            /* Espaçamento entre os vídeos */
            flex-wrap: wrap;
            /* Ajuste para telas menores */
        }

        .videos-container iframe {
            flex: 1;
            min-width: 50%;
            /* Ajusta a largura mínima para cada vídeo */
        }

        /* Estilo para a seção de sobre */
        #sobre {
            text-align: center;
            margin: 20px 0;
        }

        /* Estilo para a seção de sobre */
        #artistas {
            text-align: center;
            margin: 20px 0;
        }

        /* Estilo para a seção de contato */
        #contato {
            text-align: center;
            margin: 20px 0;
        }

        /* Estilo para a seção de galeria */
        #galeria {
            text-align: center;
            margin: 20px 0;
        }

        #galeria h2 {
            margin-bottom: 15px;
            font-size: 24px;
            color: #333;
        }

        /* Contêiner da galeria com grade */
        .galeria-container {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            /* 4 imagens por linha */
            gap: 20px;
            /* Espaço entre as imagens */
            max-width: 1200px;
            /* Limite de largura da galeria */
            margin: 0 auto;
            /* Centralizar a galeria */
        }

        /* Estilos para as imagens */
        .galeria-container img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }

        /* Efeito de zoom ao passar o mouse */
        .galeria-container img:hover {
            transform: scale(1.05);
        }

        /* Estilos para o rodapé */
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }

        /* Estilos para as redes sociais no rodapé */
        .redes-sociais {
            display: flex;
            justify-content: center;
            gap: 15px;
            /* Espaço entre os ícones */
            margin-top: 10px;
        }

        .redes-sociais a img {
            width: 30px;
            /* Tamanho dos ícones */
            filter: brightness(1) invert(0);
            /* Para combinar com o fundo escuro */
        }

        .redes-sociais a:hover img {
            filter: brightness(0.5);
            /* Clareia o ícone ao passar o mouse */
        }
    </style>
</head>

<body>
    <!-- Cabeçalho da página -->
    <header>
        <h1>Show Nacional - Rio Negro e Solimões</h1>
        <p>Venha prestigiar a abertura do Natal Luz na Praça da Paz, em Piên</p>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre o Show</a></li>
                <li><a href="#artistas">Artistas</a></li>
                <li><a href="#ingressos">Ingressos</a></li>
                <li><a href="#galeria">Galeria</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>

        <!-- Banner -->
        <div class="banner">
            <img src="img3.jpg" alt="Foto de Rio Negro e Solimões" width="300">
        </div>

    </header>

    <!-- Seção Sobre o Show -->
    <section id="sobre">
        <h2>Sobre o Show</h2>
        <p>A entrada é gratuita! Venha celebrar com a gente o início do Natal Luz de Piên, um evento que promete
            encantar toda a família. A grande abertura ficará por conta do show da famosa dupla Rio Negro e Solimões,
            que trará muita música e emoção para todos os presentes. Este será um momento mágico para marcar o começo da
            temporada natalina em nossa cidade, reunindo pessoas de todas as idades em um ambiente de festa e alegria.
        </p>
        <p>O evento acontecerá no dia <strong>22 de novembro de 2024</strong>, na Praça da Paz, em Piên - PR, e é uma excelente
            oportunidade para reunir a família e amigos em uma noite inesquecível. A celebração estará repleta de boas
            energias, e esperamos contar com a presença de todos para tornar essa noite ainda mais especial. Não deixe
            de participar dessa linda festa de abertura do Natal Luz, repleta de música, tradição e magia!</p>

    </section>

    <!-- Seção Artistas -->
    <section id="artistas">
        <h2>Artistas Confirmados</h2>
        <ul>
            <li><strong>Rio Negro e Solimões</strong> - A dupla sertaneja que conquistou o Brasil com seus sucessos!
            </li>
            <li><strong>Euller e Eduardo</strong> - A dupla sensação de Pìên!</li>
        </ul>

        <!-- Vídeo do YouTube -->
        <div class="artista-video">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/CWk7e39jPFs"
                title="Rio Negro e Solimões - Vídeo do YouTube" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen></iframe>

            <iframe width="560" height="315" src="https://www.youtube.com/embed/umirlRu3n1E"
                title="Euller e Eduardo - Vídeo do YouTube" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen></iframe>
        </div>
    </section>

    <!-- Seção Galeria -->
    <section id="galeria">
        <h2>Galeria</h2>
        <p>Veja momentos de shows anteriores e o espírito do Natal Luz em Piên.</p>
        <div class="galeria-imagens">
            <img src="img1.jpg" alt="Imagem 1 da Feira da Lua">
            <img src="img2.jpg" alt="Imagem 2 da Feira da Lua">
            <img src="img4.jpg" alt="Imagem 4 da Feira da Lua">
            <img src="img5.jpg" alt="Imagem 5 do Banner">
            <img src="img6.jpg" alt="Imagem 6 da Feira da Lua">
            <img src="img7.jpg" alt="Imagem 7 da Feira da Lua">
            <img src="img8.jpg" alt="Imagem 8 da Feira da Lua">
            <img src="img9.jpg" alt="Imagem 9 da Feira da Lua">
            <!-- Adicione mais imagens conforme necessário -->
        </div>
    </section>

    <!-- Seção de Contato -->
    <section id="contato">
        <h2>Contato</h2>
        <p>Para mais informações, entre em contato conosco:</p>
        <p><strong>Email:</strong> contato@natalpien.com</p>
        <p><strong>Telefone:</strong> (41) 98765-4321</p>
    </section>

    <!-- Rodapé da página -->
    <footer>

        <!-- Redes sociais -->
        <div class="redes-sociais">
            <a href="https://www.instagram.com/seu_perfil" target="_blank">
                <img src="instagram-icon.png" alt="Instagram" width="30">
            </a>
            <a href="https://www.facebook.com/seu_perfil" target="_blank">
                <img src="facebook-icon.png" alt="Facebook" width="30">
            </a>
            <a href="https://wa.me/seu_numero" target="_blank">
                <img src="whatsapp-icon.png" alt="WhatsApp" width="30">
            </a>
        </div>

        <p>&copy; Professor Lourenço. Todos os direitos reservados.</p>
    </footer>
</body>

</html>