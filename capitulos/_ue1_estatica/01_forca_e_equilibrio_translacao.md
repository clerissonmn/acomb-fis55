---
layout: default
title: Força e equilíbrio de translação
nav_order: 1
CAP: 1
math: katex
toc: true
---

<!--
Conf. Iniciais
exi: contor dos exercicios resolvidos
 si: contador com numero da secao
ssi: contador com o numero da aubsecao
-->

{% assign  si = 0 %} 
{% assign ssi = 0 %} 
{% assign exi = 0 %}
{% assign figi = 0 %}

<!-- Fim Conf. Iniciais -->

# {{  page.CAP }}. Força e equilíbrio de translação

{: .no_toc }

## Sumário
{: .no_toc }

-   TOC
{: toc }

---

{% assign si = si | plus: 1 %}

## {{  page.CAP }}.{{ si }}. Definição de força

Dá-se o nome de força a qualquer interação entre corpos. Quando não
equilibradas, as forças atuantes no corpo podem deformá-lo ou alterar seu
comportamento, isto é, seu estado de movimento. É importante ressaltar que não
se pode limitar a ideia de força a apenas "esforço físico". Quando o corpo
humano executa uma força, isso implica em fazer um certo esforço; entretanto, o
conceito de força é mais abrangente, pois mesmo na ausência de interação humana,
dois objetos podem exercer força entre si. Por exemplo, o navio consegue flutuar pois a água faz uma força para cima. Por fim, uma força também pode ser aplicada sem o contato físico. A força da gravidade, por exemplo, puxa todos os corpos em direção ao chão sem que possamos ver esta interação.

A força é representada por uma seta chamada _vetor_. O tamanho (ou módulo) deste
vetor representa o valor da força enquanto que a sua orientação (para onde ele
aponta) representa a direção da força.

site.url: {{ site.url }}

site.baseurl: {{ site.baseurl }}

post.path: {{ post.path }}

page.path: {{ page.path }}

post.dir: {{ post.dir }}

page.dir: {{ page.dir }}

site.static_files {{ site.static_files }}

page.collection: {{ page.collection }}

path: {{ site.baseurl }}/capitulos/_{{ page.collection }}/fig_vetores.svg


![Vetores]({{ site.baseurl }}/capitulos/_{{ page.collection }}/fig_vetores.svg)

{% assign figi = figi | plus: 1 %}
**Fig {{ figi }}.** Vetores.

{: .note }
> No Sistema Internacional (SI) a unidade de medida de força é o Newton (N).


Algumas forças são provenientes de situações e agentes específicos e, por esse
motivo, recebem nomes especiais. A seguir serão descritas aquelas que possuem
particular importância.

{% assign si = si | plus: 1 %}

## {{  page.CAP }}.{{ si }}. Força Peso

Também conhecido como _Força Gravitacional_ ou _Força da Gravidade_, é a força
que puxa todos os corpos para o chão. Isaac Newton, em seu trabalho _Principia_,
propôs que essa força é oriunda da massa dos corpos isto é, todos os corpos que
possuem massa estão sujeitas ã força da gravidade mas somente aquelas massas que
são muito grandes é que produzem efeitos observáveis. Por esse motivo a força
gravitacional só é perceptível quando os corpos tem o tamanho comparável ao de
planetas. Podemos calcular a força peso da seguinte forma:

$$
\begin{equation}
P = M \times g
\end{equation}
$$

Em que $$M$$ é a massa do corpo e $$g = 10 m/s^2$$. $$g$$ é chamada de
_aceleração da gravidade_. Importante, neste momento, é apenas saber seu valor
numérico ($$10$$) e, posteriormente (na U.E.2) ficará mais claro seu significado
e sua unidade ($$m/s^2$$).

Dessa forma, pode-se entender que $$10N$$ corresponde ao peso de uma massa de
$$1kg$$ pois

$$
P = 1 \times 10 = 10 \, N
$$

Então chegamos a conclusão de que $$1N$$ de força equivale a carregar o peso de
uma massa de $$100g$$ (faça as contas).

