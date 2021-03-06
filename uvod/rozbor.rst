..  _kap-rozbor:

*******************
Teoretický rozbor
*******************

.. |_| unicode:: 0xA0
   :trim:

Řízení pásových vozidel je velice složitá záležitost. Správné řízení závisí na mnoha aspektech. Pásová vozidla se řídí změnou rychlostí jednotlivých pásů. Pokud chceme správně řídit pásové vozidlo musíme brát v potaz nejen rychlosti pásů, ale i tření, terén a další aspekty, které by mohly ovlivnit směr a rychlost pohybu vozidla. Z tohoto důvodu je řízení pásových vozidel velice náročné. Hlavně proto, že některé z aspektů nejsou ani pořádně prakticky popsané a |_| pouze o nich uvažujeme jako například o tření. Řízením autonomních vozidel se zabývají např.: :cite:`1985:creedy`, nebo :cite:`2014:ren`.

Pro správné řízení vozidla je potřeba nejen znát jednotlivé vzdálenosti od stěn, ale i úhel natočení vůči nim. Díky tomuto úhlu je schopno vozidlo správně a včas zareagovat na přibližování ke stěně (viz. :num:`obr. #obr-uhel`. Tento úhel je možno vypočítat pomocí následujících vzorců:

..  math::  \alpha \approx (v_1 - v_2) \, t

Úhel natočení vůči stěně (:math:`\alpha`) odpovídá rozdílu rychlostí jednotlivých pásů (:math:`v_1 ; \, v_2`) za dobu za kterou se tyto rychlosti uplatní (:math:`t`).

..  math::  \Delta d = v \, \Delta t \, sin\alpha

Přírůstek vzdálenosti od stěny za přírustek času.

..  math::  d = d_0 + sin\alpha \int^{t_2}_{t_1} v \, \mathrm{d}t

Vzdálenost od stěny (:math:`d`) lze vypočítat jako součet vzdálenosti původní (:math:`d_0`), k níž se přičte :math:`sin\alpha` vynásobený integrálem. Integrál představuje měnící se vzdálenost od stěny v závislosti na čase (:math:`t_1 ; \, t_2`). Pomocí těchto vzorců lze vypočítat vzdálenost i úhel natočení vozidla vůči stěně.

..  _obr-uhel:

..  figure:: ../obrazky/Uhel.png
    :width: 33%
    
    Úhel natočení

