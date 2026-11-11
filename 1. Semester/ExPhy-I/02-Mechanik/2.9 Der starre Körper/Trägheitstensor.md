---
modul: ExPhy I
fach: Physik
part: "Kap. 2.9.2"
keywords: inertia tensor, angular momentum, moment of inertia
---

# Trägheitstensor

#exphy1 #mechanics #rigid-body #atomic

Für ein Massenelement: $\mathbf L_i=\mathbf r_i\times m_i(\boldsymbol\omega\times\mathbf r_i)$. Mit $\mathbf A\times(\mathbf B\times\mathbf C)=\mathbf B(\mathbf A\cdot\mathbf C)-\mathbf C(\mathbf A\cdot\mathbf B)$:
$$\mathbf L=\int\bigl[r^2\boldsymbol\omega-\mathbf r(\mathbf r\cdot\boldsymbol\omega)\bigr]dm=\tilde I\,\boldsymbol\omega,\qquad I_{jk}=\int\bigl(r^2\delta_{jk}-x_jx_k\bigr)dm$$
- $\tilde I$ ist **symmetrisch**: $I_{jk}=I_{kj}$. Diagonale = *Trägheitsmomente*, Nebendiagonale = *Trägheitsprodukte*.
- $\mathbf L=\tilde I\boldsymbol\omega$ ersetzt $\mathbf p=m\mathbf v$; an die Stelle des Skalars $m$ tritt eine **Matrix**, daher sind $\mathbf L$ und $\boldsymbol\omega$ i. A. **nicht parallel**.

**Baut auf:** [[Statik starrer Körper]] · [[Drehimpuls und Drehmoment]]
**Mathematik:** [[Matrixmultiplikation]] · [[Transposition]] (Symmetrie) · [[Eigenwerte und charakteristisches Polynom]]
**Wird gebraucht für:** [[Trägheitsmoment und Satz von Steiner]] · [[Hauptachsen und Eulersche Kreiselgleichungen]]