{: .cuidado }

> Neste ponto podemos perceber que _massa_ e _peso_ são duas grandezas
> diferentes. A massa é a quantidade de matéria (quilogramas) no corpo e o peso
> é a **força** (em Newton) com que a gravidade puxa essa massa para o chão.
> Nesse contexto pode-se entender que uma balança, por exemplo, nao mede o
> _peso_ mas sim a _massa_ de um corpo.

{: .exemplo_resolvido-title } {% assign exi = exi | plus: 1 %}

> Exemplo Resolvido {{  page.CAP }}.{{ exi }}
>
> Durante um teste de carga um guindaste de bordo suspende uma caixa de 1 Ton
> (tonelada). Calcule qual o peso da caixa (em Newton) que cabo do guindaste
> está suportando.
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

{: .importante }

> É importante notar que

{% assign si = si | plus: 1 %}

## {{  page.CAP }}.{{ si }}. Força de Tração ($$F_T$$)

É a força a qual uma corda, cabo ou corrente (por exemplo), é submetida quando é
puxado por forças em suas extremidades. A tração sempre atua ao longo do eixo do
material e, falando de uma forma simples, ela "informa" qual o valor da força
que está sendo aplicada sobre a corda (cabo, ou correte, etc.).

Quando um guindaste, por exemplo, é usado para suspender cargas pesadas. A força
de tração é a quela força "sentida" pelo cabo do guindaste ao ser pendurada a
carga.

{: .exemplo_resolvido-title } {% assign exi = exi | plus: 1 %}

> Exemplo Resolvido {{  page.CAP }}.{{ exi }}
>
> Qual a força de tração sentida pelo cabo de aço no exemplo 1.01
>
> **Resposta**:
>
> O cabo do guindaste está suportando todo o peso da caixa, logo a força de
> tração nele também é $$10/,000 N$$.

{% assign ssi = ssi | plus: 1 %}

### {{  page.CAP }}.{{ si }}.{{ ssi }}. Carga de trabalho (CT) e Carga de Ruptura (CR)

A **Carga de Trabalho (CT)**, também conhecida como _Carga de Trabalho Segura_
(WLL - Working Load Limit), é a máxima carga que um cabo de aço, corrente, ou
qualquer equipamento de elevação pode suportar com segurança durante o uso
regular. Ela é calculada aplicando um fator de segurança à **Carga de Ruptura
(CR)**, que é a carga máxima que o material pode suportar antes de falhar ou
romper.

O **Fator de Segurança (FS)** é uma margem adicional incorporada para garantir a
segurança, considerando variáveis como desgaste, impactos e condições adversas e
geralmente é escrito na forma de uma proporção, número. Por exemplo, um fator
típico de segurança para aplicações maritmas é $$5$$, que é o mesmo que escrever
$$5:1$$ (lê-se 5 para 1).

{: .importante }

> Note que $$5:1$$, matematicamente, é o mesmo que escrever a fração
> $${1 \over 5}=0,2$$. Então um fator de segurança (FS) igual a $$5$$ quer dizer
> que a carga de trabalho (CT) segura é $$20\%$$ da carga de ruptura do cabo
> (CR) (veja o próximo exemplo resolvido).

Para calcular a CT devemos dividir a CR pelo fator de segurança.

$$

\begin{equation} \text{CT}={\text{CR} \over \text{FS}}, \end{equation}


$$

que é o mesmo que escrever

$$

\begin{equation} \text{CR} = \text{FS} \times \text{CT} \end{equation}


$$

{: .exemplo_resolvido-title } {% assign exi = exi | plus: 1 %}

> Exemplo Resolvido {{  page.CAP }}.{{ exi }}
>
> Por exemplo, se um cabo de aço tem uma carga de ruptura de $$10$$ toneladas
> força e um fator de segurança de $$5:1$$, qual deve ser sua carga de trabalho?
>
> **Resposta** A proporção de $$5:1$$ corresponde a um FS igual a $$5$$. Dessa
> forma carga de trabalho segura seria
>
> $$
> \text{CT}={10 \over 5}=2
> $$
>
> Logo a carga segura de trabalho seria por volta de $$2$$ toneladas força. $$

