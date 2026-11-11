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

> [!definition] Divergenz
> $$\nabla\cdot\vec{F} = \frac{\partial F_x}{\partial x} + \frac{\partial F_y}{\partial y} + \frac{\partial F_z}{\partial z}$$
> Sie verwandelt ein Vektorfeld in ein Skalarfeld und zeigt Quellen und Senken an: $\nabla\cdot\vec{F} > 0$ bedeutet Quelle, $< 0$ Senke, $= 0$ Quellenfreiheit.

> [!example]- Beispiele für Quelle und Senke
> Für $\vec{F} = (x, y, 0)$ ist $\nabla\cdot\vec{F} = 2 > 0$; alle Pfeile weisen nach außen. Für $\vec{F} = (-x,-y,0)$ ist $\nabla\cdot\vec{F} = -2 < 0$; alle Pfeile weisen nach innen. Im Ursprung hat man jeweils einen Punkt statt eines Pfeils.

> [!note] Physikalischer Bezug
> Ein Beispiel ist $\nabla\cdot\vec{E} = \rho/\varepsilon_0$: Elektrische Ladungen sind die Quellen des $E$-Feldes ([[Maxwell-Gleichungen]]). Die zugehörige Integralaussage ist der [[Satz von Gauß]].

Siehe auch: [[Differentialoperatoren]], [[Skalarprodukt]], [[Fluss durch eine Fläche]], [[Laplace-Operator]], [[Nabla-Operator]]

**Weiterführend (1. Semester):** [[Kontinuitätsgleichung]]
