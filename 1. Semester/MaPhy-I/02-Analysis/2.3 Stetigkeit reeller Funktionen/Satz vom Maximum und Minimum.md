---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.3"
keywords: extreme value theorem, compact interval, boundedness
---

# Satz vom Maximum und Minimum

#maphy1 #analysis #continuity #atomic

**Satz.** Ist $f:[a,b]\to\mathbb R$ stetig, so ist $f$ beschränkt und nimmt Maximum und Minimum an.

**Beweisidee.** Wäre $f$ unbeschränkt, gäbe es $x_n$ mit $\lvert f(x_n)\rvert\ge n$; eine konvergente Teilfolge ([[Satz von Bolzano-Weierstraß]]) $x_{n_k}\to x\in[a,b]$ widerspricht der Stetigkeit in $x$. Analog für das Supremum.

> [!warning] Keine Voraussetzung darf fehlen
> - $x^2$ auf $[-1,2)$: kein Maximum (nicht abgeschlossen).
> - $f(x)=1/x$ für $x\neq0$, $f(0)=0$, auf $[0,1]$: unbeschränkt (nicht stetig).
> - $x^3$ auf $[0,\infty)$: unbeschränkt (nicht beschränktes Intervall).

**Baut auf:** [[Stetigkeit einer Funktion]] · [[Satz von Bolzano-Weierstraß]]
