---
modul: Vorkurs Physik
fach: Physik
part: "Thema Koordinatensysteme"
keywords: atan2, angle, quadrant
---

# Winkelbestimmung mit atan2

#vorkurs #vorkurs-physik

> [!definition] Der richtige Quadrant beim Arkustangens
> Aus $\tan\varphi = \frac{y}{x}$ könnte man $\varphi = \arctan\frac{y}{x}$ schließen. Das stimmt aber nur in einer Halbebene: Der Arkustangens liefert immer Werte zwischen $-\frac{\pi}{2}$ und $+\frac{\pi}{2}$, während $(1,1)$ und $(-1,-1)$ den gleichen Quotienten haben. Die vollständige Fallunterscheidung ist $\mathrm{atan2}$:
> $$\varphi = \arctan\frac{y}{x}\;(x>0), \qquad \varphi = \arctan\frac{y}{x}\pm\pi\;(x<0), \qquad \varphi = \pm\frac{\pi}{2}\;(x=0)$$
> Das Vorzeichen richtet sich jeweils nach dem von $y$. Negative Ergebnisse bringt man mit $+2\pi$ in den Bereich $[0, 2\pi)$.

> [!note] Rückprobe
> Man setzt $(\varrho, \varphi)$ in die Umrechnungsformeln ein und vergleicht die Vorzeichen. Erhält man $(-x,-y)$ statt $(x,y)$, fehlt genau ein $\pi$. Die Verwechslung der Quadranten ist hier die häufigste Fehlerquelle.

Siehe auch: [[Polarkoordinaten]], [[Zylinderkoordinaten]], [[Kugelkoordinaten]]
