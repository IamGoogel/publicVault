---
modul: MaPhy I
fach: Mathematik
part: "Kap. 6.1"
keywords: vector space, field characteristic, examples
---

# Vektorraum

#maphy1 #linear-algebra #vector-spaces #atomic

**Definition.** $K$ Körper ($\mathbb R,\mathbb C,\dots$). $V$ mit $+:V\times V\to V$ und $\cdot:K\times V\to V$ ist *Vektorraum*, wenn
1. $(V,+)$ kommutative Gruppe mit neutralem Element $0$;
2. für $\alpha,\beta\in K$, $u,v\in V$: $\alpha(\beta v)=(\alpha\beta)v$, $\ 1\cdot v=v$, $\ \alpha(u+v)=\alpha u+\alpha v$, $\ (\alpha+\beta)v=\alpha v+\beta v$.

**Lemma.** (a) $n\cdot v$ ($n$-fache Summe) ist wohldefiniert; (b) $\alpha v=0\Rightarrow\alpha=0$ oder $v=0$.

> [!warning] Charakteristik
> In $K$ kann $n\cdot1=0$ gelten; das kleinste solche $n$ ist eine Primzahl $p$ (*Charakteristik*). $\mathbb Q,\mathbb R,\mathbb C$ haben Charakteristik $0$.

**Beispiele 6.1.3.**
| Beispiel | Bemerkung |
|---|---|
| $\{0\}$ | trivialer Raum |
| $K^n$ | komponentenweise Operationen |
| $K^X=\{f:X\to K\}$ | Funktionenraum |
| $C([0,1];\mathbb R)$ | stetige Funktionen |

**Baut auf:** [[Gruppen und Untergruppen]] (abelsche Gruppe) · [[Körper- und Ordnungsaxiome]]
**Wird gebraucht für:** [[Untervektorraum und Erzeugnis]] · [[Lineare Abbildung]]
