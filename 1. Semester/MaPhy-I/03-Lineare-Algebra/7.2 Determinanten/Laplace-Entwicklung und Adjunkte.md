---
modul: MaPhy I
fach: Mathematik
part: "Kap. 7.2"
keywords: Laplace expansion, adjugate, inverse
---

# Laplace-Entwicklung und Adjunkte

#maphy1 #linear-algebra #determinant #atomic

**Satz (Laplace, nach Spalte $j$).**
$$\det A=\sum_{i=1}^n(-1)^{i+j}a_{ij}\det A_{ij},$$
$A_{ij}$ entsteht durch Streichen von Zeile $i$ und Spalte $j$. Beispiel: $\det\begin{pmatrix}0&1&2\\3&4&5\\6&7&8\end{pmatrix}=0$.

**Satz (Adjunkte).** $A\cdot\operatorname{adj}A=\det A\cdot I_n$, also
$$A^{-1}=\frac1{\det A}\operatorname{adj}A\qquad(\det A\ne0).$$

> [!warning] Vorzeichenfaktor
> Das Schachbrettmuster $(-1)^{i+j}$ nicht vergessen; die Adjunkte enthält **transponierte** Kofaktoren.

**Baut auf:** [[Determinante]] · [[Invertierbare Matrizen]]