{% assign si = si | plus: 1 %}

## {{  page.CAP }}.{{ si }}. Força de Atrito

É a força que tende a dificultar o movimento de arrastar dois corpos quando suas
superfícies estiverem em contato físico. De forma mais técnica, diz-se que a
força de atrito é a força que se opõe ao movimento relativo entre duas
superfícies em contato. Sabe-se, por experiência, que esta força depende do tipo
de material e do quanto os corpos estão sendo pressionados uns contra os outros.

Matematicamente, os diferentes tipos de material são modelados por um número
chamado _coeficiente de atrito_ ($$\mu$$). O atrito pode ser _estático_ (quando
dificulta o início do movimento) e _dinâmico_ (quando dificulta o andamento do
movimento). Todas as superfícies apresentam dois coeficientes de atrito:
coeficiente de atrito estático ($$\mu_E$$) e coeficiente de atrito dinâmico
($$\mu_D$$). É por esse motivo que começar a arrastar uma caixa pesada é mais
difícil do que mantê-la em movimento após iniciado o movimento.

{: .note }

> Quando uma superfície está molhada seu coeficiente de atrito diminui.

A _força normal_ ($$N$$) é aquela que informa com que força a superficie esta
sendo pressionada, logo, para calcular a $$F_{fat}$$ basta fazer:

$$
F_{fat} = \mu \times N.
$$

Em algumas situações do dia-a-dia o atrito é indesejavel, como nas partes móveis
de um motor, por exemplo, que precisam ser lubrificadas para que o atrito seja
reduzido e, assim, sofrer menos aquecimento. Por outro lado, há situações em que
o atrito é importante. Só podemos andar ou um carro só consegue fazer curvas se
existir atrito com o chão.

{: .exemplo_resolvido-title } {% assign exi = exi | plus: 1 %}

> Exemplo Resolvido {{  page.CAP }}.{{ exi }}
>
> Uma caixa de madeira contém uma máquina de $$100kg$$ e está sobre um piso de
> metal. Sabendo que o coeficiente de atrito estático máximo entre o piso e a
> madeira é $$\mu_E = 0.5$$ e o coeficiente de atrito dinâmico é
> $$\mu_D = 0.2$$. Com base nessas informações, responda:
>
> a) Qual o valor do peso da caixa?
>
> b) Qual o valor da força normal?
>
> c) Qual a força que deve ser aplicada na caixa para que ela inicie o
> movimento?
>
> d) Qual o valor da força que deve ser aplicada para que o movimento seja
> mantida?
>
> e) Um cabo cuja carga de ruptura (CR) é $$200\,N$$ seria uma boa opção para
> arrastar horizontalmente essa caixa?
>
> f) Se o oficial de maquinas determina que o fator de segurança para o cabo em
> questão é $$5$$. Determine qual a **carga de ruptura** do cabo se a **carga de
> trabalho** for a máxima exigida pela caixa.
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
> c) Para iniciar o movimento é necessário vencer a força de **atrito
> estático**, cujo coeficiente é $$\mu_E = 0.5$$. Esta força é calculada por
>
> $$ F\_{fat\,\text{estático}} = \mu_E \times N$$
>
> $$ F\_{fat\,\text{estático}} = 0.5 \times 1000$$
>
> $$F\_{fat\,\text{estático}} = 5\,000\,N$$
>
> d) Para o movimento ser mantido é preciso vencer a força de **atrito
> dinâmico**, cujo coeficiente é $$\mu_D = 0.2$$, que é calculada por
>
> $$F_{fat\text{ dinâmico}} = \mu_D \times N$$
>
> $$ F_{fat\text{ dinâmico}} = 0.2 \times 1\,000$$
>
> $$ F_{fat\text{ dinâmico}} = 200\,N$$
>
> e) A força máxima que o cabo suporta $$200\,N$$ então ele estaria no valor
> limite durante o movimento. Alem disso, a força necessária para iniciar o
> movimento deveria ser de, ao menos, $$300\,N$$ o que seria maior do que a
> carga de ruptura. Logo este cabo não seria uma boa escolha.
>
> f) Se o **fator de segurança** (FS) é $$5$$ e a **carga de trabalho** é
> $$300\,N$$, o cabo deve ter uma **carga de ruptura** (CR) de:
>
> $$
> \text{CR} = \text{CT} \times \text{FS}
> $$
>
> Então o cabo precisa ter uma carga ee ruptura de ao menos $$1\,500\,N$$.

