---
modul: MaPhy I
fach: Mathematik
part: "Kap. 9.1"
keywords: kernel is normal, homomorphism theorem
---

# Kern, Normalteiler und Homomorphiesatz

#maphy1 #groups #homomorphism #atomic

**Satz.** Der Kern eines Homomorphismus ist ein **Normalteiler**. Umgekehrt ist jeder Normalteiler $N$ Kern eines Homomorphismus, nämlich des kanonischen $G\to G/N$ ([[Faktorgruppe]]).

**Homomorphiesatz.**
$$G/\ker\varphi\ \cong\ \operatorname{im}\varphi,\qquad g\ker\varphi\mapsto\varphi(g).$$

```
 G ──φ──▶ G'
 │ π       ▲
 ▼         │ ≅ (induziert)
G/ker φ ───┘  = im φ
```

**Beispiele.**
- $\mathbb Z/n\mathbb Z\cong\mathbb Z_n$.
- $\det:GL(n,K)\to K^\times$ (surjektiv) mit Kern $SL(n,K)$ ⇒ $GL/SL\cong K^\times$.
- $\operatorname{sgn}:S_n\to\{\pm1\}$ mit Kern $A_n$ ⇒ $S_n/A_n\cong\mathbb Z_2$ ([[Vorzeichen und alternierende Gruppe]]).

> [!warning] Nur für Kerne
> Eine Faktorgruppe $G/N$ gibt es nur für Normalteiler.

**Baut auf:** [[Gruppenhomomorphismus]] · [[Faktorgruppe]]
