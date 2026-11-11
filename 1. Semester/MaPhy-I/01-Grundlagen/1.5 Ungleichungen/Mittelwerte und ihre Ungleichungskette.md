---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.5"
keywords: harmonic, geometric, arithmetic, quadratic mean
---

# Mittelwerte und ihre Ungleichungskette

#maphy1 #foundations #inequalities #atomic

Für $a_1,\dots,a_n>0$:

| Mittel | Formel |
|---|---|
| harmonisch $H$ | $\dfrac n{\frac1{a_1}+\dots+\frac1{a_n}}$ |
| geometrisch $G$ | $\sqrt[n]{a_1\cdots a_n}$ |
| arithmetisch $A$ | $\dfrac{a_1+\dots+a_n}n$ |
| quadratisch $Q$ | $\sqrt{\dfrac{a_1^2+\dots+a_n^2}n}$ |

**Satz.** $\min a_i\le H\le G\le A\le Q\le\max a_i$. Gleichheit an *einer* Stelle der Kette ⇔ alle $a_i$ gleich.

*Beweisideen.* $H\ge\min$: Nenner $\le n/m$. $H\le G$ folgt aus $G\le A$ für $1/a_i$. $G\le A$ per [[Vollständige Induktion]] (o. B. d. A. $a_n\le A\le a_{n+1}$, dann $(A-a_n)(a_{n+1}-A)\ge0$). $A\le Q$ aus [[Höldersche Ungleichung]]. $Q\le\max$ trivial.

> [!warning] Positivität
> Für $G,A,Q$ genügt $a_i\ge0$; mit $H$ braucht man $a_i>0$ (Kehrwerte).

**Verwendung in der Physik:** [[Messreihen und Normalverteilung]] (Mittelwert) · $v_w<\bar v<v_\text{rms}$ in der [[Kinetische Gastheorie|kinetischen Gastheorie]].
**Wird gebraucht für:** [[Rekursive Folgen und Konvergenznachweis]] (AM–GM)
