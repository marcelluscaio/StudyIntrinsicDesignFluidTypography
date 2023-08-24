Roteiro

Principios:
- Nao existe maneira certa de fazer as coisas em programacao. Existem formas nao-erradas
- "Na minha tela funciona" - Lidando com variaveis: conteudo, tamanho de tela, preferencias do usuario

Tipografia fluida
1 - Uso de px x rem
- rem resolve acessibilidade, nao responsividade;
- Acessibilidade x Responsividade
- Analisando a fonte fluida
- como fornecer uma medida "de seguranca" (fallback)

Layout fluido
2 Containers
- O que sao
- Como construir um container
- Width px x % 
- Usando max-width
- Width x padding x margin (padding inviabiliza a existencia de um background no pai) (EXPLORAR ISSO)
- Retomar: container com width, padding e margin: tudo pode funcionar, mas width eh mais facil 
  - O que importa eh: use o mesmo metodo para todo o site
  - Primeiro ponto: nao precisa dividir por dois.
  - Usando margin podemos ter problema com o max-width
  - Usando padding vamos travar na width e ter comportamentos inesperados
  - Por isso digo que o mais facil eh trabalhar com width
- padding e margin - px x rem x em x vh
(IMPORTANTE QUE SEJAM MEDIDAS RELATIVAS. Solucoes: min(% ou vw + rem) ou apontar para a fonte)


3 - E containers dentro de containers?

- Card com px?
- Nunca usar width e height fixos
- height e %
  https://codepen.io/marcelluscaio/pen/WNLvKLP
- Importância do flex e do grid
- Criando um botao



4 - Imagens
- Imagens não tem conteudo
- O que acontece usando px?
- Faz sentido usar rem?
- Razao de aspecto



COLOCAR DIV NA SECAO E DEIXAR A COMPARACAO WIDTH X PADDING E MARGIN


Objetivo:
Mais do que tecnicas específicas, quero reforçar a forma de pensar:
- A internet é responsiva por padrão, se algo está quebrado, nós cometemos algum erro
- Em vez de números absolutos, pensar na relação daqueles valores com relação ao tamanho da tela e aos outros elementos
- Imaginar seu layout sujeito a condições diversas: 
    E se a fonte do usuário for diferente da padrão? 
    E se um novo card for adicionado? 
    E se esse texto tiver 4 paragrafos em vez de 1?

Problemas:
- Eh menos exato

Defensive CSS
The CSS we write should also be responsive to the user content. 
If it’s too long, what should happen? We need to decide on these decisions early on.



Refs
https://ishadeed.com/article/responsive-design/

https://www.smashingmagazine.com/2022/01/modern-fluid-typography-css-clamp/



