---
modul: Vorkurs Physik
fach: Physik
semester: 0
part: "Thema Differentialoperatoren"
Kurs: Vorkurs Physik
Verstaendnis: 0
gelesen: false
geuebt: false
tags: [vorkurs, vorkurs-physik]
---

> [!definition] Laplace-Operator
> Auf ein Skalarfeld $f$ angewandt:
> $$\nabla^2 f = \Delta f = \nabla\cdot(\nabla f) = \frac{\partial^2 f}{\partial x^2} + \frac{\partial^2 f}{\partial y^2} + \frac{\partial^2 f}{\partial z^2}$$
> Aus einem Skalarfeld entsteht wieder ein Skalarfeld. Gebräuchlich sind sowohl $\nabla^2$ als auch $\Delta$, ebenso $\frac{\partial^2 f}{\partial x^2}$ und $\partial_{xx} f$.

> [!note] Anwendung auf Vektorfelder und Produkte
> Da $\nabla^2$ Funktionen auf Funktionen abbildet, kann man ihn auf jede Komponente eines Vektorfelds einzeln anwenden: $\nabla^2\vec{F} = (\nabla^2 F_x, \nabla^2 F_y, \nabla^2 F_z)^T$ — wieder ein Vektorfeld.
> Produkte multipliziert man zuerst aus, z. B. $(xy)^2 = x^2 y^2$. So erkennt man, welche Größe beim Ableiten als Konstante gilt: $\frac{\partial^2}{\partial x^2}(x^2 y^2) = 2y^2$.

Siehe auch: [[Differentialoperatoren]], [[Gradient]], [[Divergenz]], [[Typprüfung bei Operatoren]], [[Nabla-Operator]]
