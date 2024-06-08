
# Projeto: Básico HTML e CSS


## Visão Geral

Este projeto é uma página web simples que promove um serviço de criação de ambientes personalizados e elegantes. A página é composta por um cabeçalho (hero), uma linha de divisão e um rodapé com links para redes sociais e contato por email.

## Tecnologias Utilizadas

HTML5: Utilizado para estruturar o conteúdo da página.
CSS3: Utilizado para estilizar o conteúdo da página.


## Estrutura do HTML

    <!DOCTYPE html>
      <html lang="pt-br">
      <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Móveis Customizados</title>
        <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="./styles.css">
      </head>
      <body>
        <div id="hero">
          <img src="images/img1.jpg" alt="Desenho de uma pessoa com camisa amarela estando em uma sala com móveis">
          <h1>Ambientes <span>únicos</span> para você!</h1>
          <p>Nós criamos ambientes <strong>exclusívos</strong> e <strong>únicos</strong>, com muito bom gosto e profissionalismo, investimos tempo e <span>dedicação no seu projeto.</span>
          <br/> <br/> Tenha <span>ambientes limpos</span> e bem decorados, transmitindo <strong>elegância</strong> e <strong>finesse</strong> para todo aquele que estiver ali.</p>
        </div>
        <div id="line"></div>
        <div id="footer">
          <a target="_blank" href="https://www.instagram.com">Instagram</a>
          <a href="mailto:contato@moveisparavoce.com">Fale Conosco</a>
        </div>
        <img id="balls" src="images/balls.svg" alt="Bolinhas laranjadas no canto direito da tela">
      </body>
      </html>



### Explicação do HTML

     - <!DOCTYPE html>: Declaração do tipo de documento, especificando que
       estamos utilizando HTML5.
     - <html lang="pt-br">: Início do documento HTML com a especificação do
       idioma.
     - <head>: Contém metadados sobre o documento, incluindo links para
       fontes externas e o arquivo de estilos CSS.
     - <body>: Contém o conteúdo visível da página.
     - <div id="hero">: Seção principal da página, incluindo imagem, título
       e descrição.
     - <div id="line">: Linha de divisão entre as seções.
     - <div id="footer">: Rodapé com links para redes sociais e contato.
     - <img id="balls">: Imagem decorativa fixa no canto inferior direito da
       tela.

 ### Estilos CSS

      body {
      font-family: 'Open Sans', 'sans-serif';
      text-align: center;
      margin: 0;
    }
    
    #hero {
      width: 592px;
      margin: 0 auto 72px;
    }
    
    #hero img {
      margin-top: 72px;
    }
    
    h1 {
      font-family: 'Inter', 'sans-serif';
      font-size: 49px;
      line-height: 56px;  
      font-weight: normal;
      margin-bottom: 32px;
    }
    
    h1 span {
      font-weight: bold;
    }
    
    span, a {
      color: #FF9900;
    }
    
    p, #footer {
      color: #7D7987;
      font-size: 14px;
      line-height: 28px;
    }
    
    #footer a + a {
      margin-left: 28px;
    }
    
    #line {
      width: 568px;
      height: 0;
      margin: 0 auto 8px;
      border: 1px solid #ECEFF2;
    }
    
    #balls {
      position: fixed;
      bottom: 0;
      right: 0;
    }


### Explicação do CSS

 - body: Define a fonte padrão e centraliza o texto, além de remover
   margens.
 - #hero: Centraliza e define a largura da seção principal.
 - #hero img: Adiciona uma margem superior à imagem principal.
 - h1: Define a fonte, tamanho, altura da linha e margem do título.
 - h1 span: Adiciona negrito ao texto dentro do span no título.
 - span, a: Define a cor laranja para spans e links.
 - p, #footer: Define a cor do texto, tamanho da fonte e altura da linha
   para parágrafos e rodapé.
 - #footer a + a: Adiciona margem esquerda aos links no rodapé para espaçamento.
 - #line: Define a linha de divisão com largura, altura e borda.
 - #balls: Posiciona a imagem decorativa no canto inferior direito da tela.

## Conclusão

Neste projeto, o aprendizado de criar uma página HTML básica e aplicar estilos CSS para melhorar a aparência do conteúdo. Foi utilizado o Google Fonts para importar fontes externas e garantir uma aparência mais profissional. O conhecimento adquirido pode ser expandido para criar páginas web mais complexas e interativas.