---
modul: MaPhy I
fach: Mathematik
part: "Kap. 6.2"
keywords: rank, row rank, column rank, full rank
---

# Rang und voller Rang

#maphy1 #linear-algebra #rank #atomic

$\operatorname{rk}A=\dim\operatorname{im}A$ = **Spaltenrang** (max. Zahl linear unabhängiger Spalten); **Zeilenrang** = $\operatorname{rk}A^T$.

**Satz.** Zeilenrang = Spaltenrang.
*Beweisidee:* Basis $v_1..v_n$ von $K^n$ mit $v_{r+1..n}$ Basis von $\ker A$; $w_i=Av_i$ ($i\le r$) linear unabhängig, zur Basis von $K^m$ ergänzen. Dann $A\sim\begin{pmatrix}I_r&0\\0&0\end{pmatrix}$; Äquivalenz ändert keinen der beiden Ränge.

**Folgerung.** $\operatorname{rk}A\le\min\{m,n\}$; $A,A'\in\mathrm{Mat}_{m\times n}$ äquivalent ⇔ gleicher Rang.

**Lemma (voller Rang).**
| Fall | äquivalent |
|---|---|
| $m\ge n$ | voller Rang ⇔ $A$ injektiv ⇔ Linksinverse $B$, $BA=I_n$ |
| $m\le n$ | voller Rang ⇔ $A$ surjektiv ⇔ Rechtsinverse $B$, $AB=I_m$ |
| $m=n$ | invertierbar |

**Baut auf:** [[Kern und Bild]] · [[Basisergänzung und Dimension]] · [[Äquivalente und ähnliche Matrizen]]
**Wird gebraucht für:** [[Lösbarkeit linearer Gleichungssysteme]] · [[Invertierbare Matrizen]]
