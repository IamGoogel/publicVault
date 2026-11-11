---
modul: Vorkurs Physik
fach: Physik
semester: 0
part: "Thema Differentialgleichungen"
Kurs: Vorkurs Physik
Verstaendnis: 0
gelesen: false
geuebt: false
tags: [vorkurs, vorkurs-physik]
---

> [!definition] Anfangswert- und Randwertproblem
> Werden beide Bedingungen an derselben Stelle vorgegeben (Anfangswertproblem), lassen sich die Konstanten $a$ und $b$ der [[Schwingungsgleichung]] direkt ablesen. Liegen sie an verschiedenen Stellen (Randwertproblem, z. B. $y(0)$ und $y(\pi/2)$), muss man ein kleines Gleichungssystem lösen. Dabei werden Sinuswerte bei Vielfachen von $\frac{\pi}{2}$ benötigt.

> [!example]- $y'' + 9y = 0$ mit $y(0) = 0$ und $y(\pi/2) = 2$
> Vergleich mit der Schwingungsgleichung: $\omega_0 = 3$, also $y(x) = a\cos 3x + b\sin 3x$. Aus $y(0) = a = 0$ folgt $y = b\sin 3x$. Mit $\sin\frac{3\pi}{2} = -1$ ergibt die zweite Bedingung:
> $$y(\pi/2) = b\sin\frac{3\pi}{2} = -b \overset{!}{=} 2 \;\Rightarrow\; b = -2$$
> Lösung: $y(x) = -2\sin 3x$. Kontrolle: $y'' = 18\sin 3x = -9y$ ✓, $y(0) = 0$ ✓, $y(\pi/2) = 2$ ✓. Statt $y''$ ein zweites Mal abzuleiten, kann man die Gleichung nutzen: $y'' = -9y$.

Siehe auch: [[Allgemeine und spezielle Lösung]], [[Schwingungsgleichung]]
