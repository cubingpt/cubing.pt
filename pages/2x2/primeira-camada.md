---
title: 'Primeira Camada'
date: '2015-08-28T18:12:08+01:00'
status: publish
permalink: /2x2/primeira-camada
author: 'Cubing Portugal'
excerpt: ''
type: page
id: 491
---
Para criar uma camada bem permutada, deve-se sempre procurar escolher a face que já contenha peças bem colocadas ou cuja criação necessite poucos movimentos.

Normalmente é fácil juntar dois cantos adjacentes de uma face. Em seguida apresentam-se algoritmos para resolver todos os casos com 2 ou 3 cantos bem colocados.

Estes algoritmos são intuitivos, alguns são muito semelhantes entre si e devem apenas ser entendidos como referência.

Irá ser apresentada como camada de baixo a cor branca, mas deve pensar-se independentemente da cor utilizada.

### Dois cantos corretos

Nestes casos, todos os algoritmos assentam na colocação dos dois cantos corretos na face de baixo, à esquerda.

<div class="wp-caption aligncenter" id="attachment_492" style="width: 160px">![2x2 Bloco certo primeira face](../../../uploads/2015/08/2x2x2_face1_bloco_certo_trans.png)Bloco de peças resolvido em baixo à esquerda

</div>Os outros cantos da primeira face podem ficar nas posições seguintes, vistas de cima:

<div class="wrc-column-grid wrc-column-grid-5"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_496" style="width: 160px">![2x2 Primeira Face 1](../../../uploads/2015/08/2x2x2_face1_1.png)U2 R2

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_501" style="width: 160px">![2x2 Primeira Face 2](../../../uploads/2015/08/2x2x2_face1_2.png)U2 R U’ R U R’ U’ R

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_502" style="width: 160px">![2x2 Primeira Face 3](../../../uploads/2015/08/2x2x2_face1_3.png)U R2 U R U’ R

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_503" style="width: 160px">![2x2 Primeira Face 4](../../../uploads/2015/08/2x2x2_face1_4.png)R U R’ U R2

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_504" style="width: 160px">![2x2 Primeira Face 5](../../../uploads/2015/08/2x2x2_face1_5.png)U2 R U2 R

</div></div></div><div class="wrc-column-grid wrc-column-grid-5"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_505" style="width: 160px">![2x2 Primeira Face 6](../../../uploads/2015/08/2x2x2_face1_6.png)U R U R2

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_506" style="width: 160px">![2x2 Primeira Face 7](../../../uploads/2015/08/2x2x2_face1_7.png)R U2 R U2 R

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_507" style="width: 160px">![2x2 Primeira Face 8](../../../uploads/2015/08/2x2x2_face1_8.png)U2 R U R

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_508" style="width: 160px">![2x2 Primeira Face 9](../../../uploads/2015/08/2x2x2_face1_9.png)R’ U R2 U R2′

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_509" style="width: 160px">![2x2 Primeira Face 10](../../../uploads/2015/08/2x2x2_face1_10.png)U’ R U’ R’ U2 R’

</div></div></div><div class="wrc-column-grid wrc-column-grid-5"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_510" style="width: 160px">![2x2 Primeira Face 11](../../../uploads/2015/08/2x2x2_face1_11.png)U R U2 R U R’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_511" style="width: 160px">![2x2 Primeira Face 12](../../../uploads/2015/08/2x2x2_face1_12.png)U’ R U R’ U R’ U’ R

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_512" style="width: 160px">![2x2 Primeira Face 13](../../../uploads/2015/08/2x2x2_face1_13.png)U2 R’ U’ R2

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_513" style="width: 160px">![2x2 Primeira Face 14](../../../uploads/2015/08/2x2x2_face1_14.png)R U’ R U R’

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_514" style="width: 160px">![2x2 Primeira Face 15](../../../uploads/2015/08/2x2x2_face1_15.png)R F R F’ R2

</div></div></div><div class="wrc-column-grid wrc-column-grid-5"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_515" style="width: 160px">![2x2 Primeira Face 16](../../../uploads/2015/08/2x2x2_face1_16.png)R2 U’ R U R’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_516" style="width: 160px">![2x2 Primeira Face 17](../../../uploads/2015/08/2x2x2_face1_17.png)U’ R U2 R U’ R’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_517" style="width: 160px">![2x2 Primeira Face 18](../../../uploads/2015/08/2x2x2_face1_18.png)x U R2 U’ L

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_518" style="width: 160px">![2x2 Primeira Face 19](../../../uploads/2015/08/2x2x2_face1_19.png)U2 R’ U R’ U’ R U R’

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_519" style="width: 160px">![2x2 Primeira Face 20](../../../uploads/2015/08/2x2x2_face1_20.png)U R2 U2 R’

