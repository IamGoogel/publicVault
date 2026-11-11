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

> [!definition] Schwingungsgleichung (harmonischer Oszillator)
> Ohne Reibung und äußere Anregung:
> $$\ddot{x} + \omega_0^2\,x = 0$$
> Sie ist von zweiter Ordnung, linear und homogen; direktes Integrieren oder Separieren führt nicht zum Ziel. Stattdessen verwendet man einen Ansatz: Gesucht ist eine Funktion, die sich nach zweimaligem Ableiten bis auf einen Faktor reproduziert — die Exponentialfunktion. Mit $x = e^{\lambda t}$ ergibt sich die charakteristische Gleichung $\lambda^2 + \omega_0^2 = 0$, also $\lambda_{1,2} = \pm i\,\omega_0$. Die zwei Lösungen $e^{\pm i\omega_0 t}$ dürfen wegen der Linearität beliebig kombiniert werden; mit der Euler-Formel entstehen daraus Kosinus und Sinus.

> [!satz] Reelle Form
> Die allgemeine Lösung ist
> $$x(t) = a\cos(\omega_0 t) + b\sin(\omega_0 t), \qquad a = x(0), \quad b = \frac{\dot{x}(0)}{\omega_0}$$
> mit zwei frei wählbaren reellen Konstanten. Sie entspricht der komplexen Form $A\,e^{i\omega_0 t} + B\,e^{-i\omega_0 t}$.

> [!note] Häufiger Fehler: $\omega_0$ oder $\omega_0^2$ im Argument
> Hat die Gleichung die Gestalt $y'' + c\,y = 0$ mit positivem $c$, folgt aus dem Vergleich $\omega_0^2 = c$, also $\omega_0 = \sqrt{c}$. Im Argument von Sinus und Kosinus steht dann $\sqrt{c}\,x$ und nicht $c\,x$. Aus $y'' + 9y = 0$ ergibt sich $y = a\cos 3x + b\sin 3x$.
> Kontrolle durch Einsetzen: Für $y = \cos 9x$ ist $y'' = -81\cos 9x$, und $-81 \neq -9$; bei $y = \cos 3x$ gilt dagegen $y'' = -9y$.

> [!example]- Ursprung von $\omega_0$
> Federpendel: $m\ddot{z} = -k z$, mit $z$ gemessen von der Gleichgewichtslage, ergibt $\ddot{z} + \frac{k}{m}z = 0$, also $\omega_0 = \sqrt{k/m}$ und $T = 2\pi/\omega_0$. Beim Fadenpendel gilt $\omega_0 = \sqrt{g/\ell}$, allerdings erst nach der [[Kleinwinkelnäherung]] — das ist keine Umformung, sondern eine Annahme im Modell, siehe [[Pendelgleichung]].

Siehe auch: [[Randwertproblem]], [[Lösungsverfahren auswählen]], [[Polarform]], [[Separation der Variablen]]

**Weiterführend (1. Semester):** [[Ungedämpfte Schwingung]]
