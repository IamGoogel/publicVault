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

> [!definition] Der einfachste Fall: direktes Integrieren
> Steht rechts die gesuchte Funktion nicht, ist weder ein Ansatz noch ein besonderes Verfahren nötig: $y'(x) = f(x)$ verlangt lediglich eine [[Stammfunktion]]. So folgt aus $\dot{v} = -g$ sofort $v(t) = -g\,t + v_0$. Bei zweiter Ordnung integriert man zweimal.

> [!note] Der häufigste Fehler
> Beim zweiten Integrieren wird aus $C_1$ der Term $C_1 x$: Die Konstante aus dem ersten Schritt ist nun ein normaler Summand und wird mitintegriert.
> $$y'' = x \;\Rightarrow\; y' = \tfrac{1}{2}x^2 + C_1 \;\Rightarrow\; y = \tfrac{1}{6}x^3 + C_1 x + C_2$$
> Die allgemeine Lösung von $y'' = f(x)$ endet also stets auf $+C_1 x + C_2$ — zwei Konstanten für zweite Ordnung. Mit nur $+C_1 + C_2$ geht ein Teil der Lösungen verloren.

Siehe auch: [[Integrationskonstante]], [[Allgemeine und spezielle Lösung]], [[Lösungsverfahren auswählen]]
