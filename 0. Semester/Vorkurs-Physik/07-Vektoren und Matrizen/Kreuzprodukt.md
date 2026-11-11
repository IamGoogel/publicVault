---
modul: Vorkurs Physik
fach: Physik
semester: 0
part: "Thema Vektoren und Matrizen"
Kurs: Vorkurs Physik
Verstaendnis: 0
gelesen: false
geuebt: false
tags: [vorkurs, vorkurs-physik]
---

> [!definition] Kreuzprodukt
> Für $\vec{a}, \vec{b} \in \mathbb{R}^3$ ist das Kreuzprodukt der Vektor
> $$\vec{c} = \vec{a}\times\vec{b} = \begin{pmatrix} a_2 b_3 - a_3 b_2 \\ a_3 b_1 - a_1 b_3 \\ a_1 b_2 - a_2 b_1 \end{pmatrix}, \qquad \vec{c}\perp\vec{a},\;\vec{c}\perp\vec{b},\;|\vec{c}| = |\vec{a}|\,|\vec{b}|\sin\theta = A$$
> Gedächtnisstütze: In der $i$-ten Zeile kommt der Index $i$ nicht vor, die übrigen laufen zyklisch $1\to2\to3\to1$. Das Kreuzprodukt ist nur im $\mathbb{R}^3$ erklärt; ebene Vektoren ergänzt man durch eine dritte Komponente $0$.

> [!note] Geometrie und Regeln
> - Der Betrag entspricht dem Flächeninhalt $A$ des Parallelogramms, das $\vec{a}$ und $\vec{b}$ aufspannen. Für parallele Vektoren ist $\vec{a}\times\vec{b} = \vec{0}$.
> - Rechte-Hand-Regel: Daumen in Richtung $\vec{a}$, Zeigefinger in Richtung $\vec{b}$, dann zeigt der Mittelfinger in Richtung $\vec{a}\times\vec{b}$.
> - $\vec{a}\times\vec{b} = -\,\vec{b}\times\vec{a}$.
> - Auch der Winkel lässt sich so bestimmen: $\theta = \arcsin\frac{|\vec{a}\times\vec{b}|}{|\vec{a}||\vec{b}|}$. Der Arkussinus liefert aber für $\theta$ und $180^\circ - \theta$ denselben Wert; bei stumpfen Winkeln ist das [[Skalarprodukt]] zuverlässiger.

> [!note] Häufiger Fehler: die mittlere Komponente
> In der mittleren Zeile steht $a_3 b_1 - a_1 b_3$, also in umgekehrter Reihenfolge, nicht $a_1 b_3 - a_3 b_1$. Kontrolle: Da $\vec{a}\times\vec{b}$ auf beiden Vektoren senkrecht steht, muss $(\vec{a}\times\vec{b})\cdot\vec{a} = 0$ und $(\vec{a}\times\vec{b})\cdot\vec{b} = 0$ sein; bei einem Vorzeichenfehler ist das nicht der Fall.

> [!example]- $\vec{a} = (2,1,2)^T$, $\vec{b} = (1,2,2)^T$
> Beide Vektoren haben die Länge $\sqrt{9} = 3$. Komponenten: $c_1 = 1\cdot2 - 2\cdot2 = -2$, $c_2 = 2\cdot1 - 2\cdot2 = -2$, $c_3 = 2\cdot2 - 1\cdot1 = 3$, also $\vec{c} = (-2,-2,3)^T$.
> Kontrolle: $\vec{c}\cdot\vec{a} = -4 - 2 + 6 = 0$ und $\vec{c}\cdot\vec{b} = -2 - 4 + 6 = 0$.
> Fläche $A = |\vec{c}| = \sqrt{17} \approx 4{,}12$; daraus $\sin\theta = \frac{\sqrt{17}}{9} = 0{,}458$ und $\theta \approx 27{,}3^\circ$. Mit dem Skalarprodukt $\vec{a}\cdot\vec{b} = 8$ folgt $\cos\theta = \frac{8}{9}$, ebenfalls $\theta \approx 27{,}3^\circ$. Stimmen zwei voneinander unabhängige Wege überein, ist das die beste Kontrolle.

Siehe auch: [[Skalarprodukt]], [[Rotation]], [[Mitgedrehte Basis]], [[Determinante (Vorkurs)|Determinante]], [[Vektoren in Komponenten]]

**Weiterführend (1. Semester):** [[Drehimpuls und Drehmoment]]
