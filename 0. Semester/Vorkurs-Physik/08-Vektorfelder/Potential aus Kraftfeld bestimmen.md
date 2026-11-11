---
modul: Vorkurs Physik
fach: Physik
part: "Thema Vektorfelder"
keywords: potential, force field, integration
---

# Potential aus Kraftfeld bestimmen

#vorkurs #vorkurs-physik

> [!definition] Vorgehen: Existenz eines Potentials prüfen und berechnen
> Gegeben ist $\vec{F}$, gesucht ein $U$ mit $\vec{F} = -\nabla U$.
> 1. Vorab $\nabla\times\vec{F}$ berechnen. Ist das Ergebnis nicht der Nullvektor, gibt es kein Potential — Ende. Außerdem beachten, wo $\vec{F}$ definiert ist.
> 2. Die erste Komponente integrieren: $U = -\int F_x\,dx + C_1(y,z)$, wobei $y$ und $z$ als konstant gelten. Die Integrationskonstante ist hier eine Funktion; schriebe man nur „$+\text{const}$“, gingen alle Terme ohne $x$ verloren.
> 3. Nach $y$ ableiten und das Ergebnis mit $-F_y$ gleichsetzen. Alle Terme mit $x$ müssen sich aufheben. Es bleibt eine Gleichung für $\frac{\partial C_1}{\partial y}$.
> 4. Nach $y$ integrieren: $C_1(y,z) = \int(\dots)\,dy + C_2(z)$; dann nach $z$ ableiten und mit $-F_z$ gleichsetzen. Am Ende bleibt eine echte Konstante, denn das Potential ist nur bis auf einen additiven Term eindeutig.
> 5. Kontrolle: $-\nabla U$ berechnen und komponentenweise mit $\vec{F}$ vergleichen.

> [!example]- $\vec{A} = (2xy,\; x^2 + z,\; y)^T$
> 1. $\nabla\times\vec{A} = (1-1,\; 0-0,\; 2x-2x)^T = \vec{0}$ — ein Potential existiert.
> 2. $U = -\int 2xy\,dx = -x^2 y + C_1(y,z)$.
> 3. $\frac{\partial U}{\partial y} = -x^2 + \frac{\partial C_1}{\partial y} \overset{!}{=} -(x^2+z)$, also $\frac{\partial C_1}{\partial y} = -z$ (das $x$ fällt heraus — ein gutes Zeichen).
> 4. $C_1 = -yz + C_2(z)$; $\frac{\partial U}{\partial z} = -y + C_2'(z) \overset{!}{=} -y$, also $C_2' = 0$ und $U = -(x^2 y + y z) + \text{const}$.
> 5. Kontrolle: $-\nabla U = (2xy,\; x^2+z,\; y)^T = \vec{A}$.

> [!note] Andere Vorzeichenkonvention: $+\nabla f$
> Manchmal ist $\vec{F} = +\nabla f$ verlangt, also $f = -U$. Erhält man stattdessen $-\vec{F}$, wurden die Konventionen vertauscht. Beispiel mit $\nabla f = \vec{F}$ für $\vec{F} = (2xy,\; x^2 + 2y,\; 1)^T$: $f = x^2 y + y^2 + z + C$.
> Hat der Integrand die Form „Ableitung der inneren Funktion mal Funktion der inneren Funktion“, hilft die [[Substitution]]: Mit $Z = x^2 + y^2$ gilt $\int 2x\cos(x^2+y^2)\,dx = \sin Z$.

Siehe auch: [[Rotation]], [[Kraft und Potential]], [[Konservative Kraft]], [[Integrationskonstante]], [[Wegunabhängigkeit]]

**Weiterführend (1. Semester):** [[Konservative Kräfte und Potential]]
