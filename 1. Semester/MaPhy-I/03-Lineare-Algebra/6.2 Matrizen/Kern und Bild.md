---
modul: MaPhy I
fach: Mathematik
part: "Kap. 6.2"
keywords: kernel, image, rank-nullity
---

# Kern und Bild

#maphy1 #linear-algebra #linear-maps #atomic

Für $T\in L(V,W)$:
$$\ker T=\{v\mid Tv=0\}\subseteq V,\qquad\operatorname{im}T=T(V)\subseteq W$$
beide sind Untervektorräume ([[Untervektorraum und Erzeugnis]]). $\operatorname{rk}T=\dim\operatorname{im}T$.

- $T$ injektiv ⇔ $\ker T=\{0\}$; $T$ surjektiv ⇔ $\operatorname{im}T=W$.
- Für eine Matrix $A$: $\operatorname{im}A=\operatorname{span}\{Ae_1,\dots,Ae_n\}$ (Spaltenraum).
- Eigenräume sind Kerne: $E(\lambda;T)=\ker(\lambda I-T)$ → [[Eigenwerte und charakteristisches Polynom]].

> [!note] Ergänzung
> **Dimensionsformel:** $\dim V=\dim\ker T+\dim\operatorname{im}T$ für endlichdimensionales $V$. Die Kern-Bild-Zerlegung steckt im Beweis von Satz benutzt (Basis, deren letzte Vektoren $\ker A$ aufspannen).

> [!info] Analogon
> Beim Gruppenhomomorphismus: $\ker\varphi$ ist Normalteiler → [[Kern, Normalteiler und Homomorphiesatz]]. Das Urbild $T^{-1}(\{0\})$ ist ein Spezialfall von [[Urbild einer Menge]].

**Baut auf:** [[Lineare Abbildung]] · [[Urbild einer Menge]]
**Wird gebraucht für:** [[Rang und voller Rang]] · [[Eigenwerte und charakteristisches Polynom]]
