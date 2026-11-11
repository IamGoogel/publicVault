---
modul: MaPhy I
fach: Mathematik
part: "Kap. 10.2"
keywords: bounded sequence, Cauchy sequence, metric space
---

# Beschränkte Folgen und Cauchyfolgen in metrischen Räumen

#maphy1 #metric-spaces #metric-sequences #atomic

- *Beschränkt*: alle $x_n$ liegen in einer Kugel $\bar B(\bar x,r)$. Unabhängig vom Mittelpunkt: für $\bar x'$ genügt $r'=r+d(\bar x,\bar x')$.
- *Cauchyfolge*: $\forall\varepsilon\,\exists N\,\forall m,n\ge N:\ d(x_m,x_n)\le\varepsilon$.

**Lemma.** Konvergente Folgen sind beschränkt ($r=\max\{d(x_1,\bar x),\dots,d(x_{N-1},\bar x),1\}$).
**Lemma.** Cauchyfolgen sind beschränkt; konvergente Folgen sind Cauchy.

```
konvergent ──▶ Cauchy ──▶ beschränkt
        ◀── nur in vollständigen Räumen
```

> [!warning] Umkehrung
> Cauchy ⇏ konvergent im Allgemeinen: rationale Folge $a_n\to\sqrt2$ ist Cauchy in $\mathbb Q$, konvergiert dort aber nicht → [[Vollständigkeit]].

**Baut auf:** [[Konvergenz in metrischen Räumen]] · [[Cauchyfolge]] · [[Kugeln und Isometrien]]
**Wird gebraucht für:** [[Vollständigkeit]]
