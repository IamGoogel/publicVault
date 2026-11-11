---
modul: Vorkurs Physik
fach: Physik
part: "Thema Vektorfelder"
keywords: force, potential, gradient
---

# Kraft und Potential

#vorkurs #vorkurs-physik

> [!definition] Kraft und Potential
> $$\vec{F} = -\nabla V \quad\Longleftrightarrow\quad \nabla V = \mathrm{grad}\,V = -\vec{F}$$
> Die zweite Schreibweise ergibt sich durch Multiplikation mit $-1$. Beim Umformen wird das Minus gern vergessen.

> [!note] Wozu das Minuszeichen?
> Es ist mehr als eine Festlegung: Der Gradient weist zu höherem Potential, die Kraft zu niedrigerem — ein Ball rollt bergab, nicht bergauf. An $F_x = -\frac{\partial U}{\partial x}$ erkennt man die Einheit des Potentials: $[U] = \mathrm{N\,m} = \mathrm{J}$, es ist eine Energie.

> [!example]- Federkraft
> $F(x) = -k\,x$ und $V(x) = \frac{1}{2}k\,x^2$ (beim Ableiten ist $k$ eine Konstante). Kontrolle: $\nabla V = k\,x = -F$.
> Verhalten im Unendlichen: Da jeder Summand $x^{-n}$ für $x \to \infty$ gegen null geht, spüren sich zwei weit entfernte Körper nicht mehr.

Siehe auch: [[Konservative Kraft]], [[Gradient]], [[Potential aus Kraftfeld bestimmen]], [[Wegunabhängigkeit]]

**Weiterführend (1. Semester):** [[Konservative Kräfte und Potential]]
