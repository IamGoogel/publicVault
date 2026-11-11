---
modul: MaPhy I
fach: Mathematik
part: "Kap. 9.1"
keywords: group homomorphism, isomorphism, kernel, image
---

# Gruppenhomomorphismus

#maphy1 #groups #homomorphism #atomic

**Definition.** $\varphi:G\to G'$ mit $\varphi(gh)=\varphi(g)\varphi(h)$ (oft wird zusätzlich $\varphi(e)=e'$ gefordert).

| Begriff | Definition |
|---|---|
| Isomorphismus | bijektiver Homomorphismus, $G\cong G'$ |
| Kern | $\ker\varphi=\{g\mid\varphi(g)=e'\}$ |
| Bild | $\operatorname{im}\varphi=\{\varphi(g)\}\le G'$ (Untergruppe) |

> [!note] Redundanz
> $\varphi(e)=e'$ folgt bereits aus der Multiplikativität, wird aber oft explizit in die Definition aufgenommen.

**Beispiele.** $\det:GL(n,K)\to K^\times$ ([[Determinante und Gruppen]]); $\operatorname{sgn}:S_n\to\{\pm1\}$ ([[Vorzeichen und alternierende Gruppe]]); $\mathbb Z\to\mathbb Z_n$, $k\mapsto[k]$.

> [!info] Analogon in der linearen Algebra
> Lineare Abbildungen sind Homomorphismen von Vektorräumen → [[Lineare Abbildung]], [[Kern und Bild]].

**Baut auf:** [[Gruppe]] · [[Abbildung und Komposition]]
**Wird gebraucht für:** [[Kern, Normalteiler und Homomorphiesatz]]
