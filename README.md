# Comandos CSS

## align-items: center; (Centraliza Verticalmente)

```js
align-items: center;
```

## animation-name: animacao; (animation-name propriedade especifica um nome para a animação @keyframes)

```js
animation-name: animacao;
```

## animation-duration: (Especifique que a animação deve completar um ciclo de 20 segundos)

```js
animation-duration: 20s;
```

## animation-iteration-count: infinite; (Propriedade especifica o número de vezes que uma animação deve ser reproduzida, infinite significa infinito, agora se colocar numero, vai fazer quantas vezes foi determinado)

```js
animation-iteration-count: infinite;
```

## background-color: (Cor de Fundo)

```js
background-color: #ededed;
```

## border-bottom:(Borda botton)

```js
border-bottom: 1px solid #eee;
```

## border-color: (Cor da borda dos icones)

```js
border-color: rgb(255, 255, 255);
```

## box-shadow:(Deslocamento lateral, Deslocamento vertical, Espalhamento, Cor)

```js
box-shadow: 5 px 5px 10px green;
```

## box-sizing: (Tamanho da caixa, moldura)

```js
box-sizing: border-box;
```

## border-radius: (Arredondar os lados)

```js
border-radius: 20px
```

## border-right: (Borda Lateral)

```js
border-right: 1px solid #ddd;
```

## border-style: (Estilo da borda)

```js
border-style: solid;
```

## border-width: (Largura da borda)

```js
 border-width: 2px;
```

## box-sizing: border-box; (Tamanho da caixa, moldura, o preenchimento e a borda serão incluídos na largura e na altura, ambos div tem o mesmo tamanho agora)

```js
box-sizing: border-box;
```

## border-style: solid; (Estilo da borda)

```js
border-style: solid;
```

## color: (Cor da fonte)

```js
color: white;
```

## cursor: pointer; (Pode clicar neste item)

```js
cursor: pointer;
```

## display: flex; (Para que um item, fique do lado do outro)

```js
display: flex;
```

## display: block; (Quando a tela tiver menor, menu vai aparecer)

```js
display: block;
```

## display: none; (Deixando invisivel, Ocultar)

```js
display: none;
```

exemplo:

```js
/*Deixando chekbox, invisivel*/
#bt_menu{
display: none; /*Ocultar*/
}
```

## flex-direction: (Itens um abaixo do outro)

```js
flex-direction: column;
```

## flex-wrap: wrap; (Quebra a linha assim que um dos flex itens não puder mais ser compactado)

```js
flex-wrap: wrap;
```

## flex: 1; (Pegar o espaço disponivel)

```js
flex: 1;
```

ou

```js
flex: 1 1 200px; /*Flex: Espandir, Ficar menor, Base para a foto*/
```

## font: (Tipo de fonte)

```js
font: normal 15 pt Arial
```

## font-family: (Tipo de fonte)

```js
font-family: 'Montserrat', sans-serif;
```

ou

```js
font-style: italic;
```

## font-size: (Tamanho da fonte)

```js
font-size: 12pt;
```

## font-weight: normal; (Espessura da fonte)

```js
font-weight: normal;
```

## flex: (Flex: Espandir, Ficar menor, Base para a foto)

```js
flex: 1 1 200px;
```

## height: (Altura)

```js
height: 100%;
```

## justify-content: space-between; (Dos itens que tem dentro do header, vai ter espaços entre eles, ou seja joga um para um lado o outro para o outro e tera um espaço entre eles)

```js
justify-content: space-between;
```

## justify-content: center; (Alinhamento)

```js
justify-content: center;
```

## list-style: none; (Sem marcador)

```js
 list-style: none;
```

## line-height: (Altura da linha)

```js
line-height: 1.35em;
```

## margin: auto; (Centralizar no meio da tela, a margem)

```js
margin: auto;
```

ou

```js
margin: 0 auto;
```

ou

```js
margin: 10px; /*Espaço entre a foto
```

## margin-top: (Margem superior)

```js
 margin-top: 5px;
```

## margin-bottom: (Margem inferior)

```js
margin-bottom: 18px;
```

## margin: (Margem, espaço lateral do botão)

```js
margin: 1em 0;
```

## margin-left: (Margem esquerda)

```js
margin-left: auto;
```

## margin-rigth: (Margem direita)

```js
margin-right: auto;
```

## margin-top: (Margem superior)

```js
margin-top: 5px;
```

## max-width: (Maxima Largura)

```js
max-width: 415px;
```

## min-height: (Altura minima)

```js
min-height: 500px;
```

## opacity: 0; (Opacity especifica a trasparencia de um elemento, isto é, o grau no qual o background atrás do elemento é sobreposto)

```js
opacity: 0;
```

## opacity: 1; (Totalmente opaco)

```js
opacity: 1;
```

## outline: none; (Esboço)

```js
outline: none;
```

## padding: (Distancia entre os lados, 0, encima e embaixo, 15px distancia entre os dois lados)

```js
padding: 0 15px;
```

## position: relative; (As propriedade position pode assumir 4 valores diferentes: Static, Relative, Absolute e Fixed Utilizando o position relative o elemento passa a aceitar as propriedades Top, Botton, Left e Rigth. Com elas você pode alterar o posicionamento do elemento*/ overflow: visible; /*A propriedade overflow define o comportamento de um elemento quando suas dimensões são excedidas pelo conteúdo Hidden, O Conteudo excedido não ficará visível)

```js
position: relative;
```

## position:absolute; (Com ele você pode posicionar qualquer elemento)

```js
position: absolute;
```

## position: fixed; (Quando clicado, fixar a imagem no meio da tela, independente se rolar para baixo ou para cima)

```js
position: fixed;
```

## text-align: center; (Centralizar no meio da tela, o titulo)

```js
text-align: center;
```

## text-decoration: none; ([none (Sem decoração)], [underline red (sublinhado red)], [underline wavy cor (Sublinhado ondulado cor)] )

```js
text-decoration: none;
```

## transition: (Tempo, após passado o mouse, vai carregando a cor no tempo)

```js
transition: all 0.35s;
```

Exemplo: Adicionando efeito ao botão

```js
input[type="button"]:hover,
input[type="button"]:focus {
background-color: #b10b7f; /*Cor apos passado o mouse em cima do botão*/
border-color: #850909; /*Cor da borda após passado em cima do botão*/
transition: all 0.35s; /*Tempo, após passado o mouse, vai carregando a cor no tempo*/
```

## visibility: hidden; (O elemento está oculto mas ainda ocupa espaço)

```js
visibility: hidden;
```

## width: (Largura )

```js
width: 100%;
```
