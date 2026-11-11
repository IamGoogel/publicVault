---
modul: Vorkurs Physik
fach: Physik
part: "Thema Integralrechnung"
keywords: linear argument, integration, substitution
---

# Integration mit linearem Argument

#vorkurs #vorkurs-physik

> [!satz] Lineares Argument
> Steht statt $x$ der Ausdruck $ax + b$ ($a \neq 0$, $b$ konstant), kommt der Faktor $\frac{1}{a}$ hinzu:
> $$\int f(ax+b)\,dx = \frac{1}{a}\,F(ax+b) + C, \qquad \int (ax+b)^n\,dx = \frac{(ax+b)^{n+1}}{a\,(n+1)} + C$$

> [!note] Herkunft des Faktors
> Er gleicht die innere Ableitung aus. Kontrolle: $\frac{1}{a}F(ax+b)$ nach $x$ abgeleitet ergibt $\frac{1}{a}\,f(ax+b)\cdot a = f(ax+b)$.
> Das gilt nur bei linearem Argument. Bei $e^{x^2}$ ist die innere Ableitung $2x$ nicht konstant, die Formel liefert nichts.

Siehe auch: [[Kettenregel]], [[Grundintegrale]], [[Substitution]], [[Partielle Integration]], [[Uneigentliches Integral]]
