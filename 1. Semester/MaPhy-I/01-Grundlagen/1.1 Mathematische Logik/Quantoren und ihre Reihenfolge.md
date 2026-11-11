---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.1"
keywords: quantifier, universal, existential, order of quantifiers
---

# Quantoren und ihre Reihenfolge

#maphy1 #foundations #logic #atomic

$\forall x$: „für alle $x$“, $\exists x$: „es gibt ein $x$“. Ein Satz $P(x)$ mit freier Variable ist keine Aussage — erst durch **Binden** (Quantifizieren) wird er eine.

Über $\mathbb R$: $\forall x:\ x>1$ ist falsch, $\exists x:\ x>1$ ist wahr.

| Vertauschung | erlaubt? |
|---|---|
| $\forall x\,\forall y\iff\forall y\,\forall x$ | ja |
| $\exists x\,\exists y\iff\exists y\,\exists x$ | ja |
| $\forall x\,\exists y$ vs. $\exists y\,\forall x$ | **nein** |

> [!example] Hosen-Beispiel
> „Für jedes Kind gibt es eine passende Hose“ ($\forall$ Kind $\exists$ Hose) ≠ „Es gibt eine Hose, die allen passt“ ($\exists$ Hose $\forall$ Kind).
> Allgemein gilt nur $\exists y\,\forall x:P\Longrightarrow\forall x\,\exists y:P$.

> [!tip] Analysis
> Der Unterschied „$N$ hängt von $\varepsilon$ ab“ ($\forall\varepsilon\,\exists N$) gegenüber „ein $N$ für alle $\varepsilon$“ ist genau diese Reihenfolge → [[Konvergenz einer Folge]].

**Baut auf:** [[Aussage und Axiom]]
**Wird gebraucht für:** [[Negation quantifizierter Aussagen]] · [[Konvergenz einer Folge]] · [[Funktionsgrenzwert]]
