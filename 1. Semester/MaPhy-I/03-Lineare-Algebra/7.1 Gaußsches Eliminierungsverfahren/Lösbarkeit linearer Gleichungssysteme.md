---
modul: MaPhy I
fach: Mathematik
part: "Kap. 7.1"
keywords: linear system, solvability, rank criterion, free parameters
---

# Lösbarkeit linearer Gleichungssysteme

#maphy1 #linear-algebra #linear-systems #atomic

LGS $Ax=b$ mit $A\in\mathrm{Mat}_{m\times n}(K)$; erweiterte Matrix $(A\mid b)$. Spaltenform: $a_1x_1+\dots+a_nx_n=b$.

**Satz.** Ein LGS hat **keine, genau eine oder unendlich viele** Lösungen.

**Satz.** Lösbar ⇔ $\operatorname{rk}A=\operatorname{rk}(A\mid b)$ (⇔ $b\in\operatorname{span}\{a_1,\dots,a_n\}$).

**Satz (Normalform).** Es gibt invertierbare $M,N$ mit $MAN^{-1}=\begin{pmatrix}I_r&0\\0&0\end{pmatrix}$, $r=\operatorname{rk}A$. Mit $Nx=\binom y{y'}$, $Mb=\binom c{c'}$:
1. lösbar ⇔ $c'=0$;
2. dann $x=N^{-1}\binom c{y'}$ mit **beliebigem** $y'\in K^{n-r}$ ($n-r$ freie Parameter).

**Baut auf:** [[Rang und voller Rang]] · [[Äquivalente und ähnliche Matrizen]]
**Wird gebraucht für:** [[Gauß-Algorithmus und Zeilenoperationen]]
