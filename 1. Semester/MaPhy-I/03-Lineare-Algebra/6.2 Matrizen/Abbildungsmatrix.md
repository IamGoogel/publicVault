---
modul: MaPhy I
fach: Mathematik
part: "Kap. 6.2"
keywords: matrix of a linear map, bases, differentiation
---

# Abbildungsmatrix

#maphy1 #linear-algebra #change-of-basis #atomic

Basen $v_1,\dots,v_n$ von $V$ und $w_1,\dots,w_m$ von $W$ liefern $V\cong K^n$, $W\cong K^m$. Die *Abbildungsmatrix* $A$ von $T$ ist bestimmt durch
$$Tv_j=\sum_ia_{ij}w_i,\quad\text{d. h.}\quad(Tv_1\ \dots\ Tv_n)=(w_1\ \dots\ w_m)A .$$
**Spalte $j$** = Koordinaten von $Tv_j$ in der Basis $w$.

```
   V ──── T ────▶ W
   │≅            │≅        kommutatives Diagramm,
   ▼             ▼         die Isomorphismen hängen von den Basen ab
  K^n ─── A ───▶ K^m
```

> [!example] Beispiel (Ableitung)
> $P_3\to P_2$, $a_3x^3+a_2x^2+a_1x+a_0\mapsto3a_3x^2+2a_2x+a_1$ hat in den Basen $(1,x,x^2,x^3)$, $(1,x,x^2)$ die Matrix $\begin{pmatrix}0&1&0&0\\0&0&2&0\\0&0&0&3\end{pmatrix}$ ($\dim P_m=m+1$).

**Baut auf:** [[Lineare Abbildung]] · [[Linear unabhängig und Basis]] · [[Matrix als lineare Abbildung]]
**Wird gebraucht für:** [[Basiswechsel]] · [[Eigenwerte und charakteristisches Polynom]]
