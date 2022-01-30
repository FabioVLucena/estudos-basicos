HTML TAGS >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
<!DOCTYPE html> = identifica o documento como html 
<html lang="pt-br"> = abre o documento html

<head> = onde ficam as informações de configuração do documento
	<meta charset="UTF-8"> = usada para descrever o conteúdo 
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="style/main.css"> = especifica as relações entre o documento atual e um recurso externo
	<title>titulo-exemplo<title> = titulo da pagina, nome que ira aparecer na aba
</head>

<body> = corpo do documento html
	
	<div class="div-name"> = div são quadrados de divisao de informação, servem para facilitar a manipulação
	<header> = tag de identificacao do cabeçalho do corpo
	<main> = tag de identificacao da parte principal do corpo
	<footer> = tag de rodapé do corpo "4 tags acima são praticamento obrigatorias, mesmo não sendo"
		<nav> = tag de identificacao de divisao de navegação "geralmente usada em menus de navegaçao"
			<h1>string</h1> = tag de texto de titulo
			<h2>string</h2>	= tag de texto de titulo maior		
			<h3>string</h3> = tag de texte de titulo bem maior
			<p>string</p> = tag de descricao ou texto
			
			<a href="#">link-name</a> = tag de criacao de links
			<img class = "image-name" src="img/exemple.jpg" alt=""> = tag que estancia uma imagem
			<i class="icon-name"></i> = tag que estancia um icone		
			<button role="button" class="button-name">string</button> = tag de criacao de botoes

	<script src="https://exemple.com.br" crossorigin="anonymous"></script> = tag de script js, deve ser colocada no fim do codigo para evitar notFoundExceptions.

</body>
</html>

	--info--

-lang = define a linguagem padrao do documento
-chasert = definido como uma forma de indicar qual a lógica binária foi utilizada para armazenar letras e números dentro de bits.
-name = o atributo NAME é o identificador dentro de uma requisição GET ou POST no servidor.
-content = A propriedade CSS content é usada com os pseudoelementos ::before e ::after para gerar conteúdo em um elemento.
-rel = ele fala o tipo de relacionamento que o link vai ter com o codigo. 'Eu acho'
-href = pra onde vc vai ser clicar em algo.
-src = onde o codigo deve buscar a informação.
-alt = O alt atributo obrigatório especifica um texto alternativo para uma imagem, se a imagem não puder ser exibida.
-crossorigin = nao sei descrever.
-class = forma de localizar e manipular de forma mais facil um objeto dentro do codigo. Mais de um objeto pode ter o mesmo nome de class, permitindo alterações por javaScript ou Css em massa.

-role = esse atributo serve para dar sentido a uma determinada área ou conteúdo do site, isso ajuda muito os leitores de tela para identificar que tipo de conteúdo uma determinada área ou elemento apresenta.
	<header role="banner"> <!-- Cabeçalho -->
	<main role="main"> <!-- Conteúdo principal -->
	<article role="article"> <!-- Artigo do site -->
	<footer role="contentinfo"> <!-- Rodapé -->
	
CSS CODES >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
:root{ = cria enums
    --vermelho:#E50914;
    --preta:#141414;
}

*{ = altera todos os objetos do documento
    margin:10px; = define todas as margens para 10px    
    padding:10px; = define todas os paddings para 10px
    width: 600px; = define o largura do obejto para 600px
    height: 570px; = define a altura do objeto para 570px


    margin-top: 10px; = define a margem de cima para 10px
    margin-left: 10px; = define a margem da esquerda para 10px;
    margin-right: 10px; = etc...
    margin-bottom: 10px; "Padding tbm tem top, left, right, bottom"



    font-size: 40px; = define o tamanho da fonte para 40px
    color: var(--vermelho); = define a cor da fonte de vermelho com nosso enum
    font-family: 'Times New Roman', Times, serif; = define a fonte principal como times new roman, e na ausencia dela qualquer uma das outras duas familias times ou serif pode substituir ela.
    text-decoration: none; = remove a formatacao do texto;


    display: block; = O elemento gera uma caixa de elemento de bloco
    display: flex; = O elemento se comporta como um elemento de bloco e apresenta seu conteúdo de acordo com o modelo flexbox.
    flex-direction: column; = define como os itens serao alinhados na div
    justify-content: center; = define como os itens irao se organizar na div
    border: none; = retira a borda do objeto
    align-items: flex-start; = alinha itens na div no canto superior esquerdo;


    background-size: cover; = tamanho do background ira seguir os objetos
    background: linear-gradient(rgba(0,0,0,.50), rgba(0,0,0,.50)100%), url('/img/menu-principal.png'); = define cor de fundo em gradiente
    background: var(--preta); = define cor de fundo de preto
    background-color: rgba(0,0,0,.50); = define cor de fundo;

    box-sizing: border-box; = faz com que os objetos nao alterem o tamanho da div 

    cursor: pointer;   
    transition: .3s ease all;  faz um timer de transicao quando acionado o hover
}

- hover = aciona quando o cursor passar por cima;

header .container{ = altera <tag> .class 
    display: flex; 
    flex-direction: row; 
    align-items: center; 
    justify-content: space-between;
}

@media screen and (max-width:700px){ = faz alterações na tela quando tiver uma largura de no maximo 700px;
    header .container{
        display: flex;
        flex-direction: column;
    }

    .botao{
        margin-top: 5px;
        width: 300px;
        height: 70px ;
    }
}


JS CODES >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
"É isso ai mermo"


