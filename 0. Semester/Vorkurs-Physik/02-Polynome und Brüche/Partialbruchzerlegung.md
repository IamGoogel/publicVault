---
modul: Vorkurs Physik
fach: Physik
part: "Thema Polynome und Brüche"
keywords: partial fractions, rational function
---

# Partialbruchzerlegung

#vorkurs #vorkurs-physik

> [!definition]
> Bei der **Partialbruchzerlegung** wird ein Bruch $\frac{P(x)}{Q(x)}$ mit dem Ansatz
>
> $$\frac{P(x)}{Q(x)} \overset{!}{=} \frac{A}{x-x_1} + \frac{B}{x-x_2} + \ldots + \frac{?}{x-x_n}$$
>
> zerlegt.
>
> Voraussetzung: $\operatorname{grad} P(x) \le \operatorname{grad} Q(x)$ ?
>
> Anmerkung (grün): $n$ entspricht dem Grad von $Q$ ?
>
> Anwendung bei der Integration:
>
> $$\int \frac{P(x)}{Q(x)}\,dx = \int \frac{A}{x-x_1}\,dx + \int \frac{B}{x-x_2}\,dx + \ldots$$

> [!definition] Vorgehen
> 1. Nullstellen der Nennerfunktion bestimmen
> 2. Ansatz aufstellen und mit dem Nenner multiplizieren
> 3. Gleichungssystem (I, II, III) lösen ?
> 4. Zusammenfassen

> [!example]+ Beispiel
> $$\frac{x+2}{x(x^2-1)} \overset{!}{=} \frac{A}{x-x_1} + \frac{B}{x-x_2} + \frac{C}{x-x_3}$$
>
> **① Nullstellen des Nenners:** $x(x^2-1) \overset{!}{=} 0$, also $x_1 = 0,\ x_2 = -1,\ x_3 = 1$.
>
> **② Ansatz:**
>
> $$\frac{x+2}{x(x^2-1)} = \frac{A}{x-0} + \frac{B}{x+1} + \frac{C}{x-1}$$
>
> Multiplikation mit $x(x^2-1) = (x-1)\cdot x\cdot(x+1)$:
>
> $$
> \begin{aligned}
> x+2 &= \left(\frac{A}{x} + \frac{B}{x+1} + \frac{C}{x-1}\right)\cdot x(x^2-1) \\
> &= A(x^2-1) + B(x-1)\,x + C\,x\,(x+1) \\
> &= Ax^2 - A + Bx^2 - Bx + Cx^2 + Cx \\
> x+2 &= x^2(A+B+C) + x(C-B) - A
> \end{aligned}
> $$
>
> **③ Gleichungssystem:**
>
> - I: $0 = A + B + C$
> - II: $1 = C - B$
> - III: $-2 = A$
>
> Aus I mit $A = -2$: $2 = B + C$, also $2 - B = C$. In II: $1 = 2 - B - B \Rightarrow -1 = -2B \Rightarrow B = \tfrac{1}{2}$. In I: $C = 2 - \tfrac{1}{2} = \tfrac{3}{2}$.
>
> **④ Zusammenfassen:**
>
> $$\frac{x+2}{x(x^2-1)} = -\frac{2}{x} + \frac{1}{2(x+1)} + \frac{3}{2(x-1)}$$


Siehe auch: [[13.9 Partialbruchzerlegung komplexer Polynome]], [[13.11 Partialbruchzerlegung reeller Polynome]], [[4.3 Lineare Gleichungssysteme]], [[Gebrochen-rationale Funktion]], [[Polynomdivision]], [[Logarithmische Integration]]
