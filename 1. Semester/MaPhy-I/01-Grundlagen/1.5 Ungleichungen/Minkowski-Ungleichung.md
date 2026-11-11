---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.5"
keywords: Minkowski, p-norm, triangle inequality
---

# Minkowski-Ungleichung

#maphy1 #foundations #inequalities #atomic

Für $p\ge1$ und $\lvert x\rvert_p=\bigl(\sum\lvert x_i\rvert^p\bigr)^{1/p}$ gilt die **Dreiecksungleichung**
$$\lvert x+y\rvert_p\le\lvert x\rvert_p+\lvert y\rvert_p .$$
Gilt auch für $p=\infty$, $\lvert x\rvert_\infty=\max\lvert x_i\rvert$. $p=1$: gewöhnliche Dreiecksungleichung; Beweis für $p>1$ über [[Höldersche Ungleichung]].

> [!warning] $p<1$
> Für $p<1$ gilt die Dreiecksungleichung **nicht** — dort ist $\lvert\cdot\rvert_p$ keine Norm.

```
Young ──▶ Hölder ──▶ Minkowski
              └──▶ Cauchy–Schwarz, A ≤ Q
```

**Baut auf:** [[Höldersche Ungleichung]]
**Wird gebraucht für:** [[Metriken und Normen]] ($p$-Normen auf $\mathbb R^n$)
