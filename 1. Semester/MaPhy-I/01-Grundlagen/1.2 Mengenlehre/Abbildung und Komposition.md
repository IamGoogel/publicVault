---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.2.4"
keywords: mapping, composition
---

# Abbildung und Komposition

#maphy1 #foundations #mappings #atomic

**Definition.** Eine Abbildung $F:M\to N$ ist eine Relation $F\subseteq M\times N$, so dass es zu **jedem** $x\in M$ **genau ein** $y\in N$ mit $(x,y)\in F$ gibt; $x\mapsto F(x)$.

Beispiele: konstante Abbildung, $\mathrm{id}_M$, $n\mapsto2n+1$, $x\mapsto1+x^2$.

**Komposition.**
$$G\circ F:M\xrightarrow{F}N\xrightarrow{G}N',\qquad(G\circ F)(x)=G(F(x))$$

> [!warning] Leserichtung
> $G\circ F$ wird **von rechts nach links** gelesen: erst $F$, dann $G$. I. A. $G\circ F\ne F\circ G$. Dieselbe Konvention gilt bei [[Permutationen und Transpositionen]].

**Baut auf:** [[Relation und Äquivalenzrelation]] · [[Mengenoperationen]]
**Wird gebraucht für:** [[Injektiv, surjektiv, bijektiv]] · [[Umkehrabbildung]] · [[Lineare Abbildung]]
