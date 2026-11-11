---
modul: ExPhy I
fach: Physik
part: "Kap. 2.10.3"
keywords: continuity equation, divergence, Gauss theorem, flow fields
---

# Kontinuitätsgleichung

#exphy1 #mechanics #fluids #atomic

Strömung = drei Felder $\rho(\mathbf r,t)$, $\mathbf v(\mathbf r,t)$, $p(\mathbf r,t)$ (fünf Skalarfunktionen). Die Euler-Gleichung (Newton II je Masseneinheit) liefert drei Gleichungen; die vierte ist die Kontinuität. Stromlinien sind tangential zu $\mathbf v$; hohe Stromliniendichte = Beschleunigung.

**Massenerhaltung:** $\dfrac d{dt}\int_V\rho\,dV=-\oint_{\partial V}\rho\mathbf v\cdot d\mathbf A$. Mit dem **Satz von Gauß** (glattes Feld, Volumen mit stückweise glattem, orientiertem Rand) folgt für jedes Volumen
$$\frac{\partial\rho}{\partial t}+\operatorname{div}(\rho\mathbf v)=0$$
Inkompressibel ($\rho=$ const.): $\operatorname{div}\mathbf v=0$ ⇒ in einer Stromröhre $A_1v_1=A_2v_2$ (Verengung ⇒ höheres $v$).

> [!important] Divergenz ist lokal
> $\operatorname{div}\mathbf v=\lim_{V\to0}\Phi_V/V$ — Eigenschaft des Feldes an einem Punkt, nicht des Kontrollvolumens. Kartesisch $\operatorname{div}\mathbf v=\partial_xv_x+\partial_yv_y+\partial_zv_z$; Quelle: $\operatorname{div}\mathbf v>0$.

Beispiele: Verengung einer Autobahn, Verjüngung des Wasserstrahls unter dem Hahn.

**Wird gebraucht für:** [[Bernoulli-Gleichung]] (Venturi-Rohr)
**Mathematik:** [[Stetigkeit einer Funktion]] (Glattheit)
