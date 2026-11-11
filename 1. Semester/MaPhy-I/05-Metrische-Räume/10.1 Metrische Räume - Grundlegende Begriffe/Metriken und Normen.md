---
modul: MaPhy I
fach: Mathematik
part: "Kap. 10.1"
keywords: metric, norm, discrete metric, p-norm
---

# Metriken und Normen

#maphy1 #metric-spaces #metric-basics #atomic

**Metrik.** $d:X\times X\to[0,\infty)$ mit
(i) $d(x,y)=0\iff x=y$; (ii) $d(x,y)=d(y,x)$; (iii) $d(x,y)\le d(x,z)+d(z,y)$.
Folgerung (umgekehrte Dreiecksungleichung): $\lvert d(x,y)-d(x,z)\rvert\le d(y,z)$.

**Norm** auf einem Vektorraum: $\lVert x\rVert=0\Rightarrow x=0$, $\lVert\alpha x\rVert=\lvert\alpha\rvert\lVert x\rVert$, Dreiecksungleichung.
**Lemma.** Jede Norm liefert eine Metrik $d(x,y)=\lVert x-y\rVert$ — aber nicht umgekehrt (die diskrete Metrik kommt von keiner Norm).

| Raum | Metrik |
|---|---|
| beliebige Menge | **diskrete Metrik**: $0$ für $x=y$, sonst $1$ |
| $\mathbb R^n$ | $d_p(x,y)=\bigl(\sum\lvert x_i-y_i\rvert^p\bigr)^{1/p}$ ($1\le p<\infty$), $d_\infty=\max\lvert x_i-y_i\rvert$ |
| $C([0,1];\mathbb R)$ | $d(f,g)=\max_x\lvert f(x)-g(x)\rvert$, Norm $\lVert f\rVert_\infty=\sup\lvert f\rvert$ |

- $p=2$: euklidischer Abstand. Es gilt: $d_p\le d_q$ für $1\le q\le p\le\infty$; für $n=1$ ist $d_p=\lvert x-y\rvert$ für alle $p$.
- Die Dreiecksungleichung von $d_p$ ist die [[Minkowski-Ungleichung]].
- Hölder in Normschreibweise: $\lvert x\cdot y\rvert_r\le\lvert x\rvert_p\lvert y\rvert_q$ für $\frac1r=\frac1p+\frac1q$ ([[Höldersche Ungleichung]]).

> [!warning] Axiom (iii) in der Physik
> Der Raumzeit-Abstand $s^2=(c\Delta t)^2-\Delta x^2$ ist **keine** Metrik in diesem Sinn (indefinit, Dreiecksungleichung verletzt) → [[Lorentz-Transformation und Minkowski-Diagramme]].

**Baut auf:** [[Minkowski-Ungleichung]] · [[Vektorraum]]
**Wird gebraucht für:** [[Kugeln und Isometrien]] · [[Offene und abgeschlossene Mengen in metrischen Räumen]]
