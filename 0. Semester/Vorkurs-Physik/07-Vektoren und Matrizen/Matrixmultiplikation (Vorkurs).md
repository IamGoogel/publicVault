---
modul: Vorkurs Physik
fach: Physik
part: "Thema Vektoren und Matrizen"
keywords: matrix multiplication, matrix
---

# Matrixmultiplikation (Vorkurs)

#vorkurs #vorkurs-physik

> [!definition] Matrixmultiplikation
> Das Produkt existiert nur, wenn die Formate zusammenpassen. Sein Eintrag ist das Skalarprodukt der $i$-ten Zeile von $A$ mit der $j$-ten Spalte von $B$:
> $$M^{(n\times m)}\,N^{(m\times k)} = P^{(n\times k)}, \qquad c_{ij} = \sum_k a_{ik}\,b_{kj}$$
> Die inneren Zahlen müssen gleich sein, die äußeren geben das Format des Ergebnisses an. Sind die inneren verschieden, ist das Produkt schlicht nicht definiert — das ist eine vollständige Antwort. Beispiel: $(2\times3)\cdot(2\times2)$ geht nicht, $(2\times2)\cdot(2\times3)$ ergibt eine $2\times3$-Matrix.

> [!note] Vorgehen bei $C = A\,B$
> 1. Formate notieren: $A$ ist $n\times m$, $B$ ist $p\times k$. Gilt $m = p$? Falls nicht, ist man fertig.
> 2. Format des Ergebnisses festhalten: $C$ hat $n$ Zeilen und $k$ Spalten; ein leeres Raster hilft.
> 3. Eintrag für Eintrag: Zeile $i$ von $A$ und Spalte $j$ von $B$ paarweise multiplizieren und addieren, Vorzeichen beachten.
> 4. Das Ergebnis eintragen und zeilenweise fortfahren.
> 5. Kontrolle: eine Zeile mit vielen Nullen noch einmal nachrechnen und das Format aus Schritt 2 vergleichen.

> [!note] Zwei Regeln der Zahlenrechnung gelten hier nicht
> **Reihenfolge:** Im Allgemeinen ist $A\,B \neq B\,A$, ähnlich wie bei zwei Drehungen um verschiedene Achsen.
> $$\begin{pmatrix} 1 & 2 \\ 0 & 1 \end{pmatrix}\begin{pmatrix} 2 & 0 \\ 1 & 3 \end{pmatrix} = \begin{pmatrix} 4 & 6 \\ 1 & 3 \end{pmatrix}, \qquad \begin{pmatrix} 2 & 0 \\ 1 & 3 \end{pmatrix}\begin{pmatrix} 1 & 2 \\ 0 & 1 \end{pmatrix} = \begin{pmatrix} 2 & 4 \\ 1 & 5 \end{pmatrix}$$
> **Nullteiler:** Aus $A\,B = 0$ folgt nicht, dass $A$ oder $B$ null ist:
> $$\begin{pmatrix} 1 & 1 \\ 1 & 1 \end{pmatrix}\begin{pmatrix} 1 & -1 \\ -1 & 1 \end{pmatrix} = \begin{pmatrix} 0 & 0 \\ 0 & 0 \end{pmatrix}$$

Siehe auch: [[Matrix]], [[Inverse Matrix]], [[Skalarprodukt]]

**Weiterführend (1. Semester):** [[Matrixmultiplikation]]
