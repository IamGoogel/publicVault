---
modul: Vorkurs Physik
fach: Physik
semester: 0
part: "Thema Integralrechnung"
Kurs: Vorkurs Physik
Verstaendnis: 0
gelesen: false
geuebt: false
tags: [vorkurs, vorkurs-physik]
---

> [!definition] Unendliche Integrationsgrenze
> Eine unendliche Grenze wird als Grenzwert verstanden:
> $$\int_a^\infty f\,dx \equiv \lim_{R\to\infty}\int_a^R f\,dx$$
> Man bildet die Stammfunktion, setzt die endliche Grenze $R$ ein und untersucht, was für $R\to\infty$ mit jedem Term geschieht.

> [!example]- Exponentialfunktion
> $$\int_0^t e^{-t'/\tau}\,dt' = \Big[-\tau\,e^{-t'/\tau}\Big]_0^t = \tau\left(1 - e^{-t/\tau}\right) \xrightarrow{t\to\infty} \tau$$
> Der Faktor $-\tau$ stammt aus [[Integration mit linearem Argument]]; an der unteren Grenze ist $e^0 = 1$. Der Grenzwert dient zugleich als Test: Man setzt einen Fall ein, dessen Ergebnis man kennt, und deutet den Rest.

Siehe auch: [[Integrale in der Physik]], [[Exponentielles Wachstum und Zerfall]]
