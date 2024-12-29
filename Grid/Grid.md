# GRID

<br>
CSS Grid trouxe várias possibilidades para o desenvolvimento de layouts modernos. Veja como alinhar conteúdos com CSS Grid.<br>
<br>
Outras 4 propriedades bastante importantes ao se trabalhar com CSS Grid são:<br>
<br>
    - align-items
    - justify-items
    - align-self
    - justify-self
<br>
<br>
Essas são propriedades CSS que permitem alinhar conteúdo dentro de células da grid, o que pode ser bastante útil no desenvolvimento de qualquer layout com CSS.<br>
<br>
<br>
O Grid por padrão oculpa por total o tamanho onde se encontra
<br>
<a href="https://www.w3schools.com/css/css_grid.asp">CSS grid</a><br>
<a href="https://www.youtube.com/playlist?list=PLYgzkrmJnLwpeeGgdADYq3cE2yUwLLTOv">Curso em vídeo</a><br>
<a href="https://css-tricks.com/snippets/css/complete-guide-grid/">Guia completo de Grid</a><br>
<br>
<br>
___________<br>
**Grid-template-columns**<br>
O grid-template-columns propriedade especifica o número (e as larguras) das colunas em uma grade layout. <br>
<a href="https://www.w3schools.com/cssref/pr_grid-template-columns.php">W3chools grid-template-column</a><br>
<br>
Exemplo no codepen:<br>
<a href="https://codepen.io/Sameer-Begh/pen/bGmYZaY">CodePen Home
Grid-template-columns (CSS-only)</a><br>
<br>
<br>
___________<br>
**Grid-column-gap**<br>
A propriedade grid-column-gap define o tamanho do intervalo entre as colunas..<br>
<a href="https://www.w3docs.com/learn-css%20/grid-column-gap.html">W3Docs - grid-column-gap</a><br>
Exemplo Codepen<br>
<a href="https://codepen.io/hubspot/pen/yLRwmvx">Grid-Column_Gap</a><br>
<br>
<br>
___________<br>
**Grid-template-rows**<br>
O grid-template-rows propriedade especifica o número (e as alturas) das linhas em um layout de grade.<br>
<a href="https://www.w3schools.com/cssref/pr_grid-template-rows.php">W3schools - grid-template-rows</a><br><br>
<a href="https://codepen.io/origamid/pen/gRKpow/">Exemplo Codepen - grid-template-rows</a><br><br>
<br>
Grid explícita e grid implícita: Na explícita, especificamos a configuração da grid, na grid implícita as células da grid serão preenchidas automaticamente<br>
<br>
<br>
___________<br>
**Grid-auto-rows e grid-auto-columns**<br>
O grid-auto-rows propriedade define um tamanho para as linhas em um contêiner de grade. <br>
<a href="https://www.w3schools.com/cssref/pr_grid-auto-rows.php">W3schools - grid-auto-rows</a><br>
<a href="https://codepen.io/stephenyrkoo/pen/BwBKaz">Codepen - grid-auto-rows e grid-auto-columns</a><br>
<br>
<br>
<br>
___________<br>
**Grid-row-gap**<br>
A propriedade grid-row-gap define o tamanho do intervalo entre as linhas dos elementos da grade. A largura do intervalo pode ser especificada, separando as linhas usando um valor para grid-row-gap.<br>
<a href="https://www.w3docs.com/learn-css/grid-row-gap.html">W3Docs - grid-row-gap</a><br>
<a href="https://codepen.io/imbeshat7/pen/GRGxmKv">Codepen - grid-row-gap</a><br>
<br>
<br>
___________<br>
**Grid-gap**<br>
forma reduzida de usar o grid-row-gap, tanto em linhas como em colunas. Produz espaçamento entre elementos<br>
<a href="https://www.w3docs.com/learn-css%20/grid-gap.html">W3Docs - grid-gap</a><br>
<a href="https://codepen.io/aneesh-palamthodi/pen/dyxabZK">Codepen - grid-gap</a><br>
<br>
<br>
___________<br>
**Unidade FR**<br>
Esta unidade foi necessária criar para não ocorrer problemas, significa fração<br>
exemplo: grid-template-columns: repeat(3, 1fr); <br>
<a href="https://css-tricks.com/introduction-fr-css-unit/">Unidade FR, explicação - css-tricks</a><br>
<br>
<br>
___________<br>
**Alinhamento de conteúdo**<br>
Parecido com flexbox, tem a propriedade align-items, com as propriedades stretch, center, start, end<br>
Também a propriedade justify-items<br>
<a href="https://css-tricks.com/almanac/properties/j/justify-items/">Justify-items css-tricks</a><br>
<a href=""></a><br>
<br>
<br>
___________<br>
**Align-sef**<br>
Similar ao align-items, funciona para um item<br>
<a href="https://www.w3schools.com/cssref/css3_pr_align-self.php">W3Schools align-self</a><br>
<a href="https://codepen.io/rachelandrew/pen/KdKLLX">Codepen exemplo</a><br>
Melhor exemplo:<br>
<a href="https://codepen.io/amelieyeh/pen/KXmRxO">Codepen -exemplo 2</a>><br>
<br>
<br>
___________<br>
**Ocupando espaços no CSS grid (grid-column)**<br>
Adentrando na parte mais interessante. Grid-column é um abreviador para grid-column-start e grid-column-end. A propriedade grid-column especifica o tamanho e a localização de um item de grade em um layout de grade e é uma propriedade abreviada para as seguintes propriedades:(grid-column-start+grid-column-end)
<br>
<a href="https://www.w3schools.com/cssref/pr_grid-column.php">W3Schools - grid-column</a><br>
Aqui está o exemplo mais fácil de entender<br>
<a href="https://css-tricks.com/almanac/properties/g/grid-column/">Grid-column CSS-tricks</a><br>
Aqui está a imagem desenhada que explica a column do grid:<br>
<img src="https://i0.wp.com/css-tricks.com/wp-content/uploads/2022/10/s_5E600D44A3602E06FB6B7B59AD446BE1961B4B0D409EEEA69A28E839C5C65BD4_1662830734930_first-example.jpg?resize=805%2C288&ssl=1" weight="350" height="150"><br>
Exemplo Real, com grid, wrapper, onde a imagem se parece com um menu:<br>
<img src="github.com/Xaobin/CoursesLearn/blob/main/Grid/imgs/GridAula08-0215.png?raw=true" weight="600" height="400"><br>
<br>
<br>
___________<br>
**_**<br>
<br>
<a href=""></a><br>
<a href=""></a><br>
<br>
<br>
___________<br>
**_**<br>
<br>
<a href=""></a><br>
<a href=""></a><br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>