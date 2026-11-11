---
modul: Vorkurs Physik
fach: Physik
semester: 0
part: "Thema Volumen- und Flächenintegrale"
Kurs: Vorkurs Physik
Verstaendnis: 0
gelesen: false
geuebt: false
tags: [vorkurs, vorkurs-physik]
---

> [!definition] Fluss durch eine Fläche
> Bild: Wie viel Wasser pro Sekunde durch einen Rahmen strömt, hängt von der Strömung und von der Stellung des Rahmens ab. Für ein Vektorfeld $\vec{F}$ und eine Fläche $A$ definiert man
> $$\Phi = \int_A\vec{F}\cdot d\vec{A}, \qquad d\vec{A} = dA\,\hat{e}_n, \qquad\text{also}\qquad \Phi = \int_A\vec{F}\cdot\hat{e}_n\,dA$$
> $\hat{e}_n$ ist der Normaleneinheitsvektor der Fläche (Länge 1, senkrecht zur Fläche). $d\vec{A}$ ist demnach ein Vektor, der Fluss dagegen eine Zahl.

> [!note] Ablauf und Vorzeichen
> Man geht in drei Schritten vor: in kleine Stücke zerlegen, jeweils projizieren, alles aufaddieren. Nur der Anteil in Normalenrichtung geht ein, $\vec{F}\cdot\hat{e}_n = |\vec{F}|\cos\alpha$. Ist die Fläche geschlossen, nimmt man die äußere Normale; bei einer offenen Fläche legt man eine der beiden Richtungen fest, und die Wahl bestimmt das Vorzeichen des Flusses.
> Auf einer Kugel um den Ursprung weist die Normale radial nach außen; sie ist der Einheitsvektor $\hat{e}_r$ der [[Kugelkoordinaten]]:
> $$d\vec{A} = R^2\sin\vartheta\,d\vartheta\,d\varphi\;\hat{e}_r$$
> Im Gegensatz zum festen Vektor $(0,0,1)^T$ bei einem ebenen Quadrat ändert sich $\hat{e}_r$ von Punkt zu Punkt. Im Skalarprodukt stört das nicht, solange auch das Feld radial gerichtet ist, da $\hat{e}_r\cdot\hat{e}_r = 1$.

> [!example]- Feld $\vec{F} = \frac{c}{r^2}\hat{e}_r$ ($c > 0$) durch eine Kugelfläche mit Radius $R$
> Die Fläche ist geschlossen, also $\hat{e}_n = \hat{e}_r$. Auf der Fläche ist $r = R$:
> $$\vec{F}\cdot d\vec{A} = \frac{c}{R^2}\,R^2\sin\vartheta\,d\vartheta\,d\varphi = c\sin\vartheta\,d\vartheta\,d\varphi$$
> $$\Phi = c\int_0^{2\pi}\!\!\int_0^\pi\sin\vartheta\,d\vartheta\,d\varphi = c\cdot2\cdot2\pi = 4\pi c$$
> Gegenprobe: Das Feld ist auf der gesamten Kugel radial und hat überall den Betrag $\frac{c}{R^2}$; der Fluss ist damit $\frac{c}{R^2}\cdot4\pi R^2$. In der Lösung kommt $R$ nicht mehr vor: Die Fläche wächst mit $R^2$, das Feld nimmt mit $1/R^2$ ab. Nach dem [[Satz von Gauß]] zählt für den Fluss nur, was im Inneren liegt.

Siehe auch: [[Flächenelement der Kugel]], [[Divergenz]], [[Skalarprodukt]]
