---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.3"
keywords: limit of a function, epsilon-delta, sequence criterion, one-sided limit
---

# Funktionsgrenzwert

#maphy1 #analysis #continuity #atomic

**Voraussetzung.** $f:I\to\mathbb R$ und $b$ ein **Häufungspunkt von $I$** ([[Häufungspunkt und isolierter Punkt]]). Ohne diese Bedingung ist der Grenzwert nicht definiert.

**Definition.** $\lim_{x\to b}f(x)=L$, wenn zu jeder Umgebung $V$ von $L$ eine punktierte Umgebung $U$ von $b$ existiert mit $f(U\cap I)\subseteq V$.

**Äquivalente Formen.**
- $\varepsilon$-$\delta$: $\forall\varepsilon>0\ \exists\delta>0\ \forall x\in I,\ 0<\lvert x-b\rvert\le\delta:\ \lvert f(x)-L\rvert\le\varepsilon$.
- *Folgenkriterium:* $f(x_n)\to L$ für **jede** Folge $x_n\to b$ mit $x_n\ne b$, $x_n\in I$.

**Einseitige Grenzwerte** $f(b\pm0)$; Heaviside: $H(+0)=1$, $H(-0)=0$.

> [!example] Beispiele 2.3.2
> $\lim_{x\to2}x^2=4$. $f(x)=\frac{x^2-1}{x-1}$ ($x\ne1$), $f(1)=1$: $\lim_{x\to1}f=2\ne f(1)$. $\lim_{x\to0}\frac1{\lvert x\rvert}=\infty$. $\lim_{x\to0}\sin\frac1x$ **existiert nicht** (zwei Folgen mit verschiedenen Bildlimiten).

> [!tip] Praxis
> Folgenkriterium zum **Widerlegen**, $\varepsilon$-$\delta$ zum **Beweisen**.

**Baut auf:** [[Konvergenz einer Folge]] · [[Häufungspunkt und isolierter Punkt]]
**Wird gebraucht für:** [[Stetigkeit einer Funktion]] · [[Rechenregeln für Funktionsgrenzwerte]] · [[Unstetigkeitsstellen]]
