<!DOCTYPE html>
<html lang="en">
<head>
    <link href="https://fonts.googleapis.com/css2?family=Passero+One&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.css">    
    <link rel="stylesheet" href="style.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="keywords" content="palavras-chave-do-site">
    <meta name="description" content="Descrição do meu site">
    <title>Projeto 1</title>
</head>
<body>
    <header>
        <div class="center">
        <div class="logo left"><span>LogoMarca<span></div>
        <nav class="desktop right">
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">Sobre</a></li>
                <li><a href="">Serviços</a></li>
                <li><a href="">Contato</a></li>
            </ul>
        </nav>

        <nav class="mobile right">
            <div class="botao-menu-mobile">
                <i class="fas fa-bars"></i>
            </div>
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">Sobre</a></li>
                <li><a href="">Serviços</a></li>
                <li><a href="">Contato</a></li>
            </ul>
        </nav>
        <div class="clear"></div>
        </div>
    </header>

    <section class="banner-principal">
        <div class="overlay"></div>
        <div class="center">
        <form>
            <h2>Digite aqui o seu e-mail:</h2>
            <input type="email" name="email" required />
            <input type="submit" name="acao" value="Cadastrar!">
        </form>
        </div>
    </section>

    <section class="descricao-autor">
        <div class="center">
        <div class="w50 left">
        <h2>Átila Henrique</h2>
            <p>O <strong>Átila Henrique</strong> é um texto modelo da indústria tipográfica e de impressão. O Lorem Ipsum tem vindo a ser o texto padrão usado por estas indústrias desde o ano de 1500, quando uma misturou os caracteres de um texto para criar um espécime de livro. Este texto não só sobreviveu 5 séculos, mas também o salto para a tipografia electrónica, mantendo-se essencialmente inalterada. Foi popularizada nos anos 60 com a disponibilização das folhas de Letraset, que continham passagens com Lorem Ipsum, e mais recentemente com os programas de publicação como o Aldus PageMaker que incluem versões do Lorem Ipsum.</p>
            </div>
            <div class="w50 left">
                <img src="213.jpg" alt="imagem Átila" class="right">
            </div>
            <div class="clear"></div>
            </div>
    </section>

    <section class="especialidades">
        <div class="center">
        <h2 class="title">Especialidades</h2>
            <div class="w33 left box-especialidade">
                <h3 class="css"><i class="fab fa-css3"></i></h3>
                <h4>CSS3</h4>
                <p>O Cascading Style Sheets (CSS) é uma "folha de estilo" composta por “camadas” e utilizada para definir a apresentação (aparência) em páginas da internet que adotam para o seu desenvolvimento.</p>
            </div>

            <div class="w33 left box-especialidade">
                <h3 class="html"><i class="fab fa-html5"></i></h3>
                <h4>HTML5</h4>
                <p>O código HTML está presente nas páginas da web há mais de dez anos e tem uma larga aceitação dos usuários por todo o mundo. Com certeza, qualquer pessoa que tem uma ligação um pouco mais estreita. </p>
            </div>

            <div class="w33 left box-especialidade">
                <h3 class="js"><i class="fab fa-js"></i></h3>
                <h4>JavaScripit</h4>
                <p>JavaScript é uma linguagem de programação criada em 1995 por Brendan Eich enquanto trabalhava na Netscape Communications Corporation. Originalmente projetada para rodar no Netscape. </p>
            </div>
            <div class="clear"></div>
        </div>
    </section>

    <section class="extras">
        <div class="center">
            <div class="w50 left depoimentos-container">
                <h2 class="title">Depoimentos dos nosso clientes</h2>
                <div class="depoimento-single">
                    <p class="depoimento-descricao">"É um facto estabelecido de que um leitor é distraído pelo conteúdo legível de uma página quando analisa a sua mancha gráfica. Logo, o uso de Lorem Ipsum leva a uma distribuição mais ou menos normal de letras, ao contrário do uso de "Conteúdo aqui, conteúdo aqui", tornando-o texto legível."</p>
                    <p class="nome-autor">Lorem Ipsum</p>
                </div>

                <div class="depoimento-single">
                    <p class="depoimento-descricao">"É um facto estabelecido de que um leitor é distraído pelo conteúdo legível de uma página quando analisa a sua mancha gráfica. Logo, o uso de Lorem Ipsum leva a uma distribuição mais ou menos normal de letras, ao contrário do uso de "Conteúdo aqui, conteúdo aqui", tornando-o texto legível."</p>
                    <p class="nome-autor">Lorem Ipsum</p>
                </div>

                
                </div>
            </div>
            
            <div class="w50 left servicos-container">
                <h2 class="title">Serviços</h2>
                <div class="servicos">
                    <ul>
                        <li>Muitas ferramentas de publicação electrónica e editores de páginas web usam actualmente o Lorem Ipsum como o modelo de texto usado por omissão, e uma pesquisa por "lorem ipsum" irá encontrar muitos websites ainda na sua infância. Várias versões têm evoluído ao longo dos anos, por vezes por acidente, por vezes propositadamente (como no caso do humor).</li>
                        <li>Muitas ferramentas de publicação electrónica e editores de páginas web usam actualmente o Lorem Ipsum como o modelo de texto usado por omissão, e uma pesquisa por "lorem ipsum" irá encontrar muitos websites ainda na sua infância. Várias versões têm evoluído ao longo dos anos, por vezes por acidente, por vezes propositadamente (como no caso do humor).</li>
                        <li>Muitas ferramentas de publicação electrónica e editores de páginas web usam actualmente o Lorem Ipsum como o modelo de texto usado por omissão, e uma pesquisa por "lorem ipsum" irá encontrar muitos websites ainda na sua infância. Várias versões têm evoluído ao longo dos anos, por vezes por acidente, por vezes propositadamente (como no caso do humor).</li>
                    </ul>
                </div>
            </div>
            <div class="clear"></div>
        </div>
    </section>

    <footer>
        <div class="center">
            <p>Todos os direitos reservados</p>
        </div>
    </footer>
</body>
</html>
