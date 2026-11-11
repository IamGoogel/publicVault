---
modul: ExPhy I
fach: Physik
part: "Kap. 2.9.4"
keywords: principal axes, Euler gyroscope equations, body-fixed frame
---

# Hauptachsen und Euler’sche Kreiselgleichungen

#exphy1 #mechanics #rigid-body #atomic

| System | $\mathbf L,\boldsymbol\omega$ | $\tilde I$ |
|---|---|---|
| raumfest | zeitabhängig | zeitabhängig |
| körperfest | zeitabhängig | **konstant** |

Beste Wahl: körperfest, Ursprung im Schwerpunkt. Da $\tilde I$ reell und symmetrisch ist, existiert eine Orthonormalbasis, in der $\tilde I$ diagonal wird — ein **Eigenwertproblem**.

**Hauptachsen** $a,b,c$ und **Hauptträgheitsmomente** $I_a\le I_b\le I_c$:
$$\mathbf L=(I_a\omega_a,I_b\omega_b,I_c\omega_c),\qquad T_\text{rot}=\tfrac12\bigl(I_a\omega_a^2+I_b\omega_b^2+I_c\omega_c^2\bigr)$$
Nur beim Kugelkreisel ($I_a=I_b=I_c$, z. B. Würfel) ist $\mathbf L\parallel\boldsymbol\omega$. Rotation um eine Hauptachse ist unwuchtfrei.

**Euler-Gleichungen.** $\mathbf N=\frac{d\mathbf L}{dt}$ gilt raumfest; umgerechnet mit $\frac d{dt}=\frac{d^\prime}{dt}+\boldsymbol\omega\times$ ([[Rotierende Bezugssysteme]]):
$$N_a=I_a\dot\omega_a+\omega_b\omega_c\,(I_c-I_b)$$
und zyklisch — drei gekoppelte Differentialgleichungen.

**Baut auf:** [[Trägheitstensor]] · [[Rotierende Bezugssysteme]]
**Mathematik:** [[Eigenwerte und charakteristisches Polynom]] · [[Diagonalisierbarkeit]] (symmetrisch ⇒ diagonalisierbar) · [[Basiswechsel]]
**Wird gebraucht für:** [[Kreiselbewegung und Präzession]]
