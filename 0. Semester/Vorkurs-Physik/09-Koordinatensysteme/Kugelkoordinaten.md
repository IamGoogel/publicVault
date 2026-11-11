---
modul: Vorkurs Physik
fach: Physik
part: "Thema Koordinatensysteme"
keywords: spherical coordinates, coordinates
---

# Kugelkoordinaten

#vorkurs #vorkurs-physik

> [!definition] Kugelkoordinaten
> Ein Punkt wird durch den Abstand $r$ vom Ursprung und zwei Winkel festgelegt — ähnlich wie Radius, Breite und Länge auf der Erdkugel. Es gilt $r \in [0,\infty)$, $\vartheta \in [0,\pi]$ (Nordpol $\vartheta = 0$, Äquator $\frac{\pi}{2}$, Südpol $\pi$) und $\varphi \in [0,2\pi)$:
> $$\vec{r} = \begin{pmatrix} r\sin\vartheta\cos\varphi \\ r\sin\vartheta\sin\varphi \\ r\cos\vartheta \end{pmatrix}, \quad r = \sqrt{x^2+y^2+z^2}, \quad \vartheta = \arccos\frac{z}{r}, \quad \varphi = \mathrm{atan2}(y,x)$$
> Die Darstellung entsteht in zwei Schritten: Aus dem Dreieck in der Ebene durch die $z$-Achse folgen $\varrho = r\sin\vartheta$ und $z = r\cos\vartheta$, danach die ebene Umrechnung. Für $\vartheta$ ist keine Quadrantenkorrektur nötig, denn der Wertebereich des Arkuskosinus, $[0,\pi]$, deckt sich mit dem von $\vartheta$.

> [!satz] Orthonormale Basis
> $$\hat{e}_r = (s_\vartheta c_\varphi,\; s_\vartheta s_\varphi,\; c_\vartheta)^T, \quad \hat{e}_\vartheta = (c_\vartheta c_\varphi,\; c_\vartheta s_\varphi,\; -s_\vartheta)^T, \quad \hat{e}_\varphi = (-s_\varphi,\; c_\varphi,\; 0)^T$$
> Abkürzungen: $s_\vartheta = \sin\vartheta$, $c_\vartheta = \cos\vartheta$, analog für $\varphi$. Die Längen von $\partial\vec{r}/\partial r$, $\partial\vec{r}/\partial\vartheta$ und $\partial\vec{r}/\partial\varphi$ sind $1$, $r$ bzw. $r\,s_\vartheta$. Senkrecht: $\hat{e}_r\cdot\hat{e}_\vartheta = s_\vartheta c_\vartheta(c_\varphi^2 + s_\varphi^2) - c_\vartheta s_\vartheta = 0$. Rechtshändig: $\hat{e}_r\times\hat{e}_\vartheta = \hat{e}_\varphi$ (Komponenten $-s_\varphi$, $c_\varphi$, $0$).

> [!example]- $\vec{a} = (-3,\,3,\,3\sqrt{2})^T$ in drei Koordinatensystemen
> - Zylinderkoordinaten: $\varrho = \sqrt{9+9} = 3\sqrt{2} \approx 4{,}24$. Wegen $x<0$ und $y>0$ liegt der Punkt im zweiten Quadranten: $\arctan(-1) = -\frac{\pi}{4}$, plus $\pi$ ergibt $\varphi = \frac{3\pi}{4}$ ($135^\circ$); $z = 3\sqrt{2}$.
> - Kugelkoordinaten: derselbe Winkel $\varphi$. $r = \sqrt{9+9+18} = 6$, $\cos\vartheta = \frac{3\sqrt{2}}{6} = \frac{\sqrt{2}}{2}$, also $\vartheta = \frac{\pi}{4}$ ($45^\circ$).
> - Rückrechnung: $x = 6\cdot\frac{\sqrt{2}}{2}\cdot\left(-\frac{\sqrt{2}}{2}\right) = -3$, entsprechend $y = 3$ und $z = 3\sqrt{2}$ — alle Vorzeichen stimmen.

Siehe auch: [[Zylinderkoordinaten]], [[Winkelbestimmung mit atan2]], [[Volumenelement]], [[Flächenelement der Kugel]], [[Mitgedrehte Basis]], [[Fluss durch eine Fläche]]
