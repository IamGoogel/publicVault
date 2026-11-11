---
modul: Vorkurs Physik
fach: Physik
part: "Thema Volumen- und Flächenintegrale"
keywords: Gauss's theorem, divergence theorem, flux
---

# Satz von Gauß

#vorkurs #vorkurs-physik

> [!satz] Satz von Gauß (Divergenzsatz)
> Für ein Vektorfeld $\vec{F}$ und ein Volumen $V$, dessen Rand $\partial V$ eine geschlossene Fläche ist, gilt
> $$\underbrace{\int_V\nabla\cdot\vec{F}\,dV}_{\text{Summe aller Quellen und Senken}} = \underbrace{\oint_{\partial V}\vec{F}\cdot d\vec{A}}_{\text{Fluss durch die Oberfläche}}$$
> Links wird über das Innere integriert, rechts über den Rand; beide Seiten sind Zahlen. $\oint$ kennzeichnet die geschlossene Fläche; die Normale zeigt nach außen, sodass ein positiver Fluss einen Netto-Ausstrom bedeutet.

> [!note] Elektrostatik
> Die Elektrostatik verwendet diese Form: $\nabla\cdot\vec{E} = \rho/\varepsilon_0$. Man sollte beide Seiten berechnen können. Beim Fluss eines Coulomb-Feldes taucht der Radius im Ergebnis nicht mehr auf: Für den Fluss zählt nur, was eingeschlossen ist.

Siehe auch: [[Divergenz]], [[Fluss durch eine Fläche]], [[Volumenintegral]], [[Maxwell-Gleichungen]]
