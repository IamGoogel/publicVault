---
modul: MaPhy I
fach: Mathematik
part: "Kap. 7.4"
keywords: Jordan block, Jordan normal form
---

# Jordanblock und Jordansche Normalform

#maphy1 #linear-algebra #jordan #atomic

**Jordanblock** $J_r(\lambda)$: $r\times r$, $\lambda$ auf der Diagonale, $1$ auf der Nebendiagonale darüber:
$$J_r(\lambda)=\begin{pmatrix}\lambda&1&&\\&\lambda&\ddots&\\&&\ddots&1\\&&&\lambda\end{pmatrix}.$$

**Theorem.** Zu $T\in L(V)$ ($K$ algebraisch abgeschlossen) gibt es eine Basis, in der die Matrix blockdiagonal $\operatorname{diag}(J_{r_1}(\lambda_1),\dots,J_{r_\ell}(\lambda_\ell))$ ist, $r_1+\dots+r_\ell=n$. Die Blöcke sind bis auf Reihenfolge **eindeutig**; $p_T(\mu)=\prod_j(\mu-\lambda_j)^{r_j}$.

**Beispiel.** $\begin{pmatrix}\lambda&0\\0&\lambda\end{pmatrix}$ und $\begin{pmatrix}\lambda&1\\0&\lambda\end{pmatrix}$ haben beide $p=(\mu-\lambda)^2$, aber Eigenraum $\mathbb C^2$ bzw. nur $\operatorname{span}\binom10$.

**Beispiel.** $J_2(\lambda)\oplus J_1(\lambda)\oplus J_1(\lambda')$: $p_A=(\mu-\lambda)^3(\mu-\lambda')$, $\dim E(\lambda)=2$ (zwei Blöcke), $\dim E'(\lambda)=3$.

> [!tip] Verbindung zur Analysis/Physik
> Ein Jordanblock zu $\lambda$ erzeugt in Differentialgleichungen Lösungen $te^{\lambda t}$ — der aperiodische Grenzfall der Dämpfung → [[Gedämpfte und erzwungene Schwingung]].

**Baut auf:** [[Diagonalisierbarkeit]] · [[Äquivalente und ähnliche Matrizen]]
**Wird gebraucht für:** [[Verallgemeinerter Eigenraum]] · [[Vielfachheiten und Diagonalisierbarkeit]]
