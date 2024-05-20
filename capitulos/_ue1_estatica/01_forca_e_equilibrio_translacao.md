---
layout: default
title: Força e equilíbrio de translação
nav_order: 1
math: katex
toc: true
---

# Força e equilíbrio de translação
{: .no_toc }

## SUMÁRIO
{: .no_toc .text-delta }

1.TOC
{:toc}

--- 

## Definição de força
Dá-se o nome de força a qualquer interação entre corpos. Quando não equilibradas, as forças atuantes no corpo podem deformá-lo ou alterar seu comportamento, isto é, seu estado de movimento. É importante ressaltar que não se pode limitar a ideia de força a apenas "esforço físico". Quando o corpo humano executa uma força, isso implica em fazer um certo esforço; entretanto, o conceito de força é mais abrangente, pois mesmo na ausência de interação humana, dois objetos podem exercer força entre si. Por exemplo, uma caixa está efetivamente aplicando força (tracionando) no cabo do guindaste que a está levantando. Por fim, uma força também pode ser aplicada sem o contato físico. No exemplo anterior, a força da gravidade, por sua vez, está aplicando força no caixote, já que está puxando o mesmo em direção ao chão.

{: .note }

> No Sistema Internacional (SI) a unidade de medida de força é o Newton (N).
 
 Algumas forças são provenientes de situações e agentes específicos e, por esse motivo, recebem nomes especiais. A seguir serão descritas aquelas que possuem particular importância.
 
## Força Peso
 
 Também conhecido como _Força Gravitacional_ ou _Força da Gravidade_, é a força que puxa todos os corpos para o chão. Isaac Newton, em seu trabalho _Principia_, propôs que essa força é oriunda da massa dos corpos isto é, todos os corpos que possuem massa estão sujeitas ã força da gravidade mas somente aquelas massas que são muito grandes é que produzem efeitos observáveis. Por esse motivo a força gravitacional só é perceptível quando os corpos tem o tamanho comparável ao de planetas. Podemos calcular a força peso da seguinte forma:
 
$$
\begin{equation}
P = M \times g
\end{equation}
$$
 
Em que $$M$$ é a massa do corpo e  $$g = 10 m/s^2$$. $$g$$ é chamada de _aceleração da gravidade_. Importante, neste momento, é apenas saber seu valor numérico ($$10$$) e, posteriormente (na U.E.2) ficará mais claro seu significado e sua unidade ($$m/s^2$$).

Dessa forma, pode-se entender que $$10N$$ corresponde ao peso de uma massa de $$1kg$$ pois 

$$
P = 1 \times 10 = 10 \, N
$$.

Então chegamos a conclusão de que $$1N$$ de força equivale a carregar o peso de uma massa de $$100g$$ (faça as contas).

{: .cuidado }
> Neste ponto podemos perceber que _massa_ e _peso_ são duas grandezas diferentes. A massa é a quantidade de matéria (quilogramas) no corpo e o peso é a **força** (em Newton) com que a gravidade puxa essa massa para o chão. Nesse contexto pode-se entender que uma balança, por exemplo, nao mede o _peso_ mas sim a _massa_ de um corpo.


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


## Força de Tração ($$F_T$$)

É a força a qual uma corda, cabo ou corrente (por exemplo), é submetida quando é puxado por forças em suas extremidades. A tração sempre atua ao longo do eixo do material e, falando de uma forma simples, ela "informa" qual o valor da força que está sendo aplicada sobre a corda (cabo, ou correte, etc.).

Quando um guindaste, por exemplo, é usado para suspender cargas pesadas. A força de tração é a quela força "sentida" pelo cabo do guindaste ao ser pendurada a carga. 


{: .exemplo_resolvido-title }
> Exemplo Resolvido 1.02
>
> Qual a força de tração sentida pelo cabo de aço no exemplo 1.01
> 
> **Resposta**:
>
> O cabo do guindaste está suportando todo o peso da caixa, logo a força de tração nele também é $$10/,000 N$$.


### Carga de trabalho (CT) e Carga de Ruptura (CR)

A **Carga de Trabalho (CT)**, também conhecida como _Carga de Trabalho Segura_ (WLL - Working Load Limit), é a máxima carga que um cabo de aço, corrente, ou qualquer equipamento de elevação pode suportar com segurança durante o uso regular. Ela é calculada aplicando um fator de segurança à **Carga de Ruptura (CR)**, que é a carga máxima que o material pode suportar antes de falhar ou romper. 

O **Fator de Segurança (FS)** é uma margem adicional incorporada para garantir a segurança, considerando variáveis como desgaste, impactos e condições adversas e geralmente é escrito na forma de uma proporção, número. Por exemplo, um fator típico de segurança para aplicações maritmas é $$5$$, que é o mesmo que escrever $$5:1$$.

{: .importante }
> Note que $$5:1$$, matematicamente, é o mesmo que escrever a fração $${1 \over 5}=0,2$$. Então um fator de segurança (FS) igual a $$5$$ quer dizer que a carga de trabalho (CT) segura é $$20\%$$ da carga de ruptura do cabo (CR) (veja o próximo exemplo resolvido).

Para calcular a CT devemos dividir a CR pelo fator de segurança. 

$$
\begin{equation}
\text{CT}={\text{CR} \over \text{FS}},
\end{equation}
$$

que é o mesmo que escrever

$$
\begin{equation}
\text{CR} = \text{FS} \times \text{CT}
\end{equation}
$$

