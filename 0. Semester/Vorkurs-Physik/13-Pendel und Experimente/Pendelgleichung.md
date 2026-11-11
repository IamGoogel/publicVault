---
modul: Vorkurs Physik
fach: Physik
part: "Thema Pendel und Experimente"
keywords: pendulum equation, differential equation, small angle
---

# Pendelgleichung

#vorkurs #vorkurs-physik

> [!definition] Pendelgleichung
> Für ein Fadenpendel mit Auslenkwinkel $\varphi(t)$ gilt
> $$\varphi''(t) + \frac{g}{\ell}\,\sin\varphi(t) = 0$$
> Das ist eine nichtlineare Differentialgleichung zweiter Ordnung und schwer zu lösen, denn die gesuchte Funktion tritt sowohl als zweite Ableitung als auch im Argument des Sinus auf.

> [!satz] Mit der Kleinwinkelnäherung lösbar
> Setzt man $\sin\varphi \approx \varphi$, bleibt $\varphi'' + \frac{g}{\ell}\varphi = 0$, also die Form $\varphi'' = -\omega^2 \varphi$ der harmonischen Schwingung. Aus dem Vergleich folgt $\omega^2 = g/\ell$ und
> $$T = \frac{2\pi}{\omega} = 2\pi\sqrt{\frac{\ell}{g}}$$
> Kontrollen: $\sqrt{\ell/g}$ hat die Einheit einer Zeit, die Masse taucht nicht auf, und $\ell = 1\,\mathrm{m}$ liefert das Sekundenpendel mit $T = 2{,}0\,\mathrm{s}$.

> [!note] Der Preis dafür
> Die Näherung macht die Gleichung zwar lösbar, schränkt aber den Gültigkeitsbereich ein. Es handelt sich nicht um eine reine Umformung, sondern um eine Annahme im Modell.

Siehe auch: [[Fadenpendel]], [[Kleinwinkelnäherung]], [[Schwingungsgleichung]], [[Gültigkeitsbereich einer Näherung]]

**Weiterführend (1. Semester):** [[Ungedämpfte Schwingung]]
