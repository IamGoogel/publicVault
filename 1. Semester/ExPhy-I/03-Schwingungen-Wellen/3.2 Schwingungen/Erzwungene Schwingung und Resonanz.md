---
modul: ExPhy I
fach: Physik
part: "Kap. 3.2.4"
keywords: forced oscillation, resonance curve, phase shift, resonance catastrophe
---

# Erzwungene Schwingung und Resonanz

#exphy1 #oscillations-waves #oscillation #atomic

$$m\ddot x+r\dot x+Kx=F_0\cos(\omega_Et)$$
Lösung: $x=x_\text{hom}+x_\text{stat}$. $x_\text{hom}$ (freie Eigenschwingung) klingt mit $e^{-\gamma t}$ ab; $x_\text{stat}$ schwingt mit der **Erregerfrequenz** $\omega_E$, nicht mit $\omega_0$. Die Amplitude $a$ kürzt sich diesmal nicht heraus (rechte Seite $\ne0$):
$$|a|=\frac{F_0/m}{\sqrt{(\omega_0^2-\omega_E^2)^2+(2\gamma\omega_E)^2}}$$

- Kleine Dämpfung und $\omega_E\to\omega_0$: Nenner klein, Amplitude groß. Ohne Dämpfung wird der Nenner bei $\omega_E=\omega_0$ exakt null — **Resonanzkatastrophe**.
- Mit Dämpfung: endliches Maximum nahe $\omega_0$; mit wachsender Dämpfung wird es **flacher, breiter** und wandert zu **kleineren** Frequenzen.
- Stationär: $x_\text{stat}=A(\omega_E)\cos(\omega_Et-\delta)$ mit
$$\tan\delta=\frac{r\omega_E/m}{\omega_0^2-\omega_E^2}\qquad\Bigl(\tfrac rm=2\gamma\Bigr)$$
Bei kleinem $\omega_E$ nahezu phasengleich, oberhalb der Resonanz nahezu **gegenphasig**. Der Nenner der Resonanzkurve lässt sich auch schreiben als $\sqrt{(\omega_0^2-\omega_E^2)^2+(r\omega_E/m)^2}$, identisch zu $2\gamma\omega_E$ oben.
- Technische Beispiele: aerodynamisches Flattern, periodische Wirbelablösung an Brückenfahrbahnen (Anregung durch die Strömung selbst; vgl. [[Zirkulation und Wirbel]]).

**Baut auf:** [[Gedämpfte Schwingung]] · **Mathematik:** [[Rechenregeln und Gaußsche Zahlenebene]] (Betrag einer komplexen Zahl)
**Wird gebraucht für:** [[Gekoppelte Schwingungen]]
