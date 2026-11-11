---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.1"
keywords: Cauchy sequence, bounded, convergent implies Cauchy
---

# Cauchyfolge

#maphy1 #analysis #sequences #atomic

**Definition.** $(a_n)$ ist *Cauchyfolge*, wenn
$$\forall\varepsilon>0\ \exists N\ \forall m,n\ge N:\ \lvert a_m-a_n\rvert\le\varepsilon .$$

**Lemma.** Konvergent ⇒ Cauchy:
$\lvert a_m-a_n\rvert\le\lvert a-a_m\rvert+\lvert a-a_n\rvert$, jeweils $\le\varepsilon/2$.

**Satz.** Cauchyfolgen sind **beschränkt** (analog zu [[Eindeutigkeit und Beschränktheit des Grenzwerts]]).

**Lemma.** Hat eine Cauchyfolge eine **konvergente Teilfolge**, so konvergiert sie selbst.

```
konvergent ──▶ Cauchy ──▶ beschränkt
```

> [!warning] Umkehrung nur in $\mathbb R$
> „Cauchy ⇒ konvergent“ gilt in $\mathbb R$ ([[Cauchy-Kriterium]]), nicht in $\mathbb Q$: rationale Näherungen an $\sqrt2$ sind Cauchy, konvergieren aber in $\mathbb Q$ nicht.

**Baut auf:** [[Konvergenz einer Folge]] · [[Teilfolge und Häufungswert]]
**Wird gebraucht für:** [[Cauchy-Kriterium]] · metrisch: [[Vollständigkeit und Banachscher Fixpunktsatz]]
