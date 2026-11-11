---
modul: ExPhy I
fach: Physik
part: "Kap. 3.2, 3.2.1"
keywords: harmonic oscillator, complex ansatz, phasor, initial conditions
---

# Ungedämpfte Schwingung

#exphy1 #oscillations-waves #oscillation #atomic

**Eingenistete Modelle:** ungedämpft ⊂ gedämpft ⊂ erzwungen — streicht man Anregung, dann Dämpfung, bleibt der einfachste Fall.

**Schwingungsgleichung:** $m\ddot x+Kx=0$ (homogen, linear, 2. Ordnung, konstante Koeffizienten). Ansatz $x=ae^{i\omega t}$, $\ddot x=-\omega^2x$ ⇒ $(K-m\omega^2)a=0$, $a\ne0$ ⇒
$$\omega=\pm\omega_0,\qquad\omega_0=\sqrt{K/m}\quad(\text{Eigenkreisfrequenz})$$
Unabhängig von der Amplitude; diese wird durch die Anfangsbedingungen festgelegt.

**Reelle Lösung.** $x=ae^{i\omega_0t}+be^{-i\omega_0t}$; reell ⇒ $b=a^*$. Mit $a=c+id$:
$$x_0=2c,\qquad v_0=-2\omega_0d$$
Realteil legt die Anfangsauslenkung, Imaginärteil die Anfangsgeschwindigkeit fest. $v_0=0$: Phase $0$, $x_0$ = Amplitude. $v_0\ne0$: **$x_0$ ist nicht die Amplitude** (die Auslenkung wächst zunächst weiter).

Zeigerdarstellung: Zeiger der Länge $a$ läuft mit $\omega$ um, die Projektion auf die reelle Achse ist $a\cos\omega t$. Zeitnullpunkt frei: $\cos(\omega t+\varphi)$ ($\omega t+\varphi$ Phase, $\varphi$ Phasenverschiebung). Zusammenhang $\omega=2\pi\nu=2\pi/T$.

Beispiele: Federpendel, Fadenpendel ($T=2\pi\sqrt{\ell/g}$ bei kleinen Winkeln → [[Fadenpendel - Bestimmung von g]]), Torsionspendel ([[Torsionspendel]]).

**Baut auf:** [[Federkraft und harmonische Näherung]] · **Mathematik:** [[Rechenregeln und Gaußsche Zahlenebene]] · [[Konstruktion der komplexen Zahlen]]
**Wird gebraucht für:** [[Überlagerung von Schwingungen]] · [[Gedämpfte Schwingung]]
