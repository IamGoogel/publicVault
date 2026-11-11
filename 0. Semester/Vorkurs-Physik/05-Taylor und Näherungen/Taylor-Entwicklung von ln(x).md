---
modul: Vorkurs Physik
fach: Physik
semester: 0
part: "Thema Taylor und Näherungen"
Kurs: Vorkurs Physik
Verstaendnis: 0
gelesen: false
geuebt: false
tags: [vorkurs, vorkurs-physik]
---

> [!example]+ Taylor-Entwicklung von $\ln(x)$ um $x_0 = 1$ mit $N = 3$
> **Vorarbeit:** Ableitungen und ihre Werte an $x_0 = 1$
> $$\frac{d}{dx}\ln(x) = \frac{1}{x} \;\Rightarrow\; 1$$
> $$\frac{d^2}{dx^2}\ln(x) = -\frac{1}{x^2} \;\Rightarrow\; -1$$
> $$\frac{d^3}{dx^3}\ln(x) = \frac{2}{x^3} \;\Rightarrow\; 2$$
> Außerdem $\ln(1) = 0$ und die Fakultäten $\frac{1}{1!} = 1$, $\frac{1}{2!} = \frac{1}{2}$, $\frac{1}{3!} = \frac{1}{6}$ ([[Fakultät]]).
>
> **Einsetzen:**
> $$T^{3}_{\ln(x),\,x_0=1}(x) = 0 + 1\cdot 1\cdot(x-1) + \frac{1}{2}\cdot(-1)\cdot(x-1)^2 + \frac{1}{6}\cdot 2\cdot(x-1)^3$$
> $$= (x-1) - \frac{1}{2}(x-1)^2 + \frac{1}{3}(x-1)^3$$

Siehe auch: [[Taylor-Entwicklung]], [[Fakultät]], [[Taylor-Entwicklung berechnen]]
