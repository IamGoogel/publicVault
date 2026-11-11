---
modul: Vorkurs Physik
fach: Physik
part: "Thema Vektoren und Matrizen"
keywords: inverse matrix, matrix
---

# Inverse Matrix

#vorkurs #vorkurs-physik

> [!definition] Inverse Matrix ($2\times2$)
> Die inverse Matrix kehrt die Wirkung von $A$ um. Das Gegenstück zur Zahl 1 ist die Einheitsmatrix $\mathbb{1}$ (Einsen auf der Hauptdiagonalen, sonst Nullen), für die $\mathbb{1}A = A\mathbb{1} = A$ gilt.
> $$A^{-1} = \frac{1}{\det A}\begin{pmatrix} d & -b \\ -c & a \end{pmatrix}, \qquad A A^{-1} = A^{-1} A = \mathbb{1}$$
> Die Einträge $a$ und $d$ werden vertauscht, bei $b$ und $c$ wechselt das Vorzeichen. Weil $\det A$ im Nenner steht, existiert die Inverse nur für $\det A \neq 0$.

> [!example]- $C = \begin{pmatrix} 2 & 5 \\ 3 & 4 \end{pmatrix}$ (negative Determinante)
> 1. $\det C = 2\cdot4 - 5\cdot3 = -7 \neq 0$ — die Inverse existiert.
> 2. Einträge vertauschen bzw. Vorzeichen ändern, den Faktor davorsetzen:
> $$C^{-1} = \frac{1}{-7}\begin{pmatrix} 4 & -5 \\ -3 & 2 \end{pmatrix} = \begin{pmatrix} -\frac{4}{7} & \frac{5}{7} \\ \frac{3}{7} & -\frac{2}{7} \end{pmatrix}$$
> Wegen des negativen Faktors kehren sich alle vier Vorzeichen um; hier passieren die meisten Fehler.
> 3. Kontrolle, den Faktor zunächst außen lassend: $C\,C^{-1} = -\frac{1}{7}\begin{pmatrix} -7 & 0 \\ 0 & -7 \end{pmatrix} = \mathbb{1}$. Abseits der Diagonalen löschen sich die Summanden aus, auf der Diagonalen steht jeweils die Determinante, die sich mit dem Vorfaktor wegkürzt.

Siehe auch: [[Determinante (Vorkurs)|Determinante]], [[Matrixmultiplikation (Vorkurs)|Matrixmultiplikation]], [[Drehmatrix]], [[Matrix]]

**Weiterführend (1. Semester):** [[Invertierbare Matrizen]]
