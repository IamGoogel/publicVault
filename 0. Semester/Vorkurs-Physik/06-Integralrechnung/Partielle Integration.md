---
modul: Vorkurs Physik
fach: Physik
semester: 0
part: "Thema Integralrechnung"
Kurs: Vorkurs Physik
Verstaendnis: 0
gelesen: false
geuebt: false
tags: [vorkurs, vorkurs-physik]
---

> [!satz] Partielle Integration
> Integriert man die Produktregel $(f g)' = f' g + f g'$ auf beiden Seiten und stellt um, erhält man
> $$\int f'(x)\,g(x)\,dx = f(x)\,g(x) - \int f(x)\,g'(x)\,dx$$
> Man löst das Integral dabei nicht, sondern ersetzt es durch ein anderes — das einfacher wird, wenn man die Faktoren geschickt zuordnet.

> [!note] Zwei Schreibweisen, eine Merkregel
> Man findet die Regel auch mit vertauschten Rollen, $\int f\,g'\,dx = f g - \int f'\,g\,dx$. Beide Versionen stimmen, aber wer sie durcheinanderbringt, ordnet die Faktoren falsch zu.
> Besser merkt man sich, was zu tun ist: Einen Faktor integrieren, den anderen ableiten — und zwar die Potenz von $x$ ableiten, weil sie dabei kleiner wird ($x \to 1$, $x^2 \to 2x$) und nach ein bis zwei Schritten ganz wegfällt.

> [!example]- $\int x\,e^{cx}\,dx$ (mit der ersten Schreibweise)
> Gewählt: $f' = e^{cx}$, also $f = \frac{1}{c}e^{cx}$ (Faktor $\frac{1}{c}$ nach [[Integration mit linearem Argument]]); $g = x$, also $g' = 1$:
> $$\int x\,e^{cx}\,dx = \tfrac{1}{c}\,e^{cx}\,x - \int \tfrac{1}{c}\,e^{cx}\cdot 1\,dx = \tfrac{1}{c}\,x\,e^{cx} - \tfrac{1}{c^2}\,e^{cx} + C$$
> Kontrolle durch Ableiten (Produktregel): $\tfrac{1}{c}e^{cx} + x\,e^{cx} - \tfrac{1}{c}e^{cx} = x\,e^{cx}$. Die umgekehrte Wahl $f' = x$, $g = e^{cx}$ führt nicht weiter, weil im neuen Integral eine höhere Potenz von $x$ steht.

> [!note] Zwei nützliche Tricks
> - Eine Eins ergänzen: Man darf jede Funktion mit dem Faktor $1$ versehen: $f(x) = 1\cdot f(x)$. Mit $f' = 1$, also $f = x$, wird der einzige echte Faktor abgeleitet; so ergibt sich $\int \ln x\,dx = x(\ln x - 1) + C$.
> - Zyklisches Wiederauftreten: Taucht nach zwei Schritten das ursprüngliche Integral wieder auf, hat man eine Gleichung, die man nach ihm auflöst. Hilfreich sind dabei Umformungen des [[Trigonometrischer Pythagoras|trigonometrischen Pythagoras]]: $\sin^2\alpha = 1 - \cos^2\alpha$ und $\frac{1}{\cos^2\alpha} = 1 + \frac{\sin^2\alpha}{\cos^2\alpha}$.

Siehe auch: [[Produktregel]], [[Substitution]], [[Grundintegrale]]
