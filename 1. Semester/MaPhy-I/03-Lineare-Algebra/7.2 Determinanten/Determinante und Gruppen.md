---
modul: MaPhy I
fach: Mathematik
part: "Kap. 7.2 (GL und SL)"
keywords: GL, SL, determinant homomorphism
---

# Determinante und Gruppen ($GL$, $SL$)

#maphy1 #linear-algebra #determinant #atomic

- $GL(V)=\{T\in\mathrm{End}(V)\mid\det T\ne0\}$; $\det:GL(V)\to K^\times$ ist ein [[Gruppenhomomorphismus]] (wegen $\det(AB)=\det A\det B$).
- $SL(V)=\ker\det=\{\det T=1\}$ (*spezielle lineare Gruppe*) ist Normalteiler.
- $GL(V)\cong GL(n,K)$, $SL(V)\cong SL(n,K)$.
- $\det$ ist **surjektiv** (z. B. $\operatorname{diag}(\lambda,1,\dots,1)$), also $GL(n,K)/SL(n,K)\cong K^\times$ nach dem [[Kern, Normalteiler und Homomorphiesatz|Homomorphiesatz]].

**Physik:** Die Lorentz-Transformation in $(x,ct)$ hat $\det=\gamma^2(1-\beta^2)=1$ → [[Lorentz-Transformation und Minkowski-Diagramme]]; Transformationsgruppen der Mechanik → [[Symmetrien und Erhaltungssätze]].

**Baut auf:** [[Determinante]] · [[Gruppenhomomorphismus]] · [[Invertierbare Matrizen]]
