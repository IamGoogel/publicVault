---
modul: MaPhy I
fach: Mathematik
part: "Kap. 10.3"
keywords: closure, interior, boundary, accumulation point
---

# Abschluss, Inneres und Rand

#maphy1 #metric-spaces #metric-topology #atomic

| Begriff | Definition |
|---|---|
| Abschluss $\bar A$ | $\bigcap\{F\supseteq A\mid F\text{ abgeschlossen}\}$ (kleinste abgeschlossene Obermenge) |
| Inneres $A^\circ$ | $\bigcup\{U\subseteq A\mid U\text{ offen}\}$ (größte offene Teilmenge) |
| Rand $\partial A$ | $\bar A\setminus A^\circ$ (abgeschlossen) |
| Häufungspunkte $A'$ | Grenzwerte von Folgen in $A$ mit $x_n\ne\bar x$ |

**Lemma.** $\bar A=A\cup A'=A\cup\partial A$. Folglich: $A$ abgeschlossen ⇔ $A'\subseteq A$ ⇔ jede in $X$ konvergente Folge aus $A$ hat ihren Grenzwert in $A$.

**Lemma.** $\bar x\in\partial A$ ⇔ jede offene Umgebung von $\bar x$ trifft $A$ **und** $X\setminus A$. Disjunkte Zerlegung $X=A^\circ\cup(X\setminus A)^\circ\cup\partial A$.

> [!example] Beispiel
> $X=\mathbb R^2$, $A=[0,1)\times[0,1)$: $\bar A=[0,1]^2$, $A^\circ=(0,1)^2$, $\partial A=\{(x,y)\in[0,1]^2\mid x\in\{0,1\}\text{ oder }y\in\{0,1\}\}$.

**Baut auf:** [[Offene und abgeschlossene Mengen in metrischen Räumen]] · [[Konvergenz in metrischen Räumen]] · [[Abschluss und Dichtheit]]
**Wird gebraucht für:** [[Vollständigkeit]] (abgeschlossene Teilmengen)
