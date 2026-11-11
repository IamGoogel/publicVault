---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.1"
keywords: limsup, liminf, limit set, extended real numbers
---

# Limes superior und Limes inferior

#maphy1 #analysis #sequences #atomic

Arbeit in $\overline{\mathbb R}=\mathbb R\cup\{\pm\infty\}$: dort besitzt **jede** Teilmenge Supremum und Infimum.

**Limesmenge.** $\operatorname{Lim}(a_n)$ = Menge aller Häufungswerte ([[Teilfolge und Häufungswert]]).
$$\limsup a_n=\sup\operatorname{Lim}(a_n),\qquad \liminf a_n=\inf\operatorname{Lim}(a_n).$$

**Lemma.**
$$\limsup a_n=\inf_{m}\sup_{n\ge m}a_n,\qquad \liminf a_n=\sup_{m}\inf_{n\ge m}a_n .$$

**Kriterium.** $\lim a_n$ existiert (in $\overline{\mathbb R}$) ⇔ $\liminf a_n=\limsup a_n$; dann ist dies der Limes.

> [!example] Beispiel
> Die Folge $1,-1,0,\ 1,-2,0,\ 1,-3,0,\dots$ hat $\operatorname{Lim}=\{-\infty,0,1\}$, $\liminf=-\infty$, $\limsup=1$.

**Baut auf:** [[Teilfolge und Häufungswert]] · [[Bestimmte Divergenz und Rechnen mit Unendlich]] · [[Axiome der reellen Zahlen]]
