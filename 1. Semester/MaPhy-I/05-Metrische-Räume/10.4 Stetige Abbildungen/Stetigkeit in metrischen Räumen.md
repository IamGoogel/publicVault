---
modul: MaPhy I
fach: Mathematik
part: "Kap. 10.4"
keywords: continuity in metric spaces, limit, neighbourhood, isolated point
---

# Stetigkeit in metrischen Räumen

#maphy1 #metric-spaces #metric-continuity #atomic

*Umgebung* von $x_0$: $U\supseteq V\ni x_0$ mit $V$ offen; *punktierte Umgebung*: $U\setminus\{x_0\}$.

**Grenzwert.** $f:A\to Y$, $x_0$ **Häufungspunkt von $A$** (Voraussetzung!). $\lim_{x\to x_0}f(x)=y_0$, wenn zu jeder Umgebung $V$ von $y_0$ eine punktierte Umgebung $U$ von $x_0$ mit $f(U\cap A)\subseteq V$ existiert.

**Äquivalent.**
- Folgen: $x_n\to x_0$, $x_n\ne x_0$ ⇒ $f(x_n)\to y_0$.
- $\varepsilon$-$\delta$: $\forall\varepsilon\,\exists\delta:\ d(x,x_0)\le\delta\Rightarrow d'(f(x),y_0)\le\varepsilon$.

**Stetig in $x_0$:** $\lim_{x\to x_0}f(x)=f(x_0)$, äquivalent $x_n\to x_0\Rightarrow f(x_n)\to f(x_0)$. An isolierten Stellen ist die Bedingung leer (jede Abbildung dort stetig).

> [!tip] Praxis
> Folgenkriterium zum **Widerlegen** (zwei Folgen mit verschiedenen Bildlimiten), $\varepsilon$-$\delta$ zum **Beweisen**.

**Baut auf:** [[Funktionsgrenzwert]] · [[Stetigkeit einer Funktion]] · [[Konvergenz in metrischen Räumen]] · [[Offene und abgeschlossene Mengen in metrischen Räumen]]
**Wird gebraucht für:** [[Komposition stetiger Abbildungen]] · [[Banachscher Fixpunktsatz]]
