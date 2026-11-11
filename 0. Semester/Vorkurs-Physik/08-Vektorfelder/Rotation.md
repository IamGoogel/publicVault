---
modul: Vorkurs Physik
fach: Physik
part: "Thema Vektorfelder"
keywords: curl, rotation, vector field
---

# Rotation

#vorkurs #vorkurs-physik

> [!definition] Rotation
> Die Rotation ist das Kreuzprodukt aus dem Nabla-Vektor und dem Feld:
> $$\nabla\times\vec{F} = \mathrm{rot}\,\vec{F} = \begin{pmatrix} \frac{\partial F_z}{\partial y} - \frac{\partial F_y}{\partial z} \\ \frac{\partial F_x}{\partial z} - \frac{\partial F_z}{\partial x} \\ \frac{\partial F_y}{\partial x} - \frac{\partial F_x}{\partial y} \end{pmatrix}, \qquad \vec{F}\text{ wirbelfrei} \Longleftrightarrow \nabla\times\vec{F} = 0$$
> Anstelle jedes Produkts $a_y b_z$ im Kreuzprodukt steht hier „$F_z$ nach $y$ ableiten“. Die Zeilen folgen der zyklischen Reihenfolge $x\to y\to z\to x$. Kontrolle: Jeder Eintrag enthält genau die beiden Indizes, die nicht zu seiner eigenen Zeile gehören.

> [!satz] Test auf Potentialfelder
> Ein Gradientenfeld besteht den Test stets:
> $$\nabla\times(\nabla U) = 0$$
> In jeder Zeile treten zwei gemischte zweite Ableitungen von $U$ auf, deren Reihenfolge keine Rolle spielt (Satz von Schwarz). Die Rotation muss überall null sein, nicht nur an einzelnen Stellen. Konstante Felder sind immer wirbelfrei.

> [!example]- $\vec{B} = (y, -x, 0)^T$
> Es ist $\nabla\times\vec{B} = (0, 0, -2)^T$; das Feld dreht sich im Uhrzeigersinn um die $z$-Achse. Die Wirbelachse liegt senkrecht zur Drehebene; $\nabla\times\vec{B}$ zeigt längs dieser Achse, und seine Länge gibt die Stärke des Wirbels an.

> [!note] Felder in der Ebene
> Für die Rotation ergänzt man ein ebenes Feld auf drei Komponenten (dritte Komponente null, keine Abhängigkeit von $z$). Es bleibt nur $\nabla\times\vec{F} = \big(0,\,0,\,\frac{\partial F_y}{\partial x} - \frac{\partial F_x}{\partial y}\big)^T$. Ein ebenes Feld kann nur um eine Achse senkrecht zur Ebene wirbeln.

Siehe auch: [[Konservative Kraft]], [[Differentialoperatoren]], [[Kreuzprodukt]], [[Maxwell-Gleichungen]], [[Nabla-Operator]], [[Potential aus Kraftfeld bestimmen]], [[Linienintegral berechnen]], [[Wegunabhängigkeit]]

**Weiterführend (1. Semester):** [[Konservative Kräfte und Potential]], [[Zirkulation und Wirbel]]
