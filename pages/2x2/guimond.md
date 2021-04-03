---
title: 'Método de Guimond'
date: '2015-08-22T17:48:50+01:00'
status: publish
permalink: /2x2/guimond
author: 'Cubing Portugal'
excerpt: ''
type: page
id: 269
---
O método de Guimond foi desenvolvido por Gaétan Guimond, na década de 80, e é um método que permite resolver um 2×2 orientando primeiro todos os cantos e depois permutando ambas as camadas. Requer 16 algoritmos (sem casos equivalentes).

Passo 1: Resolver 3/4 de uma face com cores opostas
---------------------------------------------------

Deve-se entender aqui cores opostas como cores que aparecem em lados opostos do cubo. No caso do esquema de cores tradicional, são verde/azul, branco/amarelo e vermelho/laranja. Na grande maioria dos casos, se não existir nenhuma face nestas condições,

Eis alguns exemplos de 3/4 de uma face resolvida utilizando cores opostas.

<div class="wrc-column-grid wrc-column-grid-5"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_583" style="width: 160px">![2x2 Guimond Face Exemplo 1](../../../uploads/2015/08/2x2x2_guimond_ex_face1.png)Exemplo 1

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_584" style="width: 160px">![2x2 Guimond Face Exemplo 2](../../../uploads/2015/08/2x2x2_guimond_ex_face2.png)Exemplo 2

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_585" style="width: 160px">![2x2 Guimond Face Exemplo 3](../../../uploads/2015/08/2x2x2_guimond_ex_face3.png)Exemplo 3

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_586" style="width: 160px">![2x2 Guimond Face Exemplo 4](../../../uploads/2015/08/2x2x2_guimond_ex_face4.png)Exemplo 4

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_587" style="width: 160px">![2x2 Guimond Face Exemplo 5](../../../uploads/2015/08/2x2x2_guimond_ex_face5.png)Exemplo 5

</div></div></div>Como se pode verificar no exemplo 5, não é necessário que essa face parcial tenha que ser constituída sempre por cores opostas. Pode-se usar uma mesma cor ou cores opostas.

Pode-se igualmente observar que os exemplos 1 e 2 são em tudo semelhantes, exceto na orientação do 4º canto que não está bem orientado. Deve-se tomar isso em conta para a correta identificação do caso a executar no passo seguinte.

Passo 2: Orientação dos cantos
------------------------------

Coloca-se a face construída no passo anterior para baixo e, consoante a orientação do último canto não orientado (horária ou anti-horária), executam-se os algoritmos de acordo com as hipóteses apresentadas.

Note-se que se vai usar a cor rosa/roxo para simbolizar cores opostas, isto é, os autocolantes representados nas imagens seguintes podem simbolizar qualquer cor oposta, como no primeiro passo.

### Orientação “anti-horária”

<div class="wrc-column-grid wrc-column-grid-4"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_557" style="width: 160px">![2x2 Guimond Orientação 1](../../../uploads/2015/08/2x2x2_guimond_o1.png)F’ L2 F

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_558" style="width: 160px">![2x2 Guimond Orientação 2](../../../uploads/2015/08/2x2x2_guimond_o2.png)L2 U L

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_559" style="width: 160px">![2x2 Guimond Orientação 3](../../../uploads/2015/08/2x2x2_guimond_o3.png)R2 F2 U F

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_560" style="width: 160px">![2x2 Guimond Orientação 4](../../../uploads/2015/08/2x2x2_guimond_o4.png)L U’ L’

</div></div></div><div class="wrc-column-grid wrc-column-grid-4"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_561" style="width: 160px">![2x2 Guimond Orientação 5](../../../uploads/2015/08/2x2x2_guimond_o5.png)y’ R’ F’ R

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_562" style="width: 160px">![2x2 Guimond Orientação 6](../../../uploads/2015/08/2x2x2_guimond_o6.png)x2 R U’ B L’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_563" style="width: 160px">![2x2 Guimond Orientação 7](../../../uploads/2015/08/2x2x2_guimond_o7.png)F’ R U’ F2 U’

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_564" style="width: 160px">![2x2 Guimond Orientação 8](../../../uploads/2015/08/2x2x2_guimond_o8.png)R F2 U’ R2 F U’

</div></div></div>### Orientação “horária”

<div class="wrc-column-grid wrc-column-grid-4"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_568" style="width: 160px">![2x2 Guimond Orientação 9](../../../uploads/2015/08/2x2x2_guimond_o9.png)L U2 L’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_569" style="width: 160px">![2x2 Guimond Orientação 10](../../../uploads/2015/08/2x2x2_guimond_o10.png)y L2 D’ R

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_570" style="width: 160px">![2x2 Guimond Orientação 11](../../../uploads/2015/08/2x2x2_guimond_o11.png)F2 R2 U’ R’

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_571" style="width: 160px">![2x2 Guimond Orientação 12](../../../uploads/2015/08/2x2x2_guimond_o12.png)y R’ U R

</div></div></div><div class="wrc-column-grid wrc-column-grid-4"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_572" style="width: 160px">![2x2 Guimond Orientação 13](../../../uploads/2015/08/2x2x2_guimond_o13.png)L U L’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_573" style="width: 160px">![2x2 Guimond Orientação 14](../../../uploads/2015/08/2x2x2_guimond_o14.png)R U’ B L’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_574" style="width: 160px">![2x2 Guimond Orientação 15](../../../uploads/2015/08/2x2x2_guimond_o15.png)R’ F U’ F2 U

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_575" style="width: 160px">![2x2 Guimond Orientação 16](../../../uploads/2015/08/2x2x2_guimond_o16.png)x U R’ U’ R U2 R

</div></div></div>Passo 3: Resolver faces opostas
-------------------------------

Após a orientação dos cantos, resolvem-se as faces opostas.

Há 4 hipóteses relevantes:

<div class="wrc-column-grid wrc-column-grid-4"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_577" style="width: 160px">![2x2 Guimond Permutação 1](../../../uploads/2015/08/2x2x2_guimond_p1.png)R2 U2 F2

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_578" style="width: 160px">![2x2 Guimond Permutação 2](../../../uploads/2015/08/2x2x2_guimond_p2.png)R2 U’ R2′

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_579" style="width: 160px">![2x2 Guimond Permutação 3](../../../uploads/2015/08/2x2x2_guimond_p3.png)R2 U’ R2′ U’ R2

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_580" style="width: 160px">[![2x2 Guimond Permutação 4](../../../uploads/2015/08/2x2x2_guimond_p4.png)](http://cubing.pt/wp-content/uploads/2015/08/2x2x2_guimond_p4.png)R2

</div></div></div>Passo 4: Permutar ambas as camadas
----------------------------------

Este passo é exatamente igual ao passo de [permutação de ambas as camadas](http://cubing.pt/2x2/ortega/#pbl) do método Ortega.