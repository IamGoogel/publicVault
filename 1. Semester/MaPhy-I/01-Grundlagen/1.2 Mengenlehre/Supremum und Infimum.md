---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.2.3"
keywords: supremum, infimum, upper bound, maximum
---

# Supremum und Infimum

#maphy1 #foundations #relations #atomic

Sei $S\subseteq M$, $(M,\le)$ geordnet.

| Begriff | Definition |
|---|---|
| obere Schranke $b$ | $x\le b$ für alle $x\in S$ |
| nach oben beschränkt | es gibt eine obere Schranke |
| beschränkt | nach oben **und** unten beschränkt |
| $\sup S$ | **kleinste** obere Schranke (falls existent) |
| $\inf S$ | **größte** untere Schranke |
| $\max S$ | $\sup S$, **falls** $\sup S\in S$ |

> [!warning] Das Supremum muss nicht existieren
> In $\mathbb Q$ ist $S=\{x\in\mathbb Q\mid x^2<2\}$ nach oben beschränkt, aber $\sup S$ existiert in $\mathbb Q$ **nicht** ($\sqrt2\notin\mathbb Q$). Genau das repariert das [[Vollständigkeitsaxiom]].

> [!example] Teilbarkeit und Potenzmenge
> Bzgl. $\mid$ auf $\mathbb N$: $\inf S=\operatorname{ggT}(S)$, $\sup S=\operatorname{kgV}(S)$ (endliches $S$). In $(2^M,\subseteq)$: kleinstes Element $\emptyset$, größtes $M$.

> [!warning] Max ≠ Sup
> $\sup[0,1)=1$, aber $[0,1)$ hat kein Maximum.

**Baut auf:** [[Ordnungsrelation]]
**Wird gebraucht für:** [[Vollständigkeitsaxiom]] · [[Monotoniekriterium]] · [[Limes superior und Limes inferior]]
