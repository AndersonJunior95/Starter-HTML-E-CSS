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
