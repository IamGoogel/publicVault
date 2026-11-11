---
modul: ExPhy I
fach: Physik
part: "Kap. 2.9.3"
keywords: moment of inertia, parallel axis theorem, Steiner
---

# Trägheitsmoment und Satz von Steiner

#exphy1 #mechanics #rigid-body #atomic

Feste Achse parallel zu $x_3$: $L_3=I_{33}\omega$ mit $I=\int r_\perp^2\,dm$ ($r_\perp$ = Normalabstand zur Achse). Masse weit außen zählt **quadratisch** stärker.

**Satz von Steiner.** Achse $A$ parallel zur Schwerpunktachse $A_S$ im Abstand $d$:
$$I_A=I_S+Md^2$$

| Körper (Symmetrieachse) | $I_S$ |
|---|---|
| Punktmasse | $MR^2$ |
| Vollzylinder/Scheibe | $\tfrac12MR^2$ |
| Hohlzylinder | $MR^2$ |
| Vollkugel | $\tfrac25MR^2$ |
| Hohlkugel | $\tfrac23MR^2$ |
| Stab (Mitte, senkrecht) | $\tfrac1{12}ML^2$ |

> [!info] Herleitung Vollzylinder
> Nur der Vollzylinder: Zylinderkoordinaten, $dV=r\,dr\,d\varphi\,dz$, $M=\rho\pi R^2H$ ⇒ $I=\tfrac12MR^2$. Die übrigen Werte sind Standardwerte der Literatur.

**Baut auf:** [[Trägheitstensor]]
**Wird gebraucht für:** [[Rollbewegung und Maxwellsches Rad]] · [[Torsionspendel]] · [[Rotationsenergie und Drehimpulserhaltung]]
