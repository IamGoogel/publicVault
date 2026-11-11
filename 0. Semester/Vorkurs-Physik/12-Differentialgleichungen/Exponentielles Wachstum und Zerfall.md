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

> [!satz] Exponentielles Wachstum und Zerfall
> Ist die Änderungsrate einer Größe proportional zur Größe selbst, gilt
> $$\frac{dN}{dt} = k\,N \;\Rightarrow\; N(t) = N_0\,e^{kt}, \qquad N_0 = N(0)$$
> Für $k>0$ wächst die Größe, für $k<0$ nimmt sie ab (Zerfall); dann setzt man $k = -\gamma$ mit $\gamma>0$. Mit [[Separation der Variablen]] erhält man für $\dot{n} = -\gamma n$ nach Schritt 3 die Gleichung $\ln|n| = -\gamma t + C$, nach dem Exponenzieren $n = C\,e^{-\gamma t}$ und mit $n(0) = n_0$ das Zerfallsgesetz.

> [!note] Einheiten und charakteristische Größen
> - Die Konstante hat die Einheit einer inversen Zeit, $[k] = 1/\mathrm{s}$, da im Exponenten eine reine Zahl stehen muss. Prozentangaben lassen sich direkt umsetzen: „acht Prozent pro Stunde“ bedeutet $k = 0{,}08/\mathrm{h}$.
> - Mit $\gamma = |k|$ ergeben sich die Zeitkonstante $\tau = 1/\gamma$ sowie Halbwerts- bzw. Verdopplungszeit $t_{1/2} = \ln 2/\gamma$; beide hängen nicht vom Startwert ab.
> - Zur Übersetzung von Text in Gleichungen: „Änderungsrate“ steht für eine Zeitableitung, „proportional zu $X$“ für den Faktor $k\cdot X$, „bremst“ oder „nimmt ab“ für ein Minuszeichen.

> [!example]- Auslaufender Gleiter
> Die Reibung sei proportional zur Geschwindigkeit: $\dot{v} = -\gamma v$ mit $\gamma = 0{,}50/\mathrm{s}$, Anfangsgeschwindigkeit $v_0 = 2{,}0\,\mathrm{m/s}$, Startort $x(0) = 0$. Das ist die Zerfallsgleichung, also $v(t) = v_0\,e^{-\gamma t}$. Den Ort erhält man durch Integration (Integrationsvariable mit Strich; $x(0) = 0$ ist schon in der unteren Grenze berücksichtigt):
> $$x(t) = \int_0^t v(t')\,dt' = \left[-\frac{v_0}{\gamma}\,e^{-\gamma t'}\right]_0^t = \frac{v_0}{\gamma}\left(1 - e^{-\gamma t}\right)$$
> Erst am Ende Zahlen einsetzen: Für $t\to\infty$ strebt $e^{-\gamma t}$ gegen null, also $\lim_{t\to\infty}x(t) = \frac{v_0}{\gamma} = 4{,}0\,\mathrm{m}$; die Einheit stimmt, $[v_0/\gamma] = \mathrm{m/s}\cdot\mathrm{s} = \mathrm{m}$. Streng genommen steht der Gleiter nie still, rollt aber höchstens vier Meter weit.

Siehe auch: [[Uneigentliches Integral]], [[Integrale in der Physik]], [[Änderungsrate]]
