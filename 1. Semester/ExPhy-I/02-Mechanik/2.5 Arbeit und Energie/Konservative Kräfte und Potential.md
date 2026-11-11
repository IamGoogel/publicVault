---
modul: ExPhy I
fach: Physik
part: "Kap. 2.5.4"
keywords: conservative force, potential energy, curl, energy conservation
---

# Konservative Kräfte und Potential

#exphy1 #mechanics #energy #atomic

**Definition:** $\oint\mathbf F\cdot d\mathbf r=0$ für **alle** geschlossenen Wege (unpraktikabel). Nachrechenbar: $\operatorname{rot}\mathbf F=0$.
**Folge:** $W(A\to B)=-W(B\to A)$; die Arbeit ist **wegunabhängig**.

**Potentielle Energie:** Arbeit gegen die Kraft von $P_0$ nach $P_A$:
$$V(\mathbf r)=-\int_{P_0}^{\mathbf r}\mathbf F\cdot d\mathbf r^\prime,\qquad\mathbf F=-\nabla V$$
Der Bezugspunkt $P_0$ ist frei (Erdoberfläche, bzw. $\infty$ bei Gravitation/Coulomb); $V$ ist nur bis auf eine **Konstante** bestimmt, physikalisch zählen Differenzen.

**Energieerhaltung:** $E=T+V=$ const.

> [!info] Planetenbahn
> Bei rein gravitativer Wechselwirkung bleibt $E$ erhalten, $T$ und $V$ variieren gegeneinander — daher ändert sich die Bahngeschwindigkeit auf der Ellipse.

> [!warning] Voraussetzung für $\operatorname{rot}\mathbf F=0$
> Das Rotationskriterium gilt als Äquivalenz auf einfach zusammenhängenden Gebieten (Satz von Stokes); lokal ist es nur notwendig.

**Baut auf:** [[Arbeit und Wegintegral]] · [[Leistung und kinetische Energie]]
**Wird gebraucht für:** [[Federkraft und harmonische Näherung]] · [[Bernoulli-Gleichung]] · [[Noether-Theorem und Galilei-Gruppe]]
