---
modul: ExPhy I
fach: Physik
part: "Kap. 1.3.1–1.3.3"
keywords: mean, variance, standard deviation, frequency distribution
---

# Mittelwert und Standardabweichung

#exphy1 #measurement #statistics #atomic

**Häufigkeitsverteilung:** Messwerte in Klassen der Breite $\Delta x$ (äquidistant oder logarithmisch). Kenngrößen: *Positionsparameter* (Mittelwert) und *Dispersionsparameter* (Streubereich).

**Mittelwert.** Gefordert: $Q=\sum(x_i-\bar x)^2=\min$. Ableiten nach $\bar x$:
$$\frac{dQ}{d\bar x}=-2\sum x_i+2n\bar x=0\ \Rightarrow\ \bar x=\frac1n\sum_{i=1}^nx_i$$
Das arithmetische Mittel ist keine Konvention, sondern der Wert mit minimaler Quadratsumme. Der *wahre Wert* $x_w=\lim_{n\to\infty}\bar x$ ist nie zugänglich.

**Standardabweichung.**
$$\sigma^2=\frac1{n-1}\sum_{i=1}^n(x_i-\bar x)^2\qquad(n\ge2)$$
Nenner $n-1$, weil $\bar x$ aus denselben Daten gewonnen wurde. Aus **einer** Messung lässt sich keine Streuung bestimmen.

**Angabe:** $\bar x\pm\sigma$, relativ $\sigma/\bar x$; z. B. $1{,}99\,\mathrm s\ (2\,\%)=(1{,}99\pm0{,}04)\,\mathrm s$.

**Mathematisch:** [[Mittelwerte und ihre Ungleichungskette]] · [[Konvergenz einer Folge]] ($n\to\infty$)
**Wird gebraucht für:** [[Normalverteilung]] · [[Fehler des Mittelwerts]]
