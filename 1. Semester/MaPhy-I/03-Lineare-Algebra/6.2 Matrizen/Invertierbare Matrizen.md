---
modul: MaPhy I
fach: Mathematik
part: "Kap. 6.2"
keywords: inverse matrix, GL(m,K)
---

# Invertierbare Matrizen

#maphy1 #linear-algebra #matrices #atomic

$A\in\mathrm{Mat}_{m\times m}$ ist *invertierbar*, wenn es $A^{-1}$ gibt mit $AA^{-1}=A^{-1}A=I$. Die Inverse ist eindeutig; eine der beiden Gleichungen genügt (quadratisch).

**Lemma.** $(A^{-1})^{-1}=A$ und $(AB)^{-1}=B^{-1}A^{-1}$ — **Reihenfolge dreht sich um**.

$GL(m,K)$ = Menge der invertierbaren $m\times m$-Matrizen ist eine Gruppe, für $m\ge2$ nichtkommutativ; $\mathrm{Aut}(K^m)\cong GL(m,K)$.

Beispiel: $\begin{pmatrix}2&1\\1&1\end{pmatrix}^{-1}=\begin{pmatrix}1&-1\\-1&2\end{pmatrix}$.

**Kriterien.** $A$ invertierbar ⇔ $\det A\ne0$ ([[Determinante]]) ⇔ $\operatorname{rk}A=m$ ([[Rang und voller Rang]]).

**Baut auf:** [[Matrixmultiplikation]] · [[Umkehrabbildung]] · [[Gruppe]]
**Wird gebraucht für:** [[Basiswechsel]] · [[Determinante und Gruppen]] · [[Laplace-Entwicklung und Adjunkte]]
