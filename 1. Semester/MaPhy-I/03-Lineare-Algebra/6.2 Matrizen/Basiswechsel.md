---
modul: MaPhy I
fach: Mathematik
part: "Kap. 6.2"
keywords: change of basis, A' = C^-1 A B, similarity
---

# Basiswechsel

#maphy1 #linear-algebra #change-of-basis #atomic

Neue Basen: $(v'_1\dots v'_n)=(v_1\dots v_n)B$ in $V$, $(w'_1\dots w'_m)=(w_1\dots w_m)C$ in $W$ mit invertierbaren $B,C$.

**Lemma.** Die neue Abbildungsmatrix ist
$$A'=C^{-1}AB .$$
*Herleitung:* $T(v')=T(v)B=wAB=w'C^{-1}AB$.

**Spezialfall** $V=W$ mit gleichen Basen ($B=C$): $A'=B^{-1}AB$ — *Ähnlichkeit* ([[Äquivalente und ähnliche Matrizen]]).

> [!warning] Reihenfolge
> $A'=C^{-1}AB$: das Inverse gehört zur **Zielbasis** $C$, nicht zu $B$. Beim Endomorphismus fällt der Unterschied weg.

> [!tip] Invarianten
> Determinante, Spur und Eigenwerte ähnlicher Matrizen stimmen überein → Eigenschaften des Endomorphismus selbst, nicht der Basis.

**Baut auf:** [[Abbildungsmatrix]] · [[Invertierbare Matrizen]] · [[Matrixmultiplikation]]
**Wird gebraucht für:** [[Äquivalente und ähnliche Matrizen]] · [[Diagonalisierbarkeit]] · Physik: [[Bezugssysteme und Scheinkräfte]]
