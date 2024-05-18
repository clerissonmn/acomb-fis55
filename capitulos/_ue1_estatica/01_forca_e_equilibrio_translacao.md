---
layout: default
title: Força e equilíbrio de translação
nav_order: 1
math: katex
---

# 1. Força e equilíbrio de translação

Dá-se o nome de força a qualquer interação entre corpos. Quando não equilibradas, as forças atuantes no corpo podem deformá-lo ou alterar seu comportamento, isto é, seu estado de movimento. É importante ressaltar que não se pode limitar a ideia de força a apenas "esforço físico". Quando o corpo humano executa uma força, isso implica em fazer um certo esforço; entretanto, o conceito de força é mais abrangente, pois mesmo na ausência de interação humana, dois objetos podem exercer força entre si. Por exemplo, uma caixa está efetivamente aplicando força (tracionando) no cabo do guindaste que a está levantando. Por fim, uma força também pode ser aplicada sem o contato físico. No exemplo anterior, a força da gravidade, por sua vez, está aplicando força no caixote, já que está puxando o mesmo em direção ao chão.

{: .unidades }

> No Sistema Internacional (SI) a unidade de medida é o Newton (N). 

{: . importante-title }

> Importante
> 
> Existem outras unidades de medida de força que não estão no S.I. mas que são comuns em situações a bordo ou em terra:
> 
> - _Quiligrama-força (kgf)_: Equivale ao peso (veja abaixo
> 
> -
> 
> - _dyna(dyn)_ que não estão no _SI_. O instrumento de medida de força é o Dinamômetro.


## 1.1 Forças típicas
 
 Algumas forças são provenientes de situações e agentes específicos e, por esse motivo, recebem nomes especiais. A seguir serão descritas aquelas que possuem particular importância para o presente curso.
 
### 1.1.1 Peso
 
 Também conhecido como _Força Gravitacional_ ou _Força da Gravidade_, é a força que puxa todos os corpos para o chão. Isaac Newton, em seu trabalho _Principia_, propôs que essa força é oriunda da massa dos corpos _i.e_, todos os corpos que possuem massa apresentam força da gravidade mas somente aquelas massas que são muito grandes é que produzem efeitos observáveis. Por esse motivo a força gravitacional só é perceptível qual os corpos tem o tamanho comparável ao de planetas. Numericamente podemos calcular a força peso da seguinte forma:
 
$$
\begin{equation}
P = M \times g
\end{equation}
$$
 
em que $$M$$ é a massa do corpo e  $$g = 10 m/s^2$$. $$g$$ é chamada de _aceleração da gravidade_. Importante, neste momento, é apenas saber seu valor numérico ($$10$$) e, posteriormente (na U.E.2) ficará mais claro seu significado e sua unidade ($$m/s^2$$).

{: .exemplo_resolvido-title }
> Exemplo Resolvido 1.01
> 
> Durante um teste de carga um guindaste de bordo suspende uma caixa de 1 Ton (tonelada). Calcule qual o peso da caixa (em Newton) que cabo do guindaste está suportando.
>
> **Resposta**
>
> A massa da caixa é $$M = 1 \text{ton} = 1\,000 kg$$. 
> 
> Dessa forma o peso é calculado fazendo 
>
> $$P = M \times g$$
> 
> $$P = 1\,000 \times 10$$
> 
> $$P = 10\,000 N$$

### Tração

É a força a qual uma corda, cabo ou corrente (por exemplo), é submetida quando é puxado por forças em suas extremidades. Essa força sempre atua ao longo do eixo do material e, de uma forma simples, "informa" qual o valor da força que está sendo aplicada sobre a corda (cabo, ou correte, etc.).

Quando um guindaste, por exemplo, é usado para suspender cargas pesadas. A força de tração é a quela força "sentida" pelo cabo do guindaste ao ser pendurada esta carga. 


{: .exemplo_resolvido-title }
> Exemplo Resolvido 1.02
>
> Qual a força de tração sentida pelo cabo de aço no exemplo abterior (1.01)?
> 
> **Resposta**:
>
> O cabo do guindaste está suportando todo o peso da Caixa, logo a força de tração neste também é $$10/,000 N$$.

### Normal

É a força de reação que uma superfície exerce sobre um objeto que está em contato com ela, ou seja,  de forma análoga à força de tração, a força Normal é aquela que informa o quanto se está "apertando" a superfície. Importante defininir que essa força é sempre perpendicular à superfície.

Como exemplo pode-se tomar um motor de propulsão está montado em uma plataforma de metal dentro da casa de máquinas. A força normal é a força que a plataforma exerce sobre o motor, suportando seu peso. Se o motor pesa 5000 N, a força normal que a plataforma exerce sobre o motor é também de 5000 N.

### Atrito
É a força que tende a dificultar o movimento de arrastar dos corpos ou superfícies. De forma mais técnica, diz-se que a força de atrito é a força que se opõe ao movimento relativo entre duas superfícies em contato. O atrito pode ser estático (dificultando o início do movimento) ou cinético (dificultando o movimento).
 
O cálculo da força de atrito ($$f{fat}$$) é feito multiplicando a força normal ($$N$$) pelo coeficiente de atrito ($$\mu$$), ou seja, 
 
 $$f_{fat} = \mu \times N $$

Algumas vezes o atrito é interessante, outras vezes não. Por exemplo [.......]

Exemplo Prático:
Ao realizar a manutenção de um motor, o oficial de máquinas precisa desmontar partes que estão aparafusadas. O atrito entre as roscas do parafuso e a peça de metal impede que o parafuso se mova facilmente. Para soltar o parafuso, o oficial deve aplicar uma força maior para vencer o atrito estático.
### Elástica
 
 A força elástica é a força exercida por um material elástico, como uma mola ou um elástico, quando ele é deformado. Essa força obedece à Lei de Hooke, que afirma que a força é proporcional à deformação (F = -kx, onde k é a constante elástica e x é a deformação).

Os amortecedores em um sistema de suspensão de um motor marinho usam molas para absorver os choques e vibrações. Quando o motor está em funcionamento, as molas se deformam para absorver a energia dos movimentos, exercendo uma força elástica que ajuda a manter a estabilidade do motor e a reduzir o desgaste dos componentes.
 
## Decomposição de forças
 A decomposição de forças é o processo de dividir uma força em componentes perpendiculares, geralmente em direções horizontais e verticais. Isso é útil para simplificar a análise de forças que atuam em diferentes direções.

Exemplo Prático:
Imagine que uma máquina a bordo de um navio está sujeita a uma força 
𝐹
F de 5000 N que atua em um ângulo de 30° em relação à horizontal. O oficial de máquinas precisa decompor essa força em componentes horizontal (
𝐹
𝑥
F 
x
​
 ) e vertical (
𝐹
𝑦
F 
y
​
 ).
 

## Força Resultante

 A força resultante é a soma vetorial de todas as forças atuando sobre um corpo. Para que um corpo esteja em equilíbrio translacional, a força resultante deve ser zero.

Exemplo Prático:
Imagine um navio atracado com duas amarras: uma força de 5000 N puxando o navio para a direita e outra de 5000 N puxando-o para a esquerda. A força resultante é zero, mantendo o navio em equilíbrio translacional.

Quando as forças atuantes no corpo estão nas duas direções ($x$ e $y$), o cálculo da força resultante deve ser feito de forma separada. Assim encontraremos duas respostas: uma força resultante em $x$ ($F{R_x}$) e outra em $y$ ($F{R_y}$). Se uma ou mais forças não estiverem alinhadas com $x$ ou $y$, deve-se fazer a decomposição.

 
## Equilíbrio de Translação

O equilíbrio de translação ocorre quando a soma vetorial de todas as forças atuando sobre um corpo é zero, resultando em um estado onde o corpo não acelera linearmente. Em outras palavras, para um corpo estar em equilíbrio de translação, ele deve estar em repouso ou se movendo com velocidade constante em linha reta.
Para um oficial de máquinas, compreender o equilíbrio de translação é fundamental para garantir a segurança e a eficiência das operações a bordo de um navio. Manter o equilíbrio de translação evita movimentos indesejados das máquinas e equipamentos, que podem causar danos ou acidentes.
Considere um motor de propulsão montado em uma base dentro da casa de máquinas. O peso do motor (força devido à gravidade) é 5000 N e é equilibrado por forças normais de reação da base. Para que o motor esteja em equilíbrio de translação, a soma das forças verticais deve ser zero.

Peso do motor (força para baixo): 5000 N
Força normal da base (força para cima): 5000 N
Como:
∑
𝐹
𝑦
=
5000
 
N
(
𝑝
𝑎
𝑟
𝑎
𝑐
𝑖
𝑚
𝑎
)
+
(
−
5000
 
N
(
𝑝
𝑎
𝑟
𝑎
𝑏
𝑎
𝑖
𝑥
𝑜
)
)
=
0
∑F 
y
​
 =5000N(paracima)+(−5000N(parabaixo))=0

O motor está em equilíbrio de translação porque as forças se cancelam, mantendo-o em repouso.

Exemplo 2: Navio Atracado
Um navio atracado está sujeito a forças de tração dos cabos de amarração e à força de empuxo da água. Para que o navio permaneça em equilíbrio de translação, a soma das forças horizontais e verticais deve ser zero.

Força de tração dos cabos (F1 e F2) atua puxando o navio em direções opostas.
Força de empuxo da água contrabalança o peso do navio.
Suponha que:

F1 (tracionando o navio para a direita) = 10000 N
F2 (tracionando o navio para a esquerda) = 10000 N
Peso do navio = 500000 N (para baixo)
Empuxo da água = 500000 N (para cima)

Para um oficial de máquinas, garantir que todos os sistemas estejam em equilíbrio de translação é crucial para evitar movimentos indesejados que podem levar a falhas mecânicas ou acidentes. Isso inclui verificar a correta instalação e fixação de máquinas e equipamentos, monitorar as forças atuantes durante a operação e manutenção, e assegurar que as cargas estejam distribuídas de forma balanceada.

Compreender e aplicar o conceito de equilíbrio de translação ajuda a manter a integridade estrutural e a segurança operacional a bordo de um navio.

