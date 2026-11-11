---
modul: Vorkurs Physik
fach: Physik
semester: 0
part: "Thema Vektorfelder"
Kurs: Vorkurs Physik
Verstaendnis: 0
gelesen: false
geuebt: false
tags: [vorkurs, vorkurs-physik]
---

> [!definition] Gradient
> Wendet man $\nabla$ auf ein Skalarfeld $U$ an, erhält man ein Vektorfeld, den Gradienten:
> $$\nabla U = \mathrm{grad}\,U = \begin{pmatrix} \frac{\partial U}{\partial x} \\ \frac{\partial U}{\partial y} \\ \frac{\partial U}{\partial z} \end{pmatrix}$$
> Er weist in die Richtung des stärksten Anstiegs und ist senkrecht zu den [[Höhenlinie|Höhenlinien]].

> [!satz] Felder mit Kugelsymmetrie
> Hängt ein Feld nur vom Abstand $r = |\vec{r}|$ ab, nutzt man $|\vec{r}|^2 = x^2 + y^2 + z^2$ und erhält
> $$\nabla f(r) = f'(r)\,\frac{\vec{r}}{r}$$
> Praktisches Vorgehen: zunächst in Koordinaten schreiben, dann ableiten und das Ergebnis wieder durch $\vec{r}$ ausdrücken, z. B. $(2x, 2y, 2z)^T = 2\vec{r}$. Diesen letzten Schritt vergisst man leicht, dabei ist er das eigentliche Ziel.

> [!example]- $f(r) = 1/|\vec{r}|$ (Potential einer Punktmasse, bis auf Konstanten)
> Mit $f = (x^2+y^2+z^2)^{-1/2}$ und der [[Kettenregel]]:
> $$\frac{\partial f}{\partial x} = -\tfrac{1}{2}\,(x^2+y^2+z^2)^{-3/2}\cdot 2x = -\frac{x}{r^3} \;\Rightarrow\; \nabla f = -\frac{\vec{r}}{r^3}$$
> Kontrolle 1: $f(r) = r^{-1}$ hat $f'(r) = -r^{-2}$. Kontrolle 2: Der Gradient zeigt zum Ursprung hin, weil $1/r$ dort größer wird. Kontrolle 3: $|\nabla f| = 1/r^2$ ergibt das bekannte Abstandsgesetz.

Siehe auch: [[Nabla-Operator]], [[Kraft und Potential]], [[Skalarfeld und Vektorfeld]], [[Differentialoperatoren]], [[Laplace-Operator]]

**Weiterführend (1. Semester):** [[Konservative Kräfte und Potential]]
