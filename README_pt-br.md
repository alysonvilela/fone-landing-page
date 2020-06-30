# COMO E PORQUE COMEÇOU

O UI design foi feito por <a href="https://www.linkedin.com/in/emmanuel-messias-535621127/">Emmanuel Messias</a> para o <a href="https://www.devchallenge.com.br/">DevChallenge</a>, e neste artigo vou falar sobre como foi o processo de criação que utilizei para finalizar este site.

Não houve nenhum protótipo em Adobe XD ou Figma para que a conclusão do projeto fosse concluída, e isso é bom e ruim por esses dois motivos:

- **:/**: Com protótipos, todos os dimensionamentos corretos ficam claramente mais fáceis e ágeis para que projeto seja concluído.
- **:)**: Sem eles, pude ter uma base sobre o dimensionamento nas diversas possibilidades de tela. O que provavelmente no futuro, conceitos como flexbox, unidades de medida em em/rem e dimensionamento de fontes se tornarão automáticos para novos projetos.

<p align="center">
    <img src="https://i.imgur.com/YuUaCDv.gif" alt="Logo" width="1000"> </p>

## O QUE VOCÊ VAI ENCONTRAR

* [COMO E PORQUE COMEÇOU](##COMO-E-PORQUE-COMEÇOU) 
* [MODELOS](#MODELOS)
* [MOBILE FIRST CONCEPT](#MOBILE-FIRST-CONCEPT)
* [OS PRIMEIROS PASSOS](#OS-PRIMEIROS-PASSOS)
* [CSS REQUISITOS](#CSS-REQUISITOS)  
* [ADAPTAÇÕES](#ADAPTAÇÕES) 
* [PROJETO FINAL](#PROJETO-FINAL) 

## MODELOS

<p align="center">

![Desktop](https://raw.githubusercontent.com/alysonvilela/fone-landing-page/master/design/desktop.png)
  
![Mobile](https://raw.githubusercontent.com/alysonvilela/fone-landing-page/master/design/mobile.png)</p>
 

 <p align="center"> Para esse projeto foi necessário utilizar a seguinte paleta de cores: <br>
Vermelho: #ca3b3a<br>
Preto: #161616<br>
Cinza: #707070 </p>

## MOBILE FIRST CONCEPT

A ideia do conceito é a real utilização da plataforma, e, neste caso como a utilização é voltada a compras. Após um curto período de pesquisa é possível afirmar que a maioria dos usuários de plataformas de compra online utilizam smartphones para realizar suas compras. Além de ser mais "fácil" de diagramar, de acordo com o site [Polypane)](https://polypane.app/blog/responsive-design-ground-rules/).


## OS PRIMEIROS PASSOS

Como um protótipo inicial, com medidas ou porcentagens não existia, o primeiro passo foi pensar em como cada item se encaixaria em blocos. Na home section por exemplo, é possivel ver que existem dois blocos (imagem e informações) que são reajustados conforme o tamanho da tela.

Assim nasceu a primeira lista dos itens necessários para esse projeto:

 - HTML
	- Identify what will be Flexbox, Block, Inline
     - Default body
       		- Header with navbar
       		- Home section
       		- Info sectio
- CSS
	- Format root settings
	- Import font
		- Code

Com isso, fiz um diagrama ~~não tão bonito, mas que eu conseguia entender~~ que se tornou a base para todos os blocos utilizados.

Você consegue ver o diagrama [aqui](https://github.com/alysonvilela/fone-landing-page/projects/3).

## CSS REQUISITOS
Como o sistema de grids não foi utilizado, utilizou-se recursos e sistemas básicos para toda semântica.

**Os atributos mais utilizados foram:**
- Flexbox
    - Flex direction
    - Justify-content
    - Align-items
- Padding
- Margin
- Media Query

## ADAPTAÇÕES
Conforme o projeto foi andando, percebi algumas animações e adaptações que talvez fossem interessantes para não deixar o site tão *"cru"*. 

Então decidi colocar uma **shadow-box** na versão de desktop para destacar o **.contents** e colocar uma animação float no fone que estava ao lado, chamando atenção ao design daquele item em específico.

## PROJETO FINAL
Você pode ver o projeto final [aqui](https://alysonvilela.github.io/fone-landing-page). 

*OBS: No lugar dos ícones da nav bar, decidi inserir spans para representá-los*

Este desafio foi criado por <a href="https://www.linkedin.com/in/emmanuel-messias-535621127/">Emmanuel Messias</a> :)
