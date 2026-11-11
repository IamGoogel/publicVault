---
modul: Vorkurs Physik
fach: Physik
part: "Thema Vektoren und Matrizen"
keywords: rotation matrix, rotation, angle
---

# Drehmatrix

#vorkurs #vorkurs-physik

> [!definition] Drehmatrix
> Eine lineare Abbildung ist durch die Bilder der Basisvektoren festgelegt. Bei einer Drehung um den Winkel $\alpha$ gegen den Uhrzeigersinn wird $\hat{e}_x = (1,0)^T$ zu $(\cos\alpha, \sin\alpha)^T$ und $\hat{e}_y = (0,1)^T$ zu $(-\sin\alpha, \cos\alpha)^T$. Schreibt man diese Bilder als Spalten nebeneinander, entsteht die Drehmatrix:
> $$R(\alpha) = \begin{pmatrix} \cos\alpha & -\sin\alpha \\ \sin\alpha & \cos\alpha \end{pmatrix}, \qquad R_z(\alpha) = \begin{pmatrix} \cos\alpha & -\sin\alpha & 0 \\ \sin\alpha & \cos\alpha & 0 \\ 0 & 0 & 1 \end{pmatrix}$$
> Im Dreidimensionalen bleibt die Drehachse fest, was die $1$ auf der Diagonalen bewirkt.

> [!satz] Eigenschaften
> $$R(\alpha)^{-1} = R(-\alpha), \qquad |R(\alpha)\,\vec{a}| = |\vec{a}|, \qquad \det R(\alpha) = \cos^2\alpha + \sin^2\alpha = 1$$
> Das negative Vorzeichen steht oben rechts. Schneller Test: $R(0)$ muss die Einheitsmatrix $\mathbb{1}$ sein.

> [!example]- Längenerhaltung
> $R(\alpha)\,(x,y)^T = (x\cos\alpha - y\sin\alpha,\; x\sin\alpha + y\cos\alpha)^T$. Quadriert man die Komponenten und addiert, heben sich die Mischterme $\mp 2xy\cos\alpha\sin\alpha$ auf, und mit $\sin^2\alpha + \cos^2\alpha = 1$ bleibt $x^2 + y^2$.

Siehe auch: [[Determinante (Vorkurs)|Determinante]], [[Inverse Matrix]], [[Trigonometrischer Pythagoras]], [[Mitgedrehte Basis]], [[Matrix]]

**Weiterführend (1. Semester):** [[Matrix als lineare Abbildung]]
