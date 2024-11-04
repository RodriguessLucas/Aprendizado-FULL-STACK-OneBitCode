APRENDENDO HTML


1 - INFO SOBRE HTML
    -HTML = hyperText Markup Language

    -É uma linguagem usada para criar uma estrutura de elementos
    e suas informações, mais precisamente, os elementos de umapágina web.

    -Criada entre 1989 e 1990 para compartilhar pesquisas científicas.


2- COMO FUNCIONA
    -Através de arquivos de texto com a extensão .html;
    
    -Usamos tags para representar os elementos que queremos exibir na página
    web;
    
    -Existem muitos tipos de elementos no HTML: títulos, fotos cabeçalhos e etc;

    -Uma tag pode ter atributos, que são características especiais de um determinado
    elemento;

    -Exemplo de tag:
        <p> isso é uma tag<p>
    -Exemplo de tag com um atributo:
        <p id="paragrafo-principal"> isso é uma tag com atributo<p>


3- RECURSOS IMPORTANTES PARA AJUDAR NOS ESTUDOS:
    -Documentação do html;
    -W3schools;

4- ESTRUTURA DE UMA PÁGINA WEB
    -OBS: coloque sempre a página principal como index.html
    - Uma página web é composta por partes principais, o head e body;
    - a tag <had> define os meta dados do documento, ou seja, informações
    sobre o própio documento;
    -<head> é feito para o navegador, para que ele conheça melhor a pagina 
    html em questão
    - a tag<body contém todo o conteúdo visível do documento;
    - <body> é feito para os usuários, ela é a pagina em si;
    -<img src="nome da imagem" alt="">
    coloca a imagem no site, alt e weight são mais modificado em css
    o alt é um texto alternativo caso a imagem não carregue
    sempre passe o caminho para a imagem ser carregada corretamente
    dá para usar imagens da internet, só passar a url da imagem

5 - OBSERVAÇÃO SOBRE HTML
    - voce pode separar todos os arquivos html em pastas
    graças ao index.html. pois como é o padrão, voce
    pode ir indo por diretório. cois boa

6- Como comentar o código?
    -em html usamos apenas <!-- comentario -->
    somente isso!

7- FORMATOS E OTIMIZAÇÃO DE IMAGENS 
    - É importante que a página web sempre esteja otimizada
    consome mais dados, demora mais para carregar, faz com que o 
    viewer desista muitas vezes;
    - O que mais demora para carregar é as imagens
    - como otimizar as imagens:
        ultilize formatos corretos:
            JPEG(mais pesado e de maior qualidade)
            PNG(inferior a jpeg, mas pode ser comprimido mantendo qualidade)
            WEBP(equilibrado entre qualidade e tamanho de arquivo)
            SVG(usado para vetores, são super leves e pode escalar para qualquer tamanho)

            OBS: tente sempre usar o WEBP 
        Sempre tente comprimir a imagem, se possivel
        Ultilize os tamanhos corretos
            -Imagens grandes demais ficam pesadas e pequenas demais ficam pixeladas
            -Se necessário, use o atributo srcset para definir diferentes versoes da imagem
            para diferentes dispositivos.

8- QUEBRAS DE LINHA HORIZONTAL E VERTICAL
    br é quebra de linha de uma linha
    hr é uma imposião de uma regua HORIZONTALa pagina
    é somente para saber, será aplicado mais em CSS

9- ORGANIZAÇÃO DE CÓDIGO COM DIV E SPAN
    div organiza em bloco
        cria algo parecido com um paragrágo
    span organiza em linha
        cria algo parecido com uma tag
    Em um texto, o elemento div irá organizar o conteúdo em
    um bloco, ou seja, como uma quebra de linha.
    mais uma div para mostrar
    Uma div ocupa todo o espaço horizontal disponível na tela. 
    Já o elemento span irá organizar o conteúdo de forma "inline", ou seja, 
    sem quebra de linha e ocupando apenas a largura do seu conteúdo interno.

10- TRABALHANDO COM LINKS
    é chamada de ancora e a tag é a
    <a href="/exercicio(artigo)/index.html">Artigo</a>
    Exemplo acima é um link.
        onde tem artigo é o texto clicavel
        href é a referencia(passa por diretório)

11- URLS ABSLUTAS E RELATIVAS
    Antes de entender sobre URLs absolutas e relativas é importante
    conhecer o conceito de "raiz". A "raiz ou "diretorio raiz"
    é o caminhoo inicial do site. Em nossos links da aula anterior 
    a raiz é o arquivo intex.html. A raiz é a página onde caímos quando
    não especificamos nenhum caminho na URL, apenas o endereço base.

    URL absoluta: é o caminho completo de uma URL, de uma 
    determinada página.

    URL relativa: é uma URL que não é o caminho completo e sim o 
    caminho relativo à página atual.

12- LNKS DENTRO DE UMA PÁGINA
    São links para diferentes sessoes na mesma página

    Os elementos podem ter um ID, que é uma especie
    de classificação de classe, ou seja, identificar o tipo
    especial q é.

    <a href="#titulo-1">Título 1</a>
        O jogo da velha indica que é uma sessão na página atual.
        O href será o id que vc criou.

13-LINKS EXTERNOS
    São links que levam a outras páginas fora do que vc criou
    é só passar o protocolo(link completo).
    <p>Acessar a página do <a href="https://google.com">Google</a>.</p>
    veja esse Exemplo.
    acima ele abre a página sobre a página atual

    Se quiser abrir em uma nova guia usasse o target="_blank"
    <p>Acessar a página do <a href="https://google.com" target="_blank">Google</a>.</p>

14- LISTAS NO HTML: ORDENADAS E NÃO ORDENADAS:
    <ul> lista não ORDENADAS
    <ol> lista ordenada
    dentro de cada um para criar um texto usa-se <li>

15 - TABELAS
    Tabelas são elementos do html que permite organizar dados em linhas
    e colunas.

    AS principais tags são <table>,<tr> e <td>
    <tr> tag da linha
    <td> tag da coluna
    <th> tag para marcar em negrito a info
    <thead> tipo um o head do html para Tabelas
    <tbody> tipo o Body para tabelas

16- FORMULÁRIOS
    são responsaveis por fazer a comunicação 

    São estruturas que permitem a coleta de informações dos 
    usuários, como nome, senha email e etc.

    São compostos por elementos html que possibilita a criação
    de campos de entrada, botoes de envio e outras funções
    interativas.

    De forma simples, a comunicação na web ocorre de duas formas 
    : Obtendo dados e enviando dados. Sendo os formularios os 
    principais pela segunda.

    Os formulários são compostos por:
        tag <form> com atributos "action" e "method"
        campos a serem preenchidos, como <input> ou <select>
        botões para enviar <button type="submit"> texto</button>

    TIPOS de INPUT:
    
        



    