---
modul: ExPhy I
fach: Physik
part: "Kap. 1.3.8"
keywords: pendulum, g determination, worked example
---

# Fadenpendel - Bestimmung von g

#exphy1 #measurement #error-propagation #atomic

$n=15$ Messungen der Schwingungsdauer; Ableseunsicherheit der Stoppuhr $\Delta t=0{,}005$ s.

| Größe | Wert |
|---|---|
| $\bar t$ | $1{,}998$ s |
| $\sigma_t$ | $0{,}030$ s |
| $\sigma_{\bar t}=\sigma_t/\sqrt{15}$ | $0{,}008$ s |

- $\sigma_t=0{,}030\,\mathrm s>\Delta t=0{,}005\,\mathrm s$: Nicht die Uhr, sondern die **Reaktionszeit** begrenzt die Genauigkeit. Eine feinere Uhr hilft nicht, mehr Messungen schon.
- Ergebnis: $T=(2{,}00\pm0{,}03)$ s (Einzelmessung), $T=(1{,}998\pm0{,}008)$ s (Mittelwert).
- $g=4\pi^2\ell/T^2$, $\ \sigma_g/g=\sigma_\ell/\ell+2\sigma_T/T$ ([[Größtfehler]]).

> [!example] Zahlenwert
> Mit $\ell=(0{,}992\pm0{,}002)$ m: $g\approx9{,}81$ m/s²; Gauß: $\sigma_g/g=\sqrt{0{,}0020^2+0{,}0080^2}\approx0{,}8\,\%$ ⇒ $T$ dominiert.

**Baut auf:** [[Fehler des Mittelwerts]] · [[Größtfehler]] · [[Dimensionsanalyse]]
**Physik:** Pendelgleichung → [[Ungedämpfte Schwingung]]
