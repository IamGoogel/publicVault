---
modul: MaPhy I
fach: Mathematik
part: "Kap. 6.2"
keywords: matrix, linear map, standard basis
---

# Matrix als lineare Abbildung

#maphy1 #linear-algebra #matrices #atomic

$\mathrm{Mat}_{m\times n}(K)$: $m$ Zeilen, $n$ Spalten; $K$-Vektorraum der Dimension $mn$. Jede Matrix $A=(a_{ij})$ definiert eine lineare Abbildung
$$T:K^n\to K^m,\quad x\mapsto Ax,\qquad y_i=\sum_ja_{ij}x_j .$$

**Lemma.** Jede lineare Abbildung $K^n\to K^m$ entsteht so: mit $Te_j=\sum_ia_{ij}f_i$ ist $T$ durch $A$ gegeben. Die $j$-te **Spalte** von $A$ ist das Bild $Te_j$.

$$L(K^n,K^m)\ \cong\ \mathrm{Mat}_{m\times n}(K)\quad\text{(kanonisch, wegen der Standardbasen)}$$

**Baut auf:** [[Lineare Abbildung]] · [[Linear unabhängig und Basis]] (Standardbasis)
**Wird gebraucht für:** [[Matrixmultiplikation]] · [[Abbildungsmatrix]]
