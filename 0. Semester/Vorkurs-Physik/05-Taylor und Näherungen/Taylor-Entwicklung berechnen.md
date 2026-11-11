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

> [!definition] Vorgehen: Taylor-Entwicklung von $f$ um $x_0$ bis zur Ordnung $N$
> 1. Kehrwerte der Fakultäten notieren: $\frac{1}{1!} = 1$, $\frac{1}{2!} = \frac{1}{2}$, $\frac{1}{3!} = \frac{1}{6}$, $\frac{1}{4!} = \frac{1}{24}$.
> 2. Den Wert $f(x_0)$ bestimmen. Ist er null, so verschwindet dieser Term — er fehlt nicht einfach.
> 3. Erst alle Ableitungen $f', \dots, f^{(N)}$ bilden, danach an der Stelle $x_0$ einsetzen; die Reihenfolge nicht umkehren.
> 4. Die Werte in die [[Taylor-Entwicklung]] einsetzen und summieren: Kehrwert der Fakultät, Ableitungswert und $(x - x_0)^n$ werden multipliziert.
> 5. Kontrolle: Bei $x = x_0$ muss $f(x_0)$ herauskommen, und das Polynom muss dort die Ableitung $f'(x_0)$ haben.

> [!example]- $\sin x$ um $x_0 = 0$, zweite Ordnung
> $f(0) = 0$; $f'(x) = \cos x$, also $f'(0) = 1$; $f''(x) = -\sin x$, also $f''(0) = 0$. Eingesetzt:
> $$T^{(2)}(x) = 0 + 1\cdot(x - 0) + \tfrac{1}{2}\cdot 0\cdot(x-0)^2 = x$$
> Der erste und der dritte Summand haben den Wert null. Kontrolle: $T^{(2)}(0) = 0 = \sin 0$; die Ableitung des Polynoms ist $1 = \cos 0$. Daraus ergibt sich die [[Kleinwinkelnäherung]] $\sin x \approx x$.

Siehe auch: [[Taylor-Entwicklung]], [[Taylor-Entwicklung von ln(x)]], [[Fakultät]], [[Gerade und ungerade Funktion]]
