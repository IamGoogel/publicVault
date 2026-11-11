---
modul: Vorkurs Physik
fach: Physik
part: "Thema Volumen- und Flächenintegrale"
keywords: volume integral, integration
---

# Volumenintegral

#vorkurs #vorkurs-physik

> [!definition] Volumenintegral
> Für ein Skalarfeld $f$ über einem Raumgebiet $V$:
> $$\int_V f(x,y,z)\,dV = \iiint_V f(x,y,z)\,dx\,dy\,dz, \qquad V = \int_V dV$$
> Es handelt sich um drei ineinander verschachtelte gewöhnliche Integrale, die von innen nach außen berechnet werden. Bei der Integration über $x$ gelten $y$ und $z$ als konstant. Setzt man den einfachsten Integranden $f \equiv 1$, liefert jedes Teilvolumen genau seinen eigenen Beitrag, und man erhält das Volumen. Mit $f = \rho$ ergibt sich die Masse.

> [!satz] Zerlegung in ein Produkt
> Häufig lässt sich das Integral in ein Produkt einfacher Integrale aufspalten. Das geht, wenn der Integrand ein Produkt von Funktionen jeweils nur einer Variablen ist und alle Grenzen Konstanten sind:
> $$\int_{z_1}^{z_2}\!\int_{y_1}^{y_2}\!\int_{x_1}^{x_2} g(x)\,h(y)\,k(z)\,dx\,dy\,dz = \left(\int_{x_1}^{x_2} g\,dx\right)\left(\int_{y_1}^{y_2} h\,dy\right)\left(\int_{z_1}^{z_2} k\,dz\right)$$
> Beide Voraussetzungen müssen erfüllt sein. Ein konstanter Integrand ergibt die Länge des Intervalls: $\int_{u_1}^{u_2}du = u_2 - u_1$. Konstante Faktoren kann man herausziehen; „konstant“ bedeutet: unabhängig von der Variablen, nach der gerade integriert wird.

Siehe auch: [[Volumenelement]], [[Linearität des Integrals]], [[Satz von Gauß]]

**Weiterführend (1. Semester):** [[Trägheitsmoment und Satz von Steiner]]
