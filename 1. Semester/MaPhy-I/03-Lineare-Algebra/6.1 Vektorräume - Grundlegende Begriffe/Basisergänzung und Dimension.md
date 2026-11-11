---
modul: MaPhy I
fach: Mathematik
part: "Kap. 6.1"
keywords: basis extension, basis exchange, dimension
---

# Basisergänzung und Dimension

#maphy1 #linear-algebra #basis #atomic

**Basisergänzungssatz (6.1.13).** Sind $u_1,\dots,u_r$ linear unabhängig und $w_1,\dots,w_s$ ein Erzeugendensystem von $V$, so lässt sich $u_1,\dots,u_r$ durch passende $w_j$ zu einer Basis ergänzen.

**Basisaustauschsatz (6.1.14).** Sind $u,v$ Basen, so lässt sich jedes $u_i$ durch ein $v_j$ ersetzen, so dass wieder eine Basis entsteht.

**Satz.** Alle Basen haben gleich viele Elemente ⇒ $\dim V$ ist wohldefiniert.

| Folgerung | |
|---|---|
| $n>\dim V$ Vektoren | linear abhängig |
| $U\subseteq V$ | $\dim U\le\dim V$, Gleichheit ⇔ $U=V$ (endlichdim.) |
| $\dim K^n=n$ | $\dim C([0,1];\mathbb R)=\infty$ |

> [!warning] Dimension hängt vom Grundkörper ab
> $\dim_{\mathbb C}\mathbb C=1$, aber $\dim_{\mathbb R}\mathbb C=2$; allgemein $\dim_{\mathbb R}V=2\dim_{\mathbb C}V$.

**Baut auf:** [[Linear unabhängig und Basis]]
**Wird gebraucht für:** [[Abbildungsmatrix]] · [[Rang und voller Rang]]
