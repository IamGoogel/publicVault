---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.2.3"
keywords: order relation, total order, antisymmetric
---

# Ordnungsrelation

#maphy1 #foundations #relations #atomic

**Definition.** Eine Ordnung $\le$ auf $M$ ist reflexiv, **antisymmetrisch** ($x\le y\land y\le x\Rightarrow x=y$) und transitiv. $(M,\le)$ heißt *geordnete Menge*; $x<y$ bedeutet $x\le y$ und $x\ne y$.

**Totalordnung:** je zwei Elemente sind vergleichbar.

| Beispiel | Ordnung? | total? |
|---|---|---|
| $\mathbb N,\mathbb Z,\mathbb Q,\mathbb R$ mit $\le$ | ja | ja |
| $(2^M,\subseteq)$, $\lvert M\rvert\ge2$ | ja | nein ($\{1\},\{2\}$) |
| $(\mathbb N,\mid)$ Teilbarkeit | ja | nein ($2$ und $3$) |

| | Äquivalenzrelation | Ordnungsrelation |
|---|---|---|
| reflexiv | ja | ja |
| symmetrisch | ja | nein |
| antisymmetrisch | nein | ja |
| transitiv | ja | ja |

**Baut auf:** [[Relation und Äquivalenzrelation]] · [[Potenzmenge]]
**Wird gebraucht für:** [[Supremum und Infimum]] · [[Körper- und Ordnungsaxiome]]
