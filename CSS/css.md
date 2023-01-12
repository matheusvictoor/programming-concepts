# CSS

CSS (Cascading Style Sheets) é uma linguagem de folhas de estilo que é usada para definir a apresentação visual de uma página web. Ele é usado para controlar a cor, o tamanho, a fonte, a posição e outros aspectos de como os elementos HTML são exibidos na página.

As marcações CSS incluem:

## Seletores

   - Seletores de elemento, como p, h1, a, etc. são usados para selecionar elementos específicos na página.
   - Seletores de classe, como .example, são usados para selecionar elementos que possuem uma determinada classe.
   - Seletores de ID, como #example, são usados para selecionar um elemento específico que possui um determinado ID.

## Propriedades

   - Propriedades como color, font-size, background-color, width, height, etc. são usadas para definir as características visuais dos elementos selecionados.
   - Exemplo de como aplicar propriedade:
```
    p {
        color: blue;
        font-size: 14px;
    }
```
## Valores

   - Valores são atribuídos às propriedades para especificar como elas devem ser exibidas.
   - Exemplo de como aplicar valores:
```
    h1 {
        color: red;
    }
```
## Regra @

   - As regras @ são usadas para adicionar informações adicionais ao arquivo CSS.
   - Exemplo de como aplicar regra @:
```
    @import url('outro.css');
    @media (min-width: 700px) {
        /* regras CSS */
    }
```
## Box Model

   - O modelo de caixa é usado para controlar como os elementos são exibidos em termos de largura, altura, margem, borda e espaçamento.
   - Exemplo de como aplicar box model:
```
    div {
        width: 100px; 
        height: 100px;
        margin: 10px;
        padding: 10px;
        border: 1px solid black;
    }
```
## Posicionamento

   - As propriedades de posicionamento, como position, top, bottom, left e right, são usadas para controlar a posição dos elementos na página.
   - Exemplo de como aplicar posicionamento:
```
    div {
        position: absolute;
        top: 10px;
        right: 10px;
    }
```
## Transições e animações
    
   - transition: propriedade que permite que as propriedades de um elemento alterem suavemente de um estado para outro.
   - animation: permite que os elementos sejam animados usando uma série de regras CSS.

## Responsividade

   - media queries: permite que o CSS seja aplicado de maneira diferente dependendo do tamanho da tela e outras características do dispositivo.

## Flexbox

   - display: flex: permite que os elementos filhos sejam alinhados e organizados de maneira flexível dentro de um elemento pai.

## Grid

   - display: grid: permite que os elementos sejam organizados em uma grade com colunas e linhas definidas.

Esses são apenas alguns exemplos de como o CSS pode ser usado para criar páginas da web mais avançadas e estilizadas. Existem muitas outras possibilidades e recursos disponíveis.
