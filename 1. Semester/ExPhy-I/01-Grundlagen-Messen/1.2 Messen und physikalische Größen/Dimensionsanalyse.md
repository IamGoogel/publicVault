---
modul: ExPhy I
fach: Physik
part: "Kap. 1.2.4"
keywords: dimensional analysis, plausibility check
---

# Dimensionsanalyse

#exphy1 #measurement #units #atomic

Eine Gleichung muss auf beiden Seiten dieselbe Dimension haben, z. B. $[\ell]=[vt]\Rightarrow\mathrm m=\frac{\mathrm m}{\mathrm s}\cdot\mathrm s$.

- **Plausibilitätsprüfung:** falsche Dimension ⇒ Gleichung *sicher* falsch.
- **Dimensionsanalyse:** Ansatz $T=C\,\ell^ag^b$ liefert die Exponenten aus dem Dimensionsvergleich.

```
[T]=s, [l]=m, [g]=m s^-2
s^1 = m^(a+b) · s^(-2b)  ⇒  b = -1/2,  a = +1/2   (T ∝ √(l/g))
```

> [!warning] Notwendig, nicht hinreichend
> Gleiche Dimension beweist die Richtigkeit nicht; Zahlenfaktoren wie $2\pi$ liefert sie nicht.

**Baut auf:** [[Basisgrößen und Einheiten]]
**Anwendung:** [[Fadenpendel - Bestimmung von g]]