<!--
{% assign si = si | plus: 1 %}
## {{  page.CAP }}.{{ si }}. Força Elástica

A força elástica é a força exercida por um material elástico, como uma mola ou
um elástico, quando ele é deformado. Essa força obedece à Lei de Hooke, que
afirma que a força é proporcional à deformação (F = -kx, onde k é a constante
elástica e x é a deformação).

Os amortecedores em um sistema de suspensão de um motor marinho usam molas para
absorver os choques e vibrações. Quando o motor está em funcionamento, as molas
se deformam para absorver a energia dos movimentos, exercendo uma força elástica
que ajuda a manter a estabilidade do motor e a reduzir o desgaste dos
componentes.
-->

{% assign si = si | plus: 1 %}

## {{  page.CAP }}.{{ si }}. Força Resultante

Ao se aplicar **uma única força** sobre o corpo, a intuição nos diz que o corpo
tende a se movimentar para o sentido desta força. O que está correto. contudo
se forem forem aplicadas _mais de uma força_ no mesmo objeto, a análise ficará
menos intuitiva. Nesse caso o movimento do
corpo depende da **Força Resultante** entre elas.

É importante entender que a força resultante **não é a maior força** mas sim a
**combinação de todas as forças, levando em consideração seus módulos e
orientações**. Ou seja, ela é a **soma vetorial** de todas as forças que atuam
sobre um corpo e, por esse motivo, o cálculo possui suas regras especificas.

Do ponto de vista matemático, é imperativo utilizar o **formalismo de vetores**
mas como se está interessado em encontrar as forças nas direções horizontal e
vertical em separado, este texto seguirá uma abordagem própria e mais
simplificada para as regras de vetores, explicada a seguir.

{: .definicao-title }
> Regras
>
> As forças que atuam **para a direita** (sentido positivo de $$x$$), recebem o
> **sinal de positivo** ($$+$$), enquanto que as forças que atuam **no sentido
> contrário** recebem o **sinal de negativo** ($$-$$).
>
> Da mesma forma, as forças que atuam **para cima** (sentido positivo de $$y$$),
> recebem o **sinal de positivo** ($$+$$), enquanto que as forças que atuam no
> **sentido contrário** recebem o **sinal de negativo** ($$-$$).
>
> A força resultante em cada eixo ($$x$$ ou $$y$$) é a soma, considerando o sinal, de todas as forças atuantes neste eixo. Isto é chamamdo de soma algébrica. Matematicamente
> temos
>
> $$
> \begin{equation}
> F_{Rx} = F_{x1} + F_{x2} +\,\text{...}
> \end{equation}
> $$
>
> e
>
> $$
> \begin{equation}
> F_{Ry} = F_{y1} + F_{y2} +\,\text{...}
> \end{equation}
> $$

A seguir serão apresentados exemplo para que se possa apreender o uso e o
objetivo desta convenção no cálculo das forças resultantes.

{: .exemplo_resolvido-title } {% assign exi = exi | plus: 1 %}

> Exemplo Resolvido {{  page.CAP }}.{{ exi }}
>
> (Texto)
>
> **Solução**
>
> (Texto)

{: .exemplo_resolvido-title } {% assign exi = exi | plus: 1 %}

> Exemplo Resolvido {{  page.CAP }}.{{ exi }}
>
> (Texto)
>
> **Solução**
>
> (Texto)

