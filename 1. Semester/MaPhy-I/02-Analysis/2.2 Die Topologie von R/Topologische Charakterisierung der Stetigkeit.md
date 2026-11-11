---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.2"
keywords: continuity, preimage, open sets, closure
---

# Topologische Charakterisierung der Stetigkeit

#maphy1 #analysis #topology #continuity #atomic

**Satz.** Für $f:I\to\mathbb R$ sind äquivalent:
1. $f$ ist stetig auf $I$.
2. $f^{-1}(U)$ ist offen in $I$ für jede offene Menge $U\subseteq\mathbb R$.
3. $f^{-1}(V)$ ist abgeschlossen in $I$ für jede abgeschlossene Menge $V\subseteq\mathbb R$.
4. $f\bigl(I\cap\overline B\bigr)\subseteq\overline{f(B)}$ für alle $B\subseteq I$.

Beweiskette: (1) ⇒ (2) ⇒ (3) ⇒ (4) ⇒ (1).

> [!important] Urbild, nicht Bild
> Stetige Funktionen erhalten Offenheit **nicht** unter dem *Bild*, sondern unter dem *Urbild*. Urbilder $f^{-1}(U)$ sind immer definiert, auch ohne Bijektivität → [[Abbildungen]].

**Baut auf:** [[Stetigkeit einer Funktion]] · [[Relative Topologie]] · [[Abschluss und Dichtheit]] · [[Rechenregeln für offene und abgeschlossene Mengen]]
**Verallgemeinerung:** [[Stetige Abbildungen in metrischen Räumen]]
