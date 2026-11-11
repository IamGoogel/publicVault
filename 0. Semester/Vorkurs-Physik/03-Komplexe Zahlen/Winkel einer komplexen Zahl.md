---
modul: Vorkurs Physik
fach: Physik
part: "Thema Komplexe Zahlen"
keywords: argument, phase, complex numbers
---

# Winkel einer komplexen Zahl

#vorkurs #vorkurs-physik

> [!definition]
> Der Winkel $\varphi$ von $z = u + iv$ folgt aus
>
> $$\tan(\varphi) = \frac{v}{u} \;\Rightarrow\; \arctan\left(\frac{v}{u}\right) = \varphi$$
>
> **Achtung:** $x \mapsto \arctan(x)$ bildet $\mathbb{R}$ auf das [[Intervalle|Intervall]] $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$ ab. Fallunterscheidung:
>
> $$
> \varphi = \begin{cases}
> \arctan\left(\frac{v}{u}\right), & u > 0 \\
> \arctan\left(\frac{v}{u}\right) + \pi, & u < 0,\ v \ge 0 \\
> \arctan\left(\frac{v}{u}\right) - \pi, & u < 0,\ v \le 0 \\
> \frac{\pi}{2}, & u = 0,\ v > 0 \\
> -\frac{\pi}{2}, & u = 0,\ v < 0
> \end{cases}
> $$

> [!example]+ Beispiel
> $z = 4 + 2i$, gesucht: $|z|$ und $\varphi$.
>
> $$|z| = \sqrt{u^2 + v^2} = \sqrt{20}$$
>
> $$\tan(\varphi) = \frac{v}{u} \;\Rightarrow\; \arctan\left(\frac{v}{u}\right) = \varphi = \arctan\left(\frac{1}{2}\right)$$

Siehe auch: [[Betrag einer komplexen Zahl]], [[Polarform]], [[2.3 Umkehrabbildung]], [[13.2 Die Gruppe der komplexen Zahlen ohne Null]], [[Komplexe Zahl]]
