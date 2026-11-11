---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.3"
keywords: continuity, epsilon-delta, composition, polynomials
---

# Stetigkeit einer Funktion

#maphy1 #analysis #continuity #atomic

**Definition.** $f:I\to\mathbb R$ ist *stetig in $c\in I$*, wenn $\lim_{x\to c}f(x)=f(c)$ (für isoliertes $c\in I$ ist die Bedingung leer, $f$ dort automatisch stetig).

**Äquivalent.**
- Folgen: $x_n\to c\Rightarrow f(x_n)\to f(c)$.
- $\varepsilon$-$\delta$: $\forall\varepsilon\,\exists\delta\,\forall x\in I:\ \lvert x-c\rvert\le\delta\Rightarrow\lvert f(x)-f(c)\rvert\le\varepsilon$.

**Sätze 2.3.10, 2.3.12.** Summen, Produkte, Quotienten (mit $g(c)\ne0$) und **Kompositionen** stetiger Funktionen sind stetig. Polynome sind stetig auf $\mathbb R$, rationale Funktionen $p/q$ überall, wo $q\ne0$.

```
x_n ─f─▶ f(x_n) ─g─▶ g(f(x_n))   Komposition: Folgenkriterium zweimal
```

> [!warning] Zu verwechseln
> *Grenzwert in $c$* existiert vs. *stetig in $c$*: zusätzlich muss $c\in I$ und der Grenzwert gleich $f(c)$ sein.

**Baut auf:** [[Funktionsgrenzwert]] · [[Rechenregeln für Funktionsgrenzwerte]]
**Wird gebraucht für:** [[Zwischenwertsatz]] · [[Satz vom Maximum und Minimum]] · [[Topologische Charakterisierung der Stetigkeit]] · [[Umkehrfunktion stetiger monotoner Funktionen]] · metrisch: [[Stetige Abbildungen in metrischen Räumen]]
