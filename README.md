# Sierpinski
Implementação do fractal de Sierpinski em D3 JS

Fractais são estruturas autosimilares e repetidas em escalas menores. A partir de regras simples, é possível fazer desenhos extremamente complexos.

É possível fazer fractais só com triângulos e retângulos, no VBA.

![](https://ferramentasexcelvba.files.wordpress.com/2022/07/fractais01.png?w=1024)

Para criar um retângulo no VBA, basta um código como o seguinte, definindo a posição (x,y), a largura e altura do retângulo.

ActiveSheet.Shapes.AddShape(msoShapeRectangle, x, y, largura, altura)

O fractal começa com um quadrado maior. Imagine dividir o quadrado em 9 quadrados menores. O do meio, é só traçar o contorno, e os demais, jogamos de novo na recursão.


![](https://ferramentasexcelvba.files.wordpress.com/2022/07/fractais02.png)

A segunda rodada fica assim. Para cada sub-quadrado, aplicar a mesma regra numa escala menor.


![](https://ferramentasexcelvba.files.wordpress.com/2022/07/fractais03.png)

A terceira rodada de iteração fica assim.


![](https://ferramentasexcelvba.files.wordpress.com/2022/07/fractais04.png)

Podemos continuar até o computador aguentar (o número de elementos cresce exponencialmente).


![](https://ferramentasexcelvba.files.wordpress.com/2022/07/fractais05.png)

Vide versão Excel VBA, com código aberto para quem quiser estudar. É necessário ativar macros para rodar. Código e planilha no Github. [https://github.com/asgunzi/Sierpinski](https://github.com/asgunzi/Sierpinski)

O Excel não é muito bom em elementos gráficos. A biblioteca D3 do Javascript performa melhor.

Versão Javascript – D3 em:

[https://asgunzi.github.io/Sierpinski/Sierpinski.html](https://asgunzi.github.io/Sierpinski/Sierpinski.html)

e também em:

(https://asgunzi.github.io/Sierpinski/SierpinskiQuadrado.html)[https://asgunzi.github.io/Sierpinski/SierpinskiQuadrado.html]



