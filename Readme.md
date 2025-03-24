## Tutorial do CSS GRID(Display Grid)

- Imagine que o container irá definir propriedades gerais como: a forma de alinhamento no caso o grid, qtd de linhas e qtd de colunas.

- Nos itens nós iremos definir propriedades mais específicas como: a posição de um item, tamanho do item, alinhamento do item, e o comportamento do item

## Propriedades | Medidas

- `fr`: vale 33%;
- `minmax(vlm, vlmx)`: Vai definir um tamanho mínimo e máximo para a col ou a lin
- `repeat(x, 200px)`: vai repetir a col x vezes sendo que cada col vai ter 200px
- `gap`: Dá um espaço entre os el itens e também existe o column-gap e row-gap

- `grid-template-columns`: Define a largura de cada col
- `grid-template-rows`: Define a altura de cada lin

1. `justify-content`: Alinha o conteúdo principal de um contêiner, como uma grid ou um flexbox, horizontalmente, caso haja espaço extra. Valores comuns incluem start, end, center, space-between, space-around e space-evenly.

2. `align-items`: Controla o alinhamento vertical dos itens de uma grade ou de um contêiner em relação ao seu eixo cruzado (transversal). Pode ser configurado como start, end, center, stretch, etc.

3. `grid-template-areas`: Define um layout de grade baseado em áreas nomeadas. Permite organizar a grade de forma clara, referenciando as áreas definidas por nomes em grid-area.

4. `grid-column`: Especifica em quais colunas um elemento de uma grade começa e termina. Pode ser configurado com valores como start / end, por exemplo: grid-column: 1 / 3.

5. `grid-row`: Define em quais linhas um elemento de uma grade começa e termina. Assim como grid-column, é configurado com start / end, por exemplo: grid-row: 2 / 4.

6. `align-self`: Controla o alinhamento vertical de um único item em relação ao eixo cruzado do contêiner, sobrescrevendo o align-items para esse item específico. Valores incluem start, end, center e stretch.

7. `justify-self`: Define o alinhamento horizontal de um item específico dentro do seu contêiner, substituindo o justify-items. Pode ser configurado com valores como start, end, center e stretch.

8. `place-items`: Combina as propriedades align-items e justify-items em uma única linha. Define o alinhamento horizontal e vertical dos itens em um contêiner.

9. `grid-auto-rows`: Determina a altura automática de linhas geradas dinamicamente em uma grade. Útil para criar grades com alturas consistentes.

10. `justify-items`: Define como os itens de uma grade (grid) ou de um contêiner são alinhados horizontalmente em relação ao seu contêiner. Pode assumir valores como start, end, center e stretch.

11. `align-content`: Define como as linhas de uma grade ou os itens dentro de um contêiner são alinhados verticalmente quando há espaço extra disponível. Exemplos de valores incluem start, end, center, space-between, space-around e space-evenly.

### Jogos para aprender o seu uso

[Grid Garden (Jardim Grid CSS)](https://cssgridgarden.com/)

[CSS Grid Attack (Ataques Grid CSS)](https://codingfantasy.com/games/css-grid-attack)

### Dicionário de Sigla

> el: Elemento

> container: el pai(no caso a div #container)

> item(ns): el filho(s)(todo el que fica dentro do container)

> qtd: quantidade

> col(s): coluna(s)

> lin(s): linha(s)

> vlm: valor mínimo
> vlmx: valor máximo
