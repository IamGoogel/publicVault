---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.1"
keywords: Cauchy criterion, completeness of the reals
---

# Cauchy-Kriterium

#maphy1 #analysis #sequences #atomic

**Theorem.** In $\mathbb R$ gilt: $(a_n)$ konvergent ⇔ $(a_n)$ Cauchyfolge.

```
Cauchy ─▶ beschränkt ─▶ (Bolzano–Weierstraß) konvergente Teilfolge
       ─▶ ganze Folge konvergiert
```

> [!important] Nutzen
> Konvergenz zeigen, **ohne den Grenzwert zu kennen**. Beispiel: $a_n=\sum_{k=1}^n\frac1{k^2}$ ist Cauchy, denn für $n>m\ge N$ gilt (Teleskopsumme, $\frac1{k^2}<\frac1{k(k-1)}$)
> $\lvert a_n-a_m\rvert<\frac1m-\frac1n<\frac1N\le\varepsilon$.
> Der Grenzwert $\pi^2/6$ wird erst im Kapitel Reihen gezeigt.

> [!warning] Nur in vollständigen Räumen
> In $\mathbb Q$ falsch. Vollständigkeit eines metrischen Raums wird genau so definiert → [[Vollständigkeit und Banachscher Fixpunktsatz]].

**Baut auf:** [[Cauchyfolge]] · [[Satz von Bolzano-Weierstraß]]
**Wird gebraucht für:** [[Vollständigkeit und Banachscher Fixpunktsatz]]
