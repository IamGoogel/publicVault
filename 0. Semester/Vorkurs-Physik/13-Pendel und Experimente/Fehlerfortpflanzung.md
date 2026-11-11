---
modul: Vorkurs Physik
fach: Physik
semester: 0
part: "Thema Pendel und Experimente"
Kurs: Vorkurs Physik
Verstaendnis: 0
gelesen: false
geuebt: false
tags: [vorkurs, vorkurs-physik]
---

> [!satz] Fehlerfortpflanzung
> Kennt man die Eingangsgrößen von $d$ nur mit Unsicherheiten $\Delta\omega_0$, $\Delta v_0$, $\dots$, wirkt jede davon gemäß dem [[Differential]] auf $d$, und die Beträge werden addiert:
> $$\Delta d = \left|\frac{\partial d}{\partial\omega_0}\right|\Delta\omega_0 + \left|\frac{\partial d}{\partial v_0}\right|\Delta v_0 + \dots$$
> Die Betragsstriche verhindern, dass sich Beiträge mit entgegengesetztem Vorzeichen aufheben; berechnet wird die größtmögliche Abweichung.

> [!note] Gewichtung und Einheitenkontrolle
> Die partiellen Ableitungen wirken als Gewichte: Sie zeigen, wie stark sich die Unsicherheit einer einzelnen Größe auf das Ergebnis auswirkt. Bei $\Delta\omega_0 = 0{,}1/\mathrm{s}$ muss $\frac{\partial d}{\partial\omega_0}$ die Einheit $\mathrm{m\,s}$ besitzen, bei $\Delta v_0 = 0{,}1\,\mathrm{m/s}$ die Einheit $\mathrm{s}$ — erst dadurch erhält jeder Summand die Dimension einer Länge.

> [!example]- Horizontaler Wurf
> Ein Ball rollt von einer Tischkante der Höhe $H$ mit der waagerechten Geschwindigkeit $v_0$ und trifft in der Entfernung $d = v_0\sqrt{2H/g}$ auf. Messwerte: $v_0 = 2{,}0\,\mathrm{m/s}$ mit $\Delta v_0 = 0{,}1\,\mathrm{m/s}$ sowie $H = 0{,}80\,\mathrm{m}$ mit $\Delta H = 0{,}01\,\mathrm{m}$. Mit $g \approx 10\,\mathrm{m/s^2}$ ergibt sich die Fallzeit $t = 0{,}40\,\mathrm{s}$ und $d = 0{,}80\,\mathrm{m}$.
> 1. Gewichte: $\frac{\partial d}{\partial v_0} = \sqrt{2H/g} = 0{,}40\,\mathrm{s}$ und $\frac{\partial d}{\partial H} = v_0\sqrt{\frac{2}{g}}\cdot\frac{1}{2\sqrt{H}} = \frac{d}{2H} = 0{,}50$.
> 2. Einsetzen: $\Delta d = 0{,}40\,\mathrm{s}\cdot0{,}1\,\mathrm{m/s} + 0{,}50\cdot0{,}01\,\mathrm{m} = 0{,}045\,\mathrm{m} \approx 0{,}05\,\mathrm{m}$.
> 3. Kontrolle: Beide Summanden sind Längen. $v_0$ ist auf $5\,\%$ genau bekannt und geht linear ein; $5\,\%$ von $0{,}80\,\mathrm{m}$ sind $4\,\mathrm{cm}$, genau der erste Summand.
> Ergebnis: $d = (0{,}80 \pm 0{,}05)\,\mathrm{m}$. Eine genauere Höhenmessung brächte kaum etwas, eine genauere Geschwindigkeitsmessung dagegen fast alles.

Siehe auch: [[Partielle Ableitung]], [[Magnus-Experiment]], [[Differential]]

**Weiterführend (1. Semester):** [[Gaußsche Fehlerfortpflanzung]], [[Größtfehler]]