{: .exemplo_resolvido-title }
> Exemplo Resolvido 1.03
>
> Por exemplo, se um cabo de aço tem uma carga de ruptura de $$10$$ toneladas força e um fator de segurança de $$5:1$$, qual deve ser sua carga de trabalho?
> 
> **Resposta**
> A proporção de $$5:1$$ corresponde a um FS igual a $$5$$. Dessa forma carga de trabalho segura seria
>
> $$
> \text{CT}={10 \over 5}=2
> $$
>
> Logo a carga segura de trabalho seria por volta de $$2$$ toneladas força.

## Força Normal ($$F_N$$)

É a força de reação que uma superfície exerce sobre um objeto que está em contato com ela, ou seja,  de forma análoga à força de tração, a força Normal é aquela que informa o quanto se está "apertando" a superfície. Importante ressaltar que essa força é sempre perpendicular à superfície, ou seja, sempre forma $$90^{\circ}$$.

{: .exemplo_resolvido-title }
> Exemplo Resolvido 1.03
> 
> Um motor está montado em uma plataforma de metal dentro da casa de máquinas. A força normal. Calcule a força que a plataforma exerce sobre o motor.
>
> **Resposta**
> Se o motor pesa $$5\,000 N$$, a força normal que a plataforma exerce sobre o motor é também de $$5\,000 N$$.

{: .note }
> Em problemas que envolvam balanças, a leitura da balança é igual a força normal.

## Força de Atrito
É a força que tende a dificultar o movimento de arrastar dois corpos quando suas superfícies estiverem em contato físico. De forma mais técnica, diz-se que a força de atrito é a força que se opõe ao movimento relativo entre duas superfícies em contato. Sabe-se, por experiência, que esta força depende do tipo de material e do quanto os corpos estão sendo pressionados uns contra os outros. 

Matematicamente, os diferentes tipos de material são modelados por um número chamado _coeficiente de atrito_ ($$\mu$$). O atrito pode ser _estático_ (quando dificulta o início do movimento) e _dinâmico_ (quando dificulta o andamento do movimento). Todas as superfícies apresentam dois coeficientes de atrito: coeficiente de atrito estático ($$\mu_E$$) e coeficiente de atrito dinâmico ($$\mu_D$$). É por esse motivo que começar a arrastar uma caixa pesada é mais difícil do que mantê-la em movimento após iniciado o movimento.

{: .note }
> Quando uma superfície está molhada seu coeficiente de atrito diminui.

A _força normal_ ($$N$$) é aquela que informa com que força a superficie esta sendo pressionada, logo, para calcular a $$F_{fat}$$ basta fazer:
 
 $$
 F_{fat} = \mu \times N.
 $$

Em algumas situações do dia-a-dia o atrito é indesejavel, como nas partes móveis de um motor, por exemplo, que precisam ser lubrificadas para que o atrito seja reduzido e, assim, sofrer menos aquecimento. Por outro lado, há situações em que o atrito é importante. Só podemos andar ou um carro só consegue fazer curvas se existir atrito com o chão.

{: .exemplo_resolvido-title }
> Exemplo Resolvido 1.05
>
> Uma caixa de madeira contém uma máquina de $$100kg$$ e está sobre um piso de metal. Sabendo que o coeficiente de atrito estático máximo entre o piso e a madeira é $$\mu_E = 0.5$$ e o coeficiente de atrito dinâmico é $$\mu_D = 0.2$$. Com base nessas informações, responda:
>
> a) Qual o valor do peso da caixa?
>
> b) Qual o valor da força normal?
>
> c) Qual a força que deve ser aplicada na caixa para que ela inicie o movimento?
>
> d) Qual o valor da força que deve ser aplicada para que o movimento seja mantida?
>
> e) Um cabo cuja carga de ruptura (CR) é $$200\,N$$ seria uma boa opção para arrastar horizontalmente essa caixa?
>
> f) Se o oficial de maquinas determina que o fator de segurança para o cabo em questão é $$5$$. Determine qual a **carga de ruptura** do cabo se a **carga de trabalho** for a máxima exigida pela caixa.
>
> **Solução**
> 
> a) O peso da caixa é
> 
> $$
> P = M \times g
> $$
>
> $$
> P = 100 \times 10
> $$
>
> $$
> P=1\,000 N
> $$
>
> b) Como a caixa está sobre o piso, a força Normal é igual ao peso, oh seja,
>
> $$
> F_N = 1\,000\,N
> $$
>
>
> c) Para iniciar o movimento é necessário vencer a força de **atrito estático**, cujo coeficiente é $$\mu_E = 0.5$$. Esta força é calculada por
>
> $$ F_{fat estático} = \mu_E \times N$$
> 
> $$ F_{fat estático} = 0.5 \times 1000$$
> 
> $$F_{fat estático} = 5\,000\,N$$
>
> d) Para o movimento ser mantido é preciso vencer a força de **atrito dinâmico**, cujo coeficiente é $$\mu_D = 0.2$$, que é calculada por
>
> $$F_{fat\text{ dinâmico}} = \mu_D \times N$$
> 
> $$ F_{fat\text{ dinâmico}} = 0.2 \times 1000$$
>
> $$ F_{fat\text{ dinâmico}} = 200\,N$$
>
> e) A força máxima que o cabo suporta $$200\,N$$ então ele estaria no valor limite durante o movimento. Alem disso, a força necessária para iniciar o movimento deveria ser de, ao menos, $$300\,N$$ o que seria maior do que a carga de ruptura. Logo este cabo não seria uma boa escolha.
>
> f) Se o **fator de segurança** (FS) é $$5$$ e a **carga de trabalho** é $$300\N$$, o cabo deve ter uma **carga de ruptura** (CR) de:
> 
> $$
> \text{CR} = \text{CT} \times \text{FS}
> $$
>
> Então o cabo precisa ter uma carga ee ruptura de ao menos $$1\,500\,N$$.

## Força Elástica
 
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

