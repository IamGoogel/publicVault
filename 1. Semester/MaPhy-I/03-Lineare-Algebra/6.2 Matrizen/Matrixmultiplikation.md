---
modul: MaPhy I
fach: Mathematik
part: "Kap. 6.2"
keywords: matrix product, non-commutative
---

# Matrixmultiplikation

#maphy1 #linear-algebra #matrices #atomic

$$\mathrm{Mat}_{m\times n}\times\mathrm{Mat}_{n\times p}\to\mathrm{Mat}_{m\times p},\qquad c_{ik}=\sum_{j=1}^na_{ij}b_{jk}$$
**Formatregel:** Spaltenzahl links = Zeilenzahl rechts. Das Produkt entspricht der Komposition der Abbildungen ([[Matrix als lineare Abbildung]]).

**Satz.**
| Eigenschaft | gilt? |
|---|---|
| assoziativ $(AB)C=A(BC)$ | ja |
| distributiv | ja |
| neutrales Element $I_mA=AI_n=A$ | ja |
| kommutativ | **nein** (i. A. ab $m\ge2$) |

> [!example] Nichtkommutativ
> $\begin{pmatrix}1&1\\0&1\end{pmatrix}\begin{pmatrix}1&0\\1&1\end{pmatrix}=\begin{pmatrix}2&1\\1&1\end{pmatrix}\ne\begin{pmatrix}1&1\\1&2\end{pmatrix}=\begin{pmatrix}1&0\\1&1\end{pmatrix}\begin{pmatrix}1&1\\0&1\end{pmatrix}$

> [!warning] Existenz
> $AB$ kann existieren, $BA$ nicht (Format).

**Baut auf:** [[Matrix als lineare Abbildung]] · [[Abbildung und Komposition]]
**Wird gebraucht für:** [[Invertierbare Matrizen]] · [[Basiswechsel]] · [[Determinante]] ($\det(AB)=\det A\det B$)
