---
modul: MaPhy I
fach: Mathematik
part: "Kap. 9.1"
keywords: cosets, index, Lagrange
---

# Nebenklassen und Index (Satz von Lagrange)

#maphy1 #groups #group-basics #atomic

**Linksnebenklasse** $gH=\{gh\mid h\in H\}$. Sie sind die Äquivalenzklassen zu $g\sim g'\iff g^{-1}g'\in H$ ([[Relation und Äquivalenzrelation]]), zerlegen $G$ also disjunkt.

- **Index** $(G:H)$ = Anzahl der Links- = Anzahl der Rechtsnebenklassen.
- Für endliches $G$: $(G:H)=\lvert G\rvert/\lvert H\rvert$, also $\lvert H\rvert\mid\lvert G\rvert$ (**Lagrange**).
- Für Normalteiler gilt $gN=Ng$.

> [!example] Beispiel
> $H_1=\{e,b\}$, $(G:H_1)=3$. Linksnebenklassen: $\{e,b\},\{a,ab\},\{a^2,a^2b\}$. Rechtsnebenklassen: $\{e,b\},\{a,a^2b\},\{a^2,ab\}$ — **verschieden**, da $H_1$ kein Normalteiler ist.

**Baut auf:** [[Untergruppe und Normalteiler]] · [[Relation und Äquivalenzrelation]]
**Wird gebraucht für:** [[Faktorgruppe]] · [[Vorzeichen und alternierende Gruppe]] (Index 2)
