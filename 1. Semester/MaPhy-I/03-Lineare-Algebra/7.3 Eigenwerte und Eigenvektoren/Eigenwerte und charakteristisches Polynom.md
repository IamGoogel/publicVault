---
modul: MaPhy I
fach: Mathematik
part: "Kap. 7.3"
keywords: eigenvalue, eigenvector, characteristic polynomial, trace
---

# Eigenwerte und charakteristisches Polynom

#maphy1 #linear-algebra #eigenvalues #atomic

**Voraussetzung:** $K$ algebraisch abgeschlossen (z. B. $\mathbb C$, nicht $\mathbb R$), $\dim V=n$. Eigentlich genügt: $p_T$ zerfällt in Linearfaktoren ([[Fundamentalsatz der Algebra]]).

| Begriff | Definition |
|---|---|
| Eigenraum | $E(\lambda;T)=\ker(\lambda I-T)=\{v\mid Tv=\lambda v\}$ |
| Eigenwert | $\lambda$ mit $\dim E(\lambda;T)>0$ |
| Eigenvektor | $v\in E(\lambda;T)$, $v\ne0$ |
| charakteristisches Polynom | $p_T(\mu)=\det(\mu I-T)$ |

$p_T$ ist monisch vom Grad $n$:
$$p_T(\mu)=\mu^n-\alpha_1\mu^{n-1}+\alpha_2\mu^{n-2}\mp\dots+(-1)^n\alpha_n,\quad\alpha_1=\operatorname{tr}T,\ \alpha_n=\det T .$$

- **Lemma:** $\lambda$ Eigenwert ⇔ $p_T(\lambda)=0$.
- **Lemma:** $\operatorname{tr}T=a_{11}+\dots+a_{nn}$; $\operatorname{tr}(TS)=\operatorname{tr}(ST)$, obwohl i. A. $TS\ne ST$.

> [!example] Beispiel
> $A=\begin{pmatrix}0&1\\-2&3\end{pmatrix}$: $p_A(\mu)=\mu^2-3\mu+2=(\mu-1)(\mu-2)$, $E(1)=\operatorname{span}\binom11$, $E(2)=\operatorname{span}\binom12$ — Basis von $\mathbb C^2$.

> [!warning] Konstanter Koeffizient
> Er ist $(-1)^n\det T$, nicht $\det T$.

**Baut auf:** [[Determinante]] · [[Kern und Bild]] · [[Basiswechsel]] (Spur/Determinante basisunabhängig)
**Wird gebraucht für:** [[Diagonalisierbarkeit]]
**Physik:** Hauptachsen: [[Kreisel und freie Achsen]] · Normalmoden: [[Gekoppelte Schwingungen]]
