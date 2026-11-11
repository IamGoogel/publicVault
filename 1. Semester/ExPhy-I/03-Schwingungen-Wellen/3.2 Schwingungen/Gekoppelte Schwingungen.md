---
modul: ExPhy I
fach: Physik
part: "Kap. 3.2.5"
keywords: coupled oscillators, normal modes, eigenvalue problem
---

# Gekoppelte Schwingungen

#exphy1 #oscillations-waves #oscillation #atomic

Zwei Massen $m_1,m_2$, Federn $K_1,K_2$ an den Wänden, Kopplungsfeder $K_{12}$:
$$m_1\ddot x_1=-K_1x_1-K_{12}(x_1-x_2),\qquad m_2\ddot x_2=-K_2x_2-K_{12}(x_2-x_1)$$
Bei $x_1=x_2$ verschwindet der Kopplungsterm. Neu: **Verlust der Lokalität** — Energie wird zwischen den Oszillatoren übertragen.

1. **Substitution (Normalkoordinaten)**, im symmetrischen Fall $x_1+x_2$ und $x_1-x_2$: Die Gleichungen entkoppeln, jede ist eine ungedämpfte Schwingung.
2. **Matrix:** $m\ddot{\mathbf x}=A\mathbf x$ mit
$$A=\begin{pmatrix}-(K_1+K_{12})&K_{12}\\K_{12}&-(K_2+K_{12})\end{pmatrix}$$
Die **Normalmoden** sind die Eigenvektoren von $A$, die Eigenwerte liefern die Frequenzen.

Symmetrisch ($K_1=K_2=K$, $m_1=m_2=m$): gleichphasig $\omega=\sqrt{K/m}$ (Kopplungsfeder ungedehnt), gegenphasig $\omega=\sqrt{(K+2K_{12})/m}$.

**Übergang zur Welle:** Setzt man die Kette über zwei Massen fort, wird aus dem Eigenwertproblem ein Kontinuumsproblem — aus der gekoppelten Schwingung die Welle ([[Wellen - Grundlagen und Geschwindigkeiten]]).

**Baut auf:** [[Ungedämpfte Schwingung]] · **Mathematik:** [[Eigenwerte und charakteristisches Polynom]] · [[Basiswechsel]] (Normalkoordinaten)
