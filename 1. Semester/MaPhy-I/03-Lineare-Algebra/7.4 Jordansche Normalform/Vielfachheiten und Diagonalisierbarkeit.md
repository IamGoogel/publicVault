---
modul: MaPhy I
fach: Mathematik
part: "Kap. 7.4"
keywords: algebraic multiplicity, geometric multiplicity, semisimple
---

# Vielfachheiten und Diagonalisierbarkeit

#maphy1 #linear-algebra #jordan #atomic

| Begriff | Bedeutung an der Jordanform |
|---|---|
| geometrische Vielfachheit $\dim E(\lambda)$ | **Anzahl** der Blöcke zu $\lambda$ |
| algebraische Vielfachheit $\dim E'(\lambda)$ | **Summe der Größen** der Blöcke zu $\lambda$ = Nullstellenordnung in $p_T$ |
| einfach | algebraische Vielfachheit $=1$ (genau ein Block der Größe 1) |
| halbeinfach | algebraisch = geometrisch (alle Blöcke Größe 1, $E=E'$) |

**Satz.** $T$ ist diagonalisierbar ⇔ **alle** Eigenwerte sind halbeinfach.

```
geometrisch ≤ algebraisch   (#Blöcke ≤ Summe der Blockgrößen)
Gleichheit für alle λ  ⇔  diagonalisierbar
```

> [!warning] Merke
> Geometrisch ≠ algebraisch ⇒ **nicht** diagonalisierbar, z. B. $J_2(\lambda)$.

**Baut auf:** [[Jordanblock und Jordansche Normalform]] · [[Verallgemeinerter Eigenraum]] · [[Diagonalisierbarkeit]]
