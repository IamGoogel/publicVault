---
modul: Vorkurs Physik
fach: Physik
semester: 0
part: "Thema Volumen- und Flächenintegrale"
Kurs: Vorkurs Physik
Verstaendnis: 0
gelesen: false
geuebt: false
tags: [vorkurs, vorkurs-physik]
---

> [!definition] Volumenelement in verschiedenen Koordinaten
> Wie $dV$ aussieht, hängt vom Koordinatensystem ab: Ein Winkel ist keine Länge; erst $\varrho\,d\varphi$ ist eine.
> $$dV = dx\,dy\,dz, \qquad dV = \varrho\,d\varrho\,d\varphi\,dz, \qquad dV = r^2\sin\vartheta\,dr\,d\vartheta\,d\varphi$$
> Merkhilfe: Vor dem Integrieren multipliziert man $f$ mit einem Faktor — $1$, $\varrho$ oder $r^2\sin\vartheta$. Diesen zu vergessen, ist der häufigste Fehler bei krummlinigen Koordinaten; er bleibt unbemerkt, weil die Rechnung trotzdem sauber aufgeht.
> Wertebereiche: $\varrho, r \geq 0$, $\varphi \in [0,2\pi)$, $\vartheta \in [0,\pi]$. Der Polarwinkel $\vartheta$ wird von der positiven $z$-Achse aus gezählt; läuft er bis $2\pi$, wird jeder Punkt doppelt erfasst.

> [!satz] Zwei Grundintegrale für Kugelrechnungen
> $$\int_0^{2\pi}d\varphi = 2\pi, \qquad \int_0^\pi\sin\vartheta\,d\vartheta = \Big[-\cos\vartheta\Big]_0^\pi = 1 + 1 = 2$$
> Das zweite ist die einzige echte Integration; $-\cos\vartheta$ (nicht $+\cos\vartheta$) ist die Stammfunktion von $\sin\vartheta$.

> [!note] Vorgehen: Volumen- oder Flächenintegral ansetzen
> 1. Skizze anfertigen: Koordinatenachsen, den Körper hineinzeichnen, verdeckte Kanten gestrichelt, Maße ($a$, $R$, $h$) eintragen.
> 2. Koordinatensystem wählen: achsenparallele Kanten → kartesisch, Drehachse → zylindrisch, Mittelpunkt und Radius → sphärisch. Geeignet ist dasjenige, in dem die Grenzen konstant werden.
> 3. Das Element aufschreiben, mit Vorfaktor: drei Differentiale beim Volumen, zwei bei der Fläche.
> 4. Grenzen Achse für Achse bestimmen. Die Lage des Körpers entscheidet: „Mittelpunkt im Ursprung“ führt auf $-\frac{a}{2}$ bis $+\frac{a}{2}$, „Grundfläche bei $z=0$“ auf $0$ bis $h$. Bei einer Fläche ist eine Koordinate fest; sie wird eingesetzt statt integriert. Beim Fluss kommt zusätzlich die Projektion $\vec{F}\cdot\hat{e}_n$ hinzu.
> 5. Rechnen und kontrollieren: Konstanten herausziehen, wenn möglich das Integral zerlegen, sonst von innen nach außen vorgehen. Abschließend Einheiten ($[dV] = \mathrm{m^3}$, $[dA] = \mathrm{m^2}$), einen Grenzfall und die bekannte Formel vergleichen: Würfel $a^3$, Zylinder $\pi R^2 h$, Kugel $\frac{4}{3}\pi R^3$, Kugeloberfläche $4\pi R^2$.

> [!example]- Volumen eines Hohlzylinders
> Innenradius $R_1$, Außenradius $R_2$, Höhe $h$, Achse = $z$-Achse, Unterkante bei $z=0$. Wegen der Drehachse wählt man Zylinderkoordinaten: $\varrho$ von $R_1$ bis $R_2$, $\varphi$ einmal herum, $z$ von $0$ bis $h$. Der Integrand ist $f \equiv 1$ (der Faktor $\varrho$ gehört zum Volumenelement):
> $$V = \int_0^h\!\!\int_0^{2\pi}\!\!\int_{R_1}^{R_2}\varrho\,d\varrho\,d\varphi\,dz = \left[\frac{\varrho^2}{2}\right]_{R_1}^{R_2}\cdot 2\pi\cdot h = \pi\,(R_2^2 - R_1^2)\,h$$
> Kontrolle: Die Einheit ist $\mathrm{m^3}$, und für $R_1\to0$ ergibt sich $\pi R_2^2 h$, das Volumen des vollen Zylinders.

Siehe auch: [[Volumenintegral]], [[Zylinderkoordinaten]], [[Kugelkoordinaten]], [[Flächenelement der Kugel]]
