---
modul: Vorkurs Physik
fach: Physik
part: "Thema Differentialrechnung"
keywords: chain rule, derivative
---

# Kettenregel

#vorkurs #vorkurs-physik

> [!satz] Kettenregel
> Ist eine Funktion in das Argument einer anderen eingesetzt, gilt
> $$f(x) = u\big(g(x)\big) \;\Rightarrow\; f'(x) = u'\big(g(x)\big)\cdot g'(x)$$
> also „äußere Ableitung mal innere Ableitung“. Benennt man die innere Größe, lautet sie
> $$\frac{df}{dx} = \frac{df}{dg}\,\frac{dg}{dx}$$
> Formal kürzt man $dg$ weg und setzt am Ende für $g$ wieder $g(x)$ ein.

> [!note] Woran man sie erkennt, und der Standardfehler
> Hinweis auf eine Verkettung ist eine Klammer oder ein Exponent, in dem mehr als nur $x$ steht. Am häufigsten wird beim Ableiten der Faktor $g'(x)$ vergessen. Beispiel: $f = e^{ax}$ mit $g = ax$ liefert $a\,e^{ax}$.

> [!example]- Mehrere Variablen
> Bei $f(x,y,z) = u\big(v(x,y,z)\big)$ ist $\frac{\partial f}{\partial x} = u'(v)\cdot\frac{\partial v}{\partial x}$. Für $f(x,y) = \ln(x^3 y)$ mit $v = x^3 y$ folgt:
> $$\frac{\partial f}{\partial x} = \frac{1}{x^3 y}\cdot 3x^2 y = \frac{3}{x}, \qquad \frac{\partial f}{\partial y} = \frac{1}{x^3 y}\cdot x^3 = \frac{1}{y}$$
> Kontrolle: Im Ergebnis von $\frac{\partial f}{\partial x}$ darf kein $y$ mehr vorkommen, obwohl $f$ von $y$ abhängt.

Siehe auch: [[Ableitungsregeln]], [[Partielle Ableitung]], [[Standardableitungen]], [[Produktregel]], [[Integration mit linearem Argument]], [[Substitution]], [[Gradient]]
