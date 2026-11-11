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

> [!definition] Integration durch Substitution
> Sie ist die Umkehrung der [[Kettenregel]]: Die Ableitung von $F(u(x))$ ist $f(u(x))\,u'(x)$; umgekehrt gilt
> $$\int f\big(u(x)\big)\,u'(x)\,dx = \int f(u)\,du$$
> Technisch: Aus $\frac{du}{dx} = u'(x)$ folgt $du = u'(x)\,dx$, und das setzt man ein.

> [!note] Vorgehen in fünf Schritten
> 1. $u(x)$ wählen — meist das, was in einer Klammer, unter einer Wurzel, im Exponenten oder im Nenner steht.
> 2. Differential umschreiben: $\frac{du}{dx}$ berechnen und $dx$ durch $du$ ersetzen.
> 3. Einsetzen und prüfen: Im neuen Integral darf kein $x$ mehr vorkommen; sonst taugt die Wahl nicht.
> 4. In der Variablen $u$ integrieren.
> 5. Abschluss auf einem von zwei Wegen: Beim unbestimmten Integral wird zurücksubstituiert. Beim bestimmten Integral rechnet man die Grenzen um; dann braucht man nicht zurückzusubstituieren.

> [!example]- $\int_a^b \frac{1}{Ax+B}\,dx$ mit $A \neq 0$
> Mit $u = Ax + B$ gilt $dx = \frac{1}{A}\,du$; die Grenzen werden zu $u(a) = Aa + B$ und $u(b) = Ab + B$:
> $$\int_a^b \frac{dx}{Ax+B} = \frac{1}{A}\int_{Aa+B}^{Ab+B}\frac{du}{u} = \frac{1}{A}\Big[\ln|u|\Big]_{Aa+B}^{Ab+B} = \frac{1}{A}\Big(\ln|Ab+B| - \ln|Aa+B|\Big)$$
> Ohne Grenzen: $\int \frac{dx}{Ax+B} = \frac{1}{A}\ln|Ax+B| + C$. Kontrolle: Ableiten liefert $\frac{1}{A}\cdot\frac{1}{Ax+B}\cdot A = \frac{1}{Ax+B}$.

> [!note] Häufiger Fehler: Grenzen nicht umgerechnet
> Nach dem Substituieren müssen an den Integralgrenzen die Werte der neuen Variablen stehen, also $u(a)$ und $u(b)$. Prüffrage: Gehören die Grenzen zu der Variablen, die im Differential steht? Beispiel $u = 2x+1$: Aus $[1,3]$ wird $[3,7]$.

Siehe auch: [[Logarithmische Integration]], [[Integration mit linearem Argument]], [[Partielle Integration]], [[Potential aus Kraftfeld bestimmen]]
