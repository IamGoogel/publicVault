---
modul: MaPhy I
fach: Mathematik
part: "Kap. 6.1"
keywords: linear independence, basis, coordinates
---

# Linear unabhängig und Basis

#maphy1 #linear-algebra #basis #atomic

| Begriff | Definition |
|---|---|
| Linearkombination | $\sum_k\alpha_kv_k$ |
| linear unabhängig | $\sum\alpha_kv_k=0\Rightarrow$ alle $\alpha_k=0$ |
| Basis | linear unabhängig **und** $\operatorname{span}=V$ |

**Lemma.** $u_1,\dots,u_m$ linear abhängig ⇔ ein $u_j$ ist Linearkombination der übrigen.

**Lemma.** Bezüglich einer Basis hat jedes $v$ eine **eindeutige** Darstellung $v=\sum\alpha_ku_k$ ⇒ bijektive lineare Zuordnung $V\to K^m$ (*basisabhängig*).

- Standardbasis $e_j=(0,\dots,1,\dots,0)$ von $K^m$.
- Unendlichdimensional: $\mathbb R[x]$ mit Basis $1,x,x^2,\dots$.

> [!tip] Praxis in $K^n$
> $n$ Vektoren sind eine Basis ⇔ linear unabhängig ⇔ $\det\ne0$ → [[Determinante]].

**Baut auf:** [[Untervektorraum und Erzeugnis]]
**Wird gebraucht für:** [[Basisergänzung und Dimension]] · [[Abbildungsmatrix]]
