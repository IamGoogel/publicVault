---
modul: ExPhy I
fach: Physik
part: "Kap. 2.9.3"
keywords: torsion pendulum, calibration, moment of inertia measurement
---

# Torsionspendel (Messung von Trägheitsmomenten)

#exphy1 #mechanics #rigid-body #atomic

Drehteller ($I_0$) an einer Torsionsfeder: Rückstellmoment $N=-D\varphi$ (Richtgröße $D$). Mit $I\ddot\varphi=N$:
$$I\ddot\varphi+D\varphi=0,\qquad T=2\pi\sqrt{I/D}$$
Gleiche Gestalt wie die Federschwingung ([[Ungedämpfte Schwingung]]); die messbare Größe $T$ hängt nur vom Trägheitsmoment ab.

1. **Eichung:** Scheibe $(M,R)$ mit $I=I_0+\tfrac12MR^2$: $T^2-T_0^2=\dfrac{4\pi^2}{D}\cdot\tfrac12MR^2$ ⇒ $D$ bestimmbar; $I_0$ fällt heraus.
2. **Messung** des Körpers mit unbekanntem $I_K$.
3. **Umrechnung** auf die Schwerpunktachse mit [[Trägheitsmoment und Satz von Steiner]].

*Beispiel:* $M=0{,}800$ kg, $R=0{,}120$ m, $T_0=1{,}50$ s → $T=2{,}10$ s: $D=2\pi^2MR^2/(T^2-T_0^2)\approx0{,}105$ N m, $I_0=DT_0^2/4\pi^2\approx6{,}0\cdot10^{-3}$ kg m² (Kontrolle: $I_0+\tfrac12MR^2=DT^2/4\pi^2\approx0{,}0118$ kg m²).

**Baut auf:** [[Trägheitsmoment und Satz von Steiner]] · [[Zufällige und systematische Fehler]]
