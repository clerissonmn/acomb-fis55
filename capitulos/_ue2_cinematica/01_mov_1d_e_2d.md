---
layout: default
title: Movimento 1D e 2D
nav_order: 1
math: katex
---

# Movimento 1D e 2D de uma partícula

O objetivo principal da cinemática é fazer a previsão do comportamento futuro dos corpos por meio da relação entre sas _grandezas cinemáticas_, a saber, _posição_, _velocidade_ e _aceleração_. Por exemplo, se tomemos (hipoteticamente) o movimento de aproximação do navio para iniciar uma manobra de atracação. Considere que inicialmente ele está viajando a uma velocidade de 100 nós e deseja-se reduzi-la a um valor de, por exemplo, 10 nós. Ao saber o valor da _aceleração_ (nesse caso, a taxa de diminuição da velocidade) pode-se calcular em _quanto tempo_ esta redução acontecerá e, além disso, pode-se estimar quantas milhas nauticas ele percorrerá (_espaço_ percorrido) durante esse movimento. Dessa forma pode-se prever qual a distância segura para o início da manobra.

Em geral, os _corpos rígidos_ (o navio no exemplo anterior) estão livre para se mover em todas as direções, executando _trajetórias_ que podem rapidamente se tornar complicadas de analisar. Para simplificar o estudo costuma-se a fazer algumas aproximações como considerar o _móvel_ sendo um _ponto material_ e adotar, em primeiro momento, o seu estudo apenas em uma _linha reta (1D)_, ou seja em apenas um dos _eixos do plano cartesiano_ ($$x$$, $$y$$ ou $$z$$). Daí então serem analisadas o movimento nas outras dimensões de forma separada e gradativamente acrescentadas outras informações como as dimensões dos móveis e a posição e rotação com respeito ao seu centro de massa. É dessa forma que conseguimos estudar o movimento geral de um _corpo extenso_.

A seguir estão as conceituações técnicas dos termos utilizados no parágrafo anterior. de posse dessas definições você, aluno, é encorajado a lê-lo novamente (quantas vezes necessárias) até se ter apreendido todo o sentido.

<dl>
<dt>Móvel</dt>
<dd>De um modo geral, dá-se o nome de móvel a qualquer corpo em movimento.</dd>
<dt>Partícula</dt> 
<dd>Também chamado ponto material, é qualquer corpo cujas dimensões geométricas (seu famanho) sejam desprezíveis em comparando com sua trajetória. Por exemplo, para fins de planejamento de sua derrota,  o tamanho real do navio pode ser desprezado, considerando-o apenas como um ponto no espaço.</dd>
<dt>Corpo Extenso</dt><dd>É o oposto de ponto material, ou seja, é todo corpo cujas dimensões (tamanho) devem ser levados em conta. Por exemplo, no movimento de atracão do navio, o espaço ocupado por ele durante a manobra deve ser levado em conta durante o planejamento. De uma forma mais simples, são os objetos reais. Quando o objeto não apresenta flexibilidade, ou sempre que ela pode ser desprezada, o corpo extenso também é um "Corpo Rígido" </dd>
<dt>Trajetória</dt>
<dd>É o desenho do trajeto ou caminho que o móvel executou (ou executará) durante seu movimento. No caso de um navio, a trajetória corresponde á sua _derrota_ que é como um registro ou plano que indica a direção e as etapas específicas que o navio segue para alcançar seu destino.</dd>
</dl>

## Posição, repouso e movimento

A primeira etapa ao se estudar o movimento de um ponto material é determinar sua localização ou _posição_. Para tanto deve-se escolher uma _origem_, ou _referêncial_ 