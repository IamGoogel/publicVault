---
modul: Vorkurs Physik
fach: Physik
part: "Thema Komplexe Zahlen"
keywords: polar form, complex numbers, modulus, argument
---

# Polarform

#vorkurs #vorkurs-physik

> [!definition]
> Die **Polarform** einer [[Komplexe Zahl|komplexen Zahl]] $z$ ist
>
> $$z = |z|\,e^{i\varphi}$$
>
> mit dem Betrag $|z|$ und dem Winkel $\varphi$.

> [!example]+ Beispiel
> Gegeben: $z_1 = -1 + i,\ z_2 = 2i$.
>
> $$
> \begin{aligned}
> |z_1| &= \sqrt{(-1)^2 + 1^2} = \sqrt{2}, & \varphi_1 &= \arctan\left(\frac{v}{u}\right) + \pi = \frac{3\pi}{4} \\
> |z_2| &= \sqrt{2^2} = 2, & \varphi_2 &= \frac{\pi}{2}
> \end{aligned}
> $$
>
> $$z_1 = \sqrt{2}\,e^{i\,3\pi/4}, \qquad z_2 = 2\,e^{i\,\pi/2}$$
>
> **① Normalform:**
>
> $$z_1 \cdot z_2 = -2i - 2$$
>
> $$\frac{z_1}{z_2} = \frac{-1+i}{2i}\cdot\frac{-2i}{-2i} = \frac{1}{2}i + \frac{1}{2}$$
>
> **② Polarform:**
>
> $$z_1 \cdot z_2 = 2\sqrt{2}\,e^{i\,5\pi/4}$$
>
> $$\frac{z_1}{z_2} = \frac{\sqrt{2}\,e^{i\,3\pi/4}}{2\,e^{i\,\pi/2}}\cdot\frac{2\,e^{-i\,\pi/2}}{2\,e^{-i\,\pi/2}} = \frac{1}{\sqrt{2}}\,e^{i\,\pi/4}$$

Siehe auch: [[Koordinatenwechsel komplexer Zahlen]], [[Euler-Identität]], [[13.2 Die Gruppe der komplexen Zahlen ohne Null]], [[13.3 Komplexe Einheitswurzeln]], [[14.1 Die Eulersche Formel]], [[Winkel einer komplexen Zahl]], [[Schwingungsgleichung]]

**Weiterführend (1. Semester):** [[Rechenregeln und Gaußsche Zahlenebene]]
