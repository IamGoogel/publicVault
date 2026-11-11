---
modul: MaPhy I
fach: Mathematik
part: "Kap. 10.4"
keywords: composition of continuous maps
---

# Komposition stetiger Abbildungen

#maphy1 #metric-spaces #metric-continuity #atomic

**Satz.** $f:X\to Y$ stetig in $x_0$, $g:Y\to Z$ stetig in $f(x_0)$ ⇒ $g\circ f$ stetig in $x_0$.

*Beweis:* $x_n\to x_0\Rightarrow f(x_n)\to f(x_0)\Rightarrow g(f(x_n))\to g(f(x_0))$.

```
x_n ──f──▶ f(x_n) ──g──▶ g(f(x_n))
 ↓            ↓                ↓
x_0       f(x_0)         g(f(x_0))
```

**Baut auf:** [[Stetigkeit in metrischen Räumen]] · [[Abbildung und Komposition]]
Reeller Spezialfall: [[Stetigkeit einer Funktion]].
