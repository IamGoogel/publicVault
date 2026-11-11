---
modul: MaPhy I
fach: Mathematik
part: "Kap. 9.1"
keywords: group, abelian, order of element, cyclic group
---

# Gruppe

#maphy1 #groups #group-basics #atomic

**Definition.** $G\times G\to G$, $(g,h)\mapsto gh$ mit
(i) $(gh)k=g(hk)$; (ii) $\exists e:\ ge=eg=g$; (iii) $\forall g\ \exists g^{-1}:\ gg^{-1}=g^{-1}g=e$.

Neutrales Element und Inverse sind **eindeutig**. *Abelsch*: $gh=hg$ (oft additiv geschrieben).

| Größe | Definition |
|---|---|
| Ordnung $\lvert G\rvert$ | Mächtigkeit von $G$ |
| Elementordnung $\operatorname{ord}g$ | kleinstes $p$ mit $g^p=e$ (sonst $\infty$) |

> [!important] Lagrange für Elemente
> In einer endlichen Gruppe ist $\operatorname{ord}g$ endlich und **teilt** $\lvert G\rvert$ ([[Nebenklassen und Index]]).

**Beispiele.**
- Zyklische Gruppe $\mathbb Z_n=\{e,a,\dots,a^{n-1}\}$, $a^n=e$, $\operatorname{ord}a=n$.
- $(\mathbb R,+)$, $(\mathbb R\setminus\{0\},\cdot)$, $GL(n,K)$, $SL(n,K)$ ([[Determinante und Gruppen]]).
- Gruppe der Ordnung $6$: $G=\langle a,b\mid a^3,b^2,abab\rangle=\{e,a,a^2,b,ab,a^2b\}$, $ba=a^2b$. **Nichtabelsch**; drei Elemente der Ordnung 2 ($b,ab,a^2b$), zwei der Ordnung 3 ($a,a^2$). Isomorph zu $S_3$ ([[Permutationen und Transpositionen]]).

**Baut auf:** [[Abbildung und Komposition]] (Verknüpfung)
**Wird gebraucht für:** [[Untergruppe und Normalteiler]] · [[Körper- und Ordnungsaxiome]] · [[Vektorraum]]