</div></div></div><div class="wrc-column-grid wrc-column-grid-5"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_520" style="width: 160px">![2x2 Primeira Face 21](../../../uploads/2015/08/2x2x2_face1_21.png)U R U2 R2 U’ R

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_521" style="width: 160px">![2x2 Primeira Face 22](../../../uploads/2015/08/2x2x2_face1_22.png)U R’ U2 R’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_522" style="width: 160px">![2x2 Primeira Face 23](../../../uploads/2015/08/2x2x2_face1_23.png)R2 U’ R’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_523" style="width: 160px">![2x2 Primeira Face 24](../../../uploads/2015/08/2x2x2_face1_24.png)R U’ R2 U’ R

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_524" style="width: 160px">![2x2 Primeira Face 25](../../../uploads/2015/08/2x2x2_face1_25.png)R’ U’ R’

</div></div></div><div class="wrc-column-grid wrc-column-grid-5"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_525" style="width: 160px">![2x2 Primeira Face 26](../../../uploads/2015/08/2x2x2_face1_26.png)R2 U’ R2 U’ R

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_526" style="width: 160px">![2x2 Primeira Face 27](../../../uploads/2015/08/2x2x2_face1_27.png)R U R’ U2 R’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_535" style="width: 160px">![2x2 Primeira Face 31](../../../uploads/2015/08/2x2x2_face1_31.png)U R U’ R2

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_536" style="width: 160px">![2x2 Primeira Face 32](../../../uploads/2015/08/2x2x2_face1_32.png)U’ R’ U R2 U’ R2′

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_537" style="width: 160px">![2x2 Primeira Face 33](../../../uploads/2015/08/2x2x2_face1_33.png)U2 R U2 R U R2

</div></div></div><div class="wrc-column-grid wrc-column-grid-5"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_540" style="width: 160px">![2x2 Primeira Face 34](../../../uploads/2015/08/2x2x2_face1_34.png)U R’ U’ R’ U R’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_541" style="width: 160px">![2x2 Primeira Face 35](../../../uploads/2015/08/2x2x2_face1_35.png)U’ R2 U R’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_542" style="width: 160px">![2x2 Primeira Face 36](../../../uploads/2015/08/2x2x2_face1_36.png)R U R2′ U’ R U R’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_543" style="width: 160px">![2x2 Primeira Face 40](../../../uploads/2015/08/2x2x2_face1_40.png)R U’ R U’ R

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_544" style="width: 160px">![2x2 Primeira Face 41](../../../uploads/2015/08/2x2x2_face1_41.png)R’ U2 R2 U’ R2′

</div></div></div><div class="wrc-column-grid wrc-column-grid-5"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_546" style="width: 160px">![2x2 Primeira Face 43](../../../uploads/2015/08/2x2x2_face1_43.png)R2′ U R2 U2 R

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_547" style="width: 160px">![2x2 Primeira Face 44](../../../uploads/2015/08/2x2x2_face1_44.png)R’ U R’ U R’

</div></div><div class="wrc-column wrc-column-width-1"></div><div class="wrc-column wrc-column-width-1"></div><div class="wrc-column wrc-column-width-1 wrc-column-end"></div></div>### Três cantos corretos

<div class="wrc-column-grid wrc-column-grid-5"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_527" style="width: 160px">![2x2 Primeira Face 28](../../../uploads/2015/08/2x2x2_face1_28.png)U’ R2 U’ R2 U R2

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_529" style="width: 160px">![2x2 Primeira Face 29](../../../uploads/2015/08/2x2x2_face1_29.png)U R’ U2 R

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_530" style="width: 160px">![2x2 Primeira Face 30](../../../uploads/2015/08/2x2x2_face1_30.png)U’ R’ U’ R

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_532" style="width: 160px">![2x2 Primeira Face 37](../../../uploads/2015/08/2x2x2_face1_37.png)R U R’ U’ R2 U’ R

</div></div><div class="wrc-column wrc-column-width-1 wrc-column-end"><div class="wp-caption aligncenter" id="attachment_531" style="width: 160px">![2x2 Primeira Face 38](../../../uploads/2015/08/2x2x2_face1_38.png)R’ U R U’ R’ U R

</div></div></div><div class="wrc-column-grid wrc-column-grid-5"><div class="wrc-column wrc-column-width-1 wrc-column-start"><div class="wp-caption aligncenter" id="attachment_548" style="width: 160px">![2x2 Primeira Face 39](../../../uploads/2015/08/2x2x2_face1_39.png)R U’ R’ U R U’ R’

</div></div><div class="wrc-column wrc-column-width-1"><div class="wp-caption aligncenter" id="attachment_549" style="width: 160px">![2x2 Primeira Face 42](../../../uploads/2015/08/2x2x2_face1_42.png)R U R’ U’ R U R’

</div></div><div class="wrc-column wrc-column-width-1"></div><div class="wrc-column wrc-column-width-1"></div><div class="wrc-column wrc-column-width-1 wrc-column-end"></div></div>