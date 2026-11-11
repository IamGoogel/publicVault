---
modul: ExPhy I
fach: Physik
part: "Kap. 1.3.6"
keywords: standard error, 1/sqrt n
---

# Fehler des Mittelwerts

#exphy1 #measurement #error-propagation #atomic

Sonderfall der [[Gaußsche Fehlerfortpflanzung|Gauß'schen Fortpflanzung]] für $R=\bar x=\frac1n(x_1+\dots+x_n)$, $\partial R/\partial x_i=1/n$:
$$\sigma_{\bar x}=\sqrt{\frac1{n^2}\,n\sigma_x^2}=\frac{\sigma_x}{\sqrt n}$$

| Größe | Aussage |
|---|---|
| $\bar x$ | Mittelwert der Messreihe |
| $\sigma_x$ | Streuung der Einzelwerte — Eigenschaft des **Verfahrens**, sinkt nicht mit $n$ |
| $\sigma_{\bar x}$ | Unsicherheit des Mittelwerts — sinkt mit $1/\sqrt n$ |

Halbierte Unsicherheit ⇒ **vierfache** Zahl an Messungen.

**Baut auf:** [[Gaußsche Fehlerfortpflanzung]] · [[Mittelwert und Standardabweichung]]
**Wird gebraucht für:** [[Fadenpendel - Bestimmung von g]] · [[Zufällige und systematische Fehler]]
