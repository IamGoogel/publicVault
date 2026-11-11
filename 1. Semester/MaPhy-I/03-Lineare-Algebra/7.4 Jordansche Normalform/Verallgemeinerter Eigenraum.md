---
modul: MaPhy I
fach: Mathematik
part: "Kap. 7.4"
keywords: generalized eigenspace, kernel chain
---

# Verallgemeinerter Eigenraum

#maphy1 #linear-algebra #jordan #atomic

**Definition.**
$$E'(\lambda;T)=\bigcup_{j\ge1}\ker(\lambda I-T)^j=\ker(\lambda I-T)^{r_\lambda}.$$
**Lemma.** Die Kette $\ker(\lambda I-T)\subseteq\ker(\lambda I-T)^2\subseteq\dots$ wird bei $r_\lambda$ stationär.

**Satz.** Für die verschiedenen Eigenwerte $\lambda_1,\dots,\lambda_\sigma$:
$$V=E'(\lambda_1;T)\oplus\dots\oplus E'(\lambda_\sigma;T).$$

$\dim E'(\lambda)$ = algebraische Vielfachheit = Nullstellenordnung in $p_T$ = Summe der Blockgrößen zu $\lambda$.

**Baut auf:** [[Jordanblock und Jordansche Normalform]] · [[Kern und Bild]]
**Wird gebraucht für:** [[Vielfachheiten und Diagonalisierbarkeit]]
