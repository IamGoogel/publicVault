---
modul: Vorkurs Physik
fach: Physik
part: "Thema Vektoren und Matrizen"
keywords: force decomposition, vector components, forces
---

# Kräftezerlegung

#vorkurs #vorkurs-physik

> [!definition] Kräftezerlegung (Orthogonalzerlegung)
> Man schreibt eine Kraft als Summe zweier aufeinander senkrechter Anteile. Hat die Kraft den Betrag $F$ und schließt den Winkel $\alpha$ mit der $x$-Achse ein, dann gilt
> $$\vec{F} = F\begin{pmatrix} \cos\alpha \\ \sin\alpha \end{pmatrix} = \begin{pmatrix} F\cos\alpha \\ F\sin\alpha \end{pmatrix}$$
> Der Kosinus gehört zu der Achse, von der aus der Winkel gemessen wird, der Sinus zur anderen.

> [!example]- Klotz auf einer schiefen Ebene (Neigung $\alpha$)
> Die Gewichtskraft $F_G = m g$ zeigt senkrecht nach unten. Man zerlegt sie in eine Komponente längs der Ebene und eine senkrecht dazu:
> $$F_\parallel = F_G \sin\alpha, \qquad F_\perp = F_G \cos\alpha$$
> Grenzfälle: $\alpha = 0$ ergibt $F_\parallel = 0$; $\alpha = 90^\circ$ ergibt $F_\parallel = F_G$ (freier Fall).

> [!note] Koordinatenachsen geschickt legen
> Wie man das Koordinatensystem orientiert, ist frei wählbar und der entscheidende Schritt. Bei der schiefen Ebene legt man eine Achse in die Ebene hinein und eine senkrecht dazu; die Normalkraft hat dann nur eine Komponente. Mehrere Kräfte addiert man komponentenweise und bestimmt den Betrag der Summe wie bei jedem Vektor.
> Kontrollen: $|\vec{F}| = F\sqrt{\cos^2\alpha + \sin^2\alpha} = F$, und das Ergebnis muss die Einheit $\mathrm{N}$ haben. Zwei gleich große Kräfte unter den Winkeln $+\beta$ und $-\beta$ ergeben $2F\cos\beta$, weil sich die $y$-Anteile aufheben. Nützliche Werte: $\cos 30^\circ = \frac{\sqrt{3}}{2}$, $\sin 30^\circ = \frac{1}{2}$, $\sin 45^\circ = \cos 45^\circ = \frac{1}{\sqrt{2}} \approx 0{,}707$.

Siehe auch: [[Skalarprodukt]], [[Vektoren in Komponenten]], [[Trigonometrischer Pythagoras]]

**Weiterführend (1. Semester):** [[Superpositionsprinzip]]