{: .exemplo_resolvido-title } {% assign exi = exi | plus: 1 %}

> Exemplo Resolvido {{  page.CAP }}.{{ exi }}
>
> (Texto)
>
> **Solução**
>
> (Texto)

{: .exemplo_resolvido-title } {% assign exi = exi | plus: 1 %}

> Exemplo Resolvido {{  page.CAP }}.{{ exi }}
>
> (Texto)
>
> **Solução**
>
> (Texto)

{: .exemplo_resolvido-title } {% assign exi = exi | plus: 1 %}

> Exemplo Resolvido {{  page.CAP }}.{{ exi }}
>
> (Texto)
>
> **Solução**
>
> (Texto)

{: .exemplo_resolvido-title } {% assign exi = exi | plus: 1 %}

> Exemplo Resolvido {{  page.CAP }}.{{ exi }}
>
> (Texto)
>
> **Solução**
>
> (Texto)

Todas as forças mostradas nesta seção estão alinhas com algum eixo ($$x$$ ou
$$y$$). Quando uma ou mais forças não estão orientadas para algum eixo, se faz
necessário a decomposição.

{% assign ssi = ssi | plus: 1 %}

<<<<<<< HEAD
## {{  page.CAP }}.{{ si }}.{{ ssi }} Decomposição de forças
=======
### {{ page.UE }}.{{ si }}.{{ ssi }} Decomposição de forças
>>>>>>> 717dec2489ba18a407fddf3a70d2ffb3c0cea75f

A decomposição de forças é o processo de dividir uma força em componentes
perpendiculares, geralmente nas direções horizontais e verticais (eixos $$x$$ e
$$y$$). Isso é útil para simplificar a análise de problemas com forças que atuam
em diferentes direções.

A decomposição é feita em 3 passos:

1. Identificar qual o ângulo de referência. Se o ângulo não estiver tocando em
   um dos eixos, deve-se fazer a projeção do ângulo para um dos eixos;
2. A partir do ângulo, nomear as componentes de interesse. Por exemplo, $$F_x$$ e $$F_y$$;
3. A partir do ângulo, decidir qual a componente seno e qual a componente cosseno.

{: .exemplo_resolvido-title } {% assign exi = exi | plus: 1 %}

> Exemplo Resolvido {{  page.CAP }}.{{ exi }}
>
> Imagine que uma máquina a bordo de um navio está sujeita a uma força $$F$$ de
> $$5\,000\,N$$ que atua em um ângulo de $$30^{\circ}$$ em relação à horizontal
> (eixo $$x$$). Faça a decomposição desta força.
>
> **Solução**
>
> 

{% assign si = si | plus: 1 %}

## {{  page.CAP }}.{{ si }}. Equilíbrio de Translação

{: .definicao }
> Equilíbrio de translação ocorre quando **a Força Resultante é Zero**.

Nesse caso o corpo não muda seu comportamento, ou seja, se está parado, ele continuará parado. Note que o corpo pode estar em equilíbrio em uma direção mas, ao mesmo tempo, não estar em outra. Uma mesa sendo arrastada, por exemplo, está em equilíbrio em relação à vertical mas fora do equilíbrio na horizontal. Manter o equilíbrio de translação evita movimentos indesejados das máquinas e equipamentos, que podem causar danos ou acidentes.

{{: . importante }}
> A palavra translação significa que o corpo arrasta sem rotacionar. No outro capítulo será analisada a rotação.

Muitas vezes saber préviamente que o corpo está em equilíbrio é útil para determinar forças desconhecidas nas situações. Você conseguiria dizer quais os exemplos da seção anterior estão em equilíbrio?

Um navio atracado está sujeito a forças de tração dos cabos de amarração e à força de da água que o mantém flutuando. Podemos dizer que, de certa forma, o navio  Para que o navio permaneça em equilíbrio pois o peso do navio está equilibrado pela força da água e ele nao se afasta do cais pois está sendo puxado pelas trações nas cordas.