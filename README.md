# Starter-HTML-E-CSS

 O curso tem sido de suma importância a onde eu estou me localizando novamente - 07/08/2023

# Desafio HTML dia 08/08/2023

- [x] Adicionar as imagens
- [x] Criar os pontos de navegação
- [x] Criar a navegação entre os arquivos
- [x] Criar as listas
- [x] Finalizar projeto

# Estudo dia 09/08/2023

Hoje aprendi sobre tabelas no HTML, daqui a pouco vamos aprender a como personalizar com o CSS, que será de suma importância para o uso do Front End

# Estudo dia 10/08/2023

Hoje aprendi sobre meta e como utilizar em diferentes hipóteses

# Estudo dia 11/08/2023

## O que significa CSS

* Cascading Style Sheet
* Código para criar estilos no HTML

## Exemplos

/* Comentarios no código são escritos assim: */ não esqueça de fechar o comentário ao abri-lo

# Anatomia do CSS

```Css

h1 {
    color:blue;
    font-size:60px;
    background:gray;
}

```

* Selector
* Declaration
* Properties
* Property Value

# Selectors

Conecta um elemento HTML com o CSS

## Tipos

* Global selector `*`
* Element/Type selector `h1, h2, p, div`
* ID Selector `#box, #container`
* Class Selector `.red, .m-4`
* Attribute selector, Pseudo-class, Pseudo-element, e outros

# DIA 21/08/2023

Semana passada foi uma semana corrida e não consegui estudar mas essa semana eu consigo...

* Tamanho (largura x altura): width e height, respectivamente
* Conteúdo: o content
* Bordas: o border
* Preenchimento interno: o padding
* Espaços fora da caixa: a margin

# Adicionando CSS

## Inline

* atributo `style`

## <style>

* tag html que irá conter o css

## <link>

* arquivo css externo

## @import

* arquivo css externo

# Estudo dia 22/08/23

# A Cascata (cascading)

A escolha do browser de qual regra aplicar, caso haja muitas regras para o mesmo elemento

* Seu estilo é lido de cima para baixo.

É levado em consideração 3 fatores

1. Origem do estilo
2. Especificidade
3. Importância

### Origem do estilo

inline > tag style > tag link

### Especificidade

É um cálculo matemático, onde, cada tipo de seletor e origem do estilo, possuem valores a serem considerados.

0. Universal selector, combinators e nagation pseudo-class (:not())
1. Element type selector e pseudo-elements (::before, ::after)
10. Classes e attribute selectors ((type="radio))
100. ID selector
1000 Inline

# Estudo dia 23/08/2023

Bora lá para mais um dia de estudo

### A regra !important

* cuidado, evite o uso
* não é considerado uma boa prática
* quebra o fluxo natural da cascata

# At-rules

* Está relacionado ao comportamento do CSS
* começa com o sinal de `@` seguido do identificador e valor

## Exemplos comuns

- @import /* incluir um CSS externo */

- @media /* regras condicionais para dispositivos */

- @font-face /* fontes externas */

- @keyframes /* Animation */

```css
@import "https://local.com/style.css";

@media (min-width: 500px) {
    /* rules here */
}

@font-face {
    /* rules here */
}

@keyframes nameofanamiton {
    /* rules here */
}
```

# Shorthand

* junção de propriedades
* resumido
* legível

```css

{
    /* background properties */
    background-color: #000;
    background-image: url(images/bg.gif);
    background-repeat: no-repeat;
    background-position: left top;

    /* background shorthand */
    background: #000 url(images/bg.gif) no-repeat left top;

    /* font properties */
    font-style: italic;
    font-weight: bold;
    font-size: .8em;
    line-height: 1.2;
    font-family: Arial, sans-serif;

    /* font shorthand */
        font: bold italic .8em/1.2 Arial, sans-serif;
}
```
## Detalhes

* Não irá considerar propriedades anteriores
* Valores não especificados irão assumir o valor padrão
* Geralmente, a ordem descrita não importa, mas, se houver muitas propriedades com valores semelhantes, poderemos encontrar problemas

## Propriedades que aceitam shorthand

animation, background, border, border-bottom, border-color, border-left, border-radius, border-right, border-style, border-top, border-width, column-rule, columns, flex, flex-flow, font, grid, grid-area, grid-column, grid-row, grid template, list-style, margin, offset, outline, overflow, padding, place, content, place items, place self, text decoration, transition

# Estudo dia 24/08/2023

Hoje o dia foi exaustivo mas bora pra cima

# Funções

* nome seguido de bre e fecha parentesis
* recebe argumentos

## Exemplos

```css

@import url("http://urlaqui.com/style.css");

{
    color: rgb(255,0,100);
    width: calc(100% - 10px);
}