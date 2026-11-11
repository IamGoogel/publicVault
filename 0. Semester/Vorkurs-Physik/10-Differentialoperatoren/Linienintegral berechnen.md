---
modul: Vorkurs Physik
fach: Physik
part: "Thema Differentialoperatoren"
keywords: line integral, computation, parametrization
---

# Linienintegral berechnen

#vorkurs #vorkurs-physik

> [!definition] Vorgehen: Linienintegral in sechs Schritten
> 1. Den Weg parametrisieren: $\vec{r}(t)$ mit $t \in [t_1, t_2]$. Kontrolle: $t_1$ und $t_2$ müssen Anfangs- und Endpunkt ergeben ([[Bahnkurve]]).
> 2. Das Integral in ein gewöhnliches umschreiben — der zentrale Schritt:
> $$\int_C\vec{F}\cdot d\vec{r} = \int_{t_1}^{t_2}\vec{F}\big(\vec{r}(t)\big)\cdot\frac{d\vec{r}}{dt}\,dt$$
> 3. Zwei Dinge berechnen: das Feld entlang des Weges, $\vec{F}(\vec{r}(t))$ (die Komponenten von $\vec{r}(t)$ für $x,y,z$ einsetzen), und die Ableitung $\frac{d\vec{r}}{dt}$ komponentenweise.
> 4. Skalarprodukt bilden und vereinfachen. Es bleibt eine gewöhnliche Funktion von $t$.
> 5. Das nun eindimensionale Integral aufschreiben — es entspricht den Integralen aus Kapitel 4.
> 6. Auswerten: Stammfunktion, Grenzen einsetzen, subtrahieren.

> [!satz] Zusammengesetzte Wege
> - Eine Strecke von $\vec{r}_A$ nach $\vec{r}_B$ (konstante Richtung) parametrisiert man so:
> $$\vec{r}(t) = \vec{r}_A + t\,(\vec{r}_B - \vec{r}_A),\quad t\in[0,1],\qquad \frac{d\vec{r}}{dt} = \vec{r}_B - \vec{r}_A$$
> - Additivität: Besteht $C$ aus Teilstücken $C_1,\dots,C_n$, parametrisiert man jedes für sich (meist wieder mit $t \in [0,1]$) und addiert die Ergebnisse: $\int_C = \int_{C_1} + \dots + \int_{C_n}$.
> - Richtung: Läuft man den Weg $-C$ rückwärts durch, ändert sich das Vorzeichen: $\int_{-C}\vec{F}\cdot d\vec{r} = -\int_C\vec{F}\cdot d\vec{r}$, weil alle Wegelemente ihr Vorzeichen wechseln. Man kehrt entweder das Vorzeichen um oder vertauscht die Grenzen — beides gleichzeitig hebt sich auf und ist falsch.

> [!example]- $\oint_C\vec{F}\cdot d\vec{r}$ für $\vec{F} = (x+y,\; x^2,\; 0)^T$ über ein Dreieck
> Eckpunkte $P_0 = (0,0)$, $P_1 = (2,0)$, $P_2 = (0,2)$, Umlauf gegen den Uhrzeigersinn; jede Seite mit $t \in [0,1]$:
> - $C_1$ ($P_0 \to P_1$): $\vec{r} = (2t, 0, 0)$, $\frac{d\vec{r}}{dt} = (2,0,0)$, $\vec{F} = (2t, 4t^2, 0)$, $\vec{F}\cdot\frac{d\vec{r}}{dt} = 4t$, $\int_0^1 4t\,dt = 2$.
> - $C_2$ ($P_1 \to P_2$): $\vec{r} = (2-2t, 2t, 0)$, $\frac{d\vec{r}}{dt} = (-2,2,0)$. Da $x+y = 2$, ist $\vec{F} = (2, (2-2t)^2, 0)$ und $\vec{F}\cdot\frac{d\vec{r}}{dt} = -4 + 2(2-2t)^2 = 4 - 16t + 8t^2$; $\int_0^1 = \big[4t - 8t^2 + \tfrac{8}{3}t^3\big]_0^1 = -\tfrac{4}{3}$.
> - $C_3$ ($P_2 \to P_0$): $\vec{r} = (0, 2-2t, 0)$, $\frac{d\vec{r}}{dt} = (0,-2,0)$, $\vec{F} = (2-2t, 0, 0)$, $\vec{F}\cdot\frac{d\vec{r}}{dt} = 0$: Das Feld zeigt in $x$-Richtung, der Weg verläuft in $y$-Richtung — kein Beitrag.
> Summe: $2 - \frac{4}{3} + 0 = \frac{2}{3}$.
> Kontrollen: Das Ergebnis ist ungleich null, was zu erwarten ist, denn $(\nabla\times\vec{F})_z = 2x - 1$, das Feld ist nicht wirbelfrei. Beim Umlauf im Uhrzeigersinn ergäbe sich $-\frac{2}{3}$.

Siehe auch: [[Linienintegral]], [[Wegunabhängigkeit]], [[Rotation]]

**Weiterführend (1. Semester):** [[Arbeit und Wegintegral]]
