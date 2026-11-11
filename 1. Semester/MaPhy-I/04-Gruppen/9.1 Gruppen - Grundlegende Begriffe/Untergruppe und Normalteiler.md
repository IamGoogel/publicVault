---
modul: MaPhy I
fach: Mathematik
part: "Kap. 9.1"
keywords: subgroup, normal subgroup, conjugation
---

# Untergruppe und Normalteiler

#maphy1 #groups #group-basics #atomic

**Untergruppe** $H\le G$: $e\in H$, $gh\in H$, $g^{-1}\in H$ für $g,h\in H$.

**Normalteiler** $N\trianglelefteq G$: $gNg^{-1}\subseteq N$ für alle $g\in G$ (äquivalent: $gNg^{-1}=N$ bzw. $gN=Ng$).

- $gHg^{-1}$ sind die zu $H$ **konjugierten** Untergruppen; $N$ ist Normalteiler ⇔ $N$ ist nur zu sich selbst konjugiert.
- In der Gruppe der Ordnung 6 ([[Gruppe]]): $N=\{e,a,a^2\}$ ist Normalteiler; $H_1=\{e,b\}$, $H_2=\{e,ab\}$, $H_3=\{e,a^2b\}$ sind zueinander konjugiert und **keine** Normalteiler.

```
Normalteiler ⊂ Untergruppe ⊂ Gruppe
   (gN = Ng)    (abgeschlossen)
```

> [!warning] Abelsche Gruppen
> In abelschen Gruppen ist jede Untergruppe Normalteiler (da $gng^{-1}=n$).

**Baut auf:** [[Gruppe]]
**Wird gebraucht für:** [[Nebenklassen und Index]] · [[Faktorgruppe]] · [[Kern, Normalteiler und Homomorphiesatz]]
