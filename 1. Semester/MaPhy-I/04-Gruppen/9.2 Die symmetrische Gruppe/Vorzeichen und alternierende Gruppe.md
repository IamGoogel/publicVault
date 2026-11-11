---
modul: MaPhy I
fach: Mathematik
part: "Kap. 9.2"
keywords: sign of a permutation, alternating group
---

# Vorzeichen und alternierende Gruppe

#maphy1 #groups #permutations #atomic

**Definition.** Für $\sigma=\theta_\ell\circ\dots\circ\theta_1$ (Transpositionen) ist $\operatorname{sgn}\sigma=(-1)^\ell$. Wohldefiniert, da die Parität nach [[Permutationen und Transpositionen]] eindeutig ist.

- $\operatorname{sgn}:S_n\to\{1,-1\}$ ist ein [[Gruppenhomomorphismus]].
- Kern (für $n\ge2$) = **alternierende Gruppe** $A_n=\{\sigma\mid\operatorname{sgn}\sigma=1\}$, also Normalteiler mit $(S_n:A_n)=2$ und $S_n/A_n\cong\mathbb Z_2$ ([[Kern, Normalteiler und Homomorphiesatz]]).

```
gerade   = Produkt gerade vieler Transpositionen  (sgn = +1) ∈ A_n
ungerade = Produkt ungerade vieler Transpositionen (sgn = −1)
```

> [!warning] Nicht eindeutig
> Die Anzahl der Transpositionen ist nicht festgelegt, nur ihre Parität. Das Vorzeichen geht in die Leibniz-Formel ein → [[Determinante]].

**Baut auf:** [[Permutationen und Transpositionen]] · [[Nebenklassen und Index]]
**Wird gebraucht für:** [[Determinante]]
