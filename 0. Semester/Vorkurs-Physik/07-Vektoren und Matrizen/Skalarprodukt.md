---
modul: Vorkurs Physik
fach: Physik
part: "Thema Vektoren und Matrizen"
keywords: scalar product, dot product, vectors
---

# Skalarprodukt

#vorkurs #vorkurs-physik

> [!definition] Skalarprodukt
> Wenn $\vec{a}$ und $\vec{b}$ den Winkel $\alpha$ bilden, gilt
> $$\vec{a}\cdot\vec{b} = |\vec{a}|\,|\vec{b}|\cos\alpha = a_1 b_1 + a_2 b_2 + a_3 b_3 \in \mathbb{R}, \qquad \alpha = \arccos\left(\frac{\vec{a}\cdot\vec{b}}{|\vec{a}|\,|\vec{b}|}\right)$$
> Das Ergebnis ist eine Zahl und kein Vektor; der Winkel liegt zwischen $0^\circ$ und $180^\circ$. Beide Darstellungen sind in jeder Dimension gültig.

> [!satz] Orthogonalität
> Da $\cos 90^\circ = 0$ ist, gilt $\vec{a} \perp \vec{b} \Leftrightarrow \vec{a}\cdot\vec{b} = 0$. Damit prüft man rechnerisch auf Rechtwinkligkeit — eine der wichtigsten Anwendungen. Zeigen die Vektoren in dieselbe Richtung, ist $\vec{a}\cdot\vec{b} = +ab$, bei entgegengesetzter Richtung $-ab$, und bei einem stumpfen Winkel ist das Produkt negativ.

> [!note] Veranschaulichung durch Projektion
> Wirft man $\vec{b}$ senkrecht auf die Gerade durch $\vec{a}$, hat der Schatten die Länge $|\vec{b}|\cos\alpha$ (Projektion von $\vec{b}$ auf $\vec{a}$). Das Skalarprodukt ist diese Länge multipliziert mit $|\vec{a}|$; es misst also den Anteil von $\vec{b}$ in Richtung $\vec{a}$. Es ist symmetrisch: $\vec{a}\cdot\vec{b} = \vec{b}\cdot\vec{a}$.

Siehe auch: [[Kreuzprodukt]], [[Kräftezerlegung]], [[Divergenz]], [[Matrixmultiplikation (Vorkurs)|Matrixmultiplikation]], [[Vektoren in Komponenten]], [[Linienintegral]], [[Höhenlinie]], [[Fluss durch eine Fläche]]

**Weiterführend (1. Semester):** [[Arbeit und Wegintegral]]
