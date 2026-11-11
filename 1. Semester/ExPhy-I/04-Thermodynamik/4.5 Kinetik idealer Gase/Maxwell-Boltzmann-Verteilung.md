---
modul: ExPhy I
fach: Physik
part: "Kap. 4.5.3–4.5.4"
keywords: Maxwell-Boltzmann distribution, most probable speed, rms speed
---

# Maxwell–Boltzmann-Verteilung

#exphy1 #thermodynamics #kinetic-theory #atomic

**Weg über die barometrische Höhenformel:** Ein Molekül erreicht die Höhe $z$ nur, wenn seine kinetische Energie die potentielle $mgz$ aufbringt ⇒ Boltzmann-Faktor $e^{-E/k_BT}$. Für alle drei Richtungen:
$$f(v)\sim\frac{v^2}{(k_BT)^{3/2}}\,e^{-E_\text{kin}/k_BT}\qquad N(v)=4\pi N_\text{ges}\Bigl[\frac m{2\pi k_BT}\Bigr]^{3/2}v^2\,e^{-mv^2/2k_BT}$$
$v^2$ stammt vom Volumen der Kugelschale im Geschwindigkeitsraum, der Exponentialfaktor von der Energieverteilung.

| Größe | Ausdruck |
|---|---|
| wahrscheinlichste $v_w$ | $\sqrt{2k_BT/m}$ |
| mittlere $\bar v$ | $\sqrt{8k_BT/\pi m}=\tfrac2{\sqrt\pi}v_w$ |
| rms $v_\text{rms}$ | $\sqrt{3k_BT/m}=\sqrt{\tfrac32}\,v_w$ |

Stets $v_w<\bar v<v_\text{rms}$; nur $v_\text{rms}$ gehört zur mittleren kinetischen Energie (hängt von $v^2$ ab). Die Verteilung ist **unsymmetrisch** (kleine $v$: Faktor $v^2$ drückt, große $v$: Exponentialfaktor); höheres $T$ ⇒ flacher, nach rechts.

```
 f(v)
  │    ╱╲___  T1 (kalt)
  │   ╱    ╲___
  │  ╱  ╱‾╲_____ T2 > T1
  └───v_w v̄ v_rms────────► v
```
**Mathematik:** Mittelwertkette → [[Mittelwerte und ihre Ungleichungskette]] · Gegenbild zur symmetrischen [[Normalverteilung]].

**Baut auf:** [[Druck und Temperatur in der kinetischen Gastheorie]]
