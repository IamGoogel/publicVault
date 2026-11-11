---
modul: Vorkurs Physik
fach: Physik
semester: 0
part: "Thema Koordinatensysteme"
Kurs: Vorkurs Physik
Verstaendnis: 0
gelesen: false
geuebt: false
tags: [vorkurs, vorkurs-physik]
---

> [!satz] Geschwindigkeit in Zylinderkoordinaten
> Die Geschwindigkeit ist die zeitliche Ableitung des Ortsvektors. Da $\hat{e}_\varrho$ nach [[Mitgedrehte Basis|der Ableitungsregel]] nicht konstant ist, entstehen bei der [[Produktregel]] drei Summanden:
> $$\vec{v} = \dot{\varrho}\,\hat{e}_\varrho + \varrho\dot{\varphi}\,\hat{e}_\varphi + \dot{z}\,\hat{e}_z, \qquad |\vec{v}|^2 = \dot{\varrho}^2 + (\varrho\dot{\varphi})^2 + \dot{z}^2$$
> Die drei Anteile stehen für radiale Bewegung, Umlauf und Steigen. Zur kinetischen Energie $K = \frac{1}{2}m|\vec{v}|^2$ trägt jeder der drei Anteile bei, auch der unscheinbarste.

> [!note] Warum der Faktor $\varrho$?
> $\dot{\varphi}$ hat die Einheit $1/\mathrm{s}$; erst die Multiplikation mit einer Länge ergibt eine Geschwindigkeit. Für $\varrho = R$ und $\dot{z} = 0$ bleibt $v = R\omega = \frac{2\pi R}{T}$.

> [!example]- Schraubenlinie
> Hier gilt $\dot{\varrho} = 0$, $\dot{\varphi} = \frac{2\pi}{T}$, $\dot{z} = v_z$, also
> $$\vec{v} = \frac{2\pi R}{T}\,\hat{e}_\varphi + v_z\,\hat{e}_z, \qquad K = \frac{m}{2}\left[\left(\frac{2\pi R}{T}\right)^2 + v_z^2\right]$$
> Mit nur $K = \frac{1}{2}m v_z^2$ würde der Umlauf fehlen. Test: Für $v_z = 0$ bleibt eine Kreisbewegung in der Ebene mit $K = \frac{1}{2}m(2\pi R/T)^2$, die falsche Formel dagegen gäbe $K = 0$.

Siehe auch: [[Bahnkurve]], [[Zylinderkoordinaten]], [[Momentangeschwindigkeit]]
