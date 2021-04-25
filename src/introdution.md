#CSS
## SIGNIFICDO
  *CASCADING STYLE SHEET
  * Código para criar estilos no HTML
  * Não é uma linguagem de programação
  * é uma linguagem de style sheet

## Comentários

/* */

## Anatomia

elemento html {
  propriedade css : valor
}

ex:

h1{
    color: blue;
}

## Selectors

  Conecta um elemento html com o CSS

  ## Tipos

  Global '*'
  Element/Type selector 'h1, h2, p , div'
  ID Seletor '#box, #container'
  Class Selector '.red, .m-4'
  Attribute selector, Pseudo-class, Pseudo-element, e outros

  ## Caixas

  * Quase tudo no são caixas do Css
  * Posicionamentos, tamanhos, espaçamentos, bordas, cores
  * Caixa pode ficar ao lado ums da outra ou em cima e embaixo
  * Elementos Html são caixas, Cada elemento é uma caixa

  ## Adicionando Css

  ### inline

  * atibuto `style` escrito diretamente na tag html

  ### <link>

  * tag html que irá conter o html

  ### @import

  * arquivos css externos

  ## A Castata (cascading)

  A escolha do browser de qual regra aplicar, caso haha muitas regras para o mesmo elemento.

  * Seu estilo é lido de cima para baixo.

  É levado em consiração 3 fatores 

  1. Origem do Estilo
  2. Especificidade
  3. Importância

  ### Origem do Estilo

  Inline > tag style > tag link

  ### Especificidade 

  É um cálculo matemático, onde, cada tipo de seletor e origem do estilo, possuem valores a serem considerados.

  0. Universal selector, combinators e negation pseudo-class (:not())
  1. Element type selector e pseudo-elemet (::before, ::after)
  10. Calsses e atributte selectors ([type="radio"])
  100. ID selector
  1000. inline

  ### A regra !important

  * cuidado, evite o uso
  * não é uma boa prática
  * quebra o fluxo natural da cascata
  * sobrescreve desconsiderando as regras das cascatas








