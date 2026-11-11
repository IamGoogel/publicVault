---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.5"
keywords: Hölder, Cauchy-Schwarz, power means
---

# Höldersche Ungleichung (inkl. Cauchy–Schwarz)

#maphy1 #foundations #inequalities #atomic

**Satz.** Für konjugierte $p,q$ ($\frac1p+\frac1q=1$) und $x_i,y_i\ge0$:
$$\sum x_iy_i\le\Bigl(\sum x_i^p\Bigr)^{1/p}\Bigl(\sum y_i^q\Bigr)^{1/q}.$$
*Beweis:* Normieren $\sum x_i^p=\sum y_i^q=1$, dann [[Youngsche Ungleichung]] summieren: $\sum x_iy_i\le\frac1p+\frac1q=1$.

**Folgerung (Potenzmittel).** Für $0<p<q$: $\bigl(\frac{x_1^p+\dots+x_n^p}n\bigr)^{1/p}\le\bigl(\frac{x_1^q+\dots+x_n^q}n\bigr)^{1/q}$.

**Allgemeine Form 1.5.5.** Für $\frac1r=\frac1p+\frac1q$:
$$\Bigl(\sum\lvert x_iy_i\rvert^r\Bigr)^{1/r}\le\Bigl(\sum\lvert x_i\rvert^p\Bigr)^{1/p}\Bigl(\sum\lvert y_i\rvert^q\Bigr)^{1/q}.$$

**Cauchy–Schwarz:** $p=q=2$, $r=1$: $\ \sum\lvert x_iy_i\rvert\le\lvert x\rvert_2\lvert y\rvert_2$; Gleichheit bei $x\parallel y$.

**Baut auf:** [[Youngsche Ungleichung]]
**Wird gebraucht für:** [[Minkowski-Ungleichung]] · [[Mittelwerte und ihre Ungleichungskette]] ($A\le Q$)
