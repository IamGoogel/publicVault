---
modul: MaPhy I
fach: Mathematik
part: "Kap. 6.1"
keywords: linear map, homomorphism, endomorphism, isomorphism
---

# Lineare Abbildung

#maphy1 #linear-algebra #linear-maps #atomic

**Definition.** $T:V\to W$ ($K$-Vektorräume) ist *linear*, wenn
(i) $T(v_1+v_2)=Tv_1+Tv_2$, (ii) $T(\alpha v)=\alpha Tv$.

Beispiel: $T:\mathbb R^2\to\mathbb R^3$, $(x,y)\mapsto(x+2y,\,-x-y,\,0)$.

**Satz.** (a) $T0=0$. (b) Ist $T$ bijektiv, ist $T^{-1}$ linear. (c) Kompositionen linearer Abbildungen sind linear. Außerdem ist $L(V,W)$ mit komponentenweisen Operationen ein $K$-Vektorraum.

| Name | Bedeutung |
|---|---|
| $\mathrm{Hom}(V,W)=L(V,W)$ | lineare Abbildungen |
| Mono-/Epi-/Isomorphismus | injektiv / surjektiv / bijektiv |
| $\mathrm{End}(V)=L(V)$ | Endomorphismen |
| $\mathrm{Aut}(V)$ | bijektive Endomorphismen; $\mathrm{Aut}(K^m)\cong GL(m,K)$ |

> [!warning] Nicht-lineare Gegenbeispiele
> $x\mapsto x+1$ ist **nicht** linear ($T0\ne0$), ebenso $x\mapsto x^2$.

**Baut auf:** [[Vektorraum]] · [[Injektiv, surjektiv, bijektiv]] · [[Abbildung und Komposition]]
**Wird gebraucht für:** [[Kern und Bild]] · [[Matrix als lineare Abbildung]] · [[Abbildungsmatrix]] · [[Gruppenhomomorphismus]] (Analogon)
