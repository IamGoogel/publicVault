---
modul: Vorkurs Physik
fach: Physik
part: "Thema Vektorfelder"
keywords: level line, contour line, scalar field
---

# Höhenlinie

#vorkurs #vorkurs-physik

> [!definition] Höhenlinie
> Eine Höhenlinie verbindet alle Punkte, an denen ein Skalarfeld denselben Wert hat. Andere Namen sind Konturlinie, Isolinie und (beim Potential) Äquipotentiallinie.
> Vorgehen: den Funktionswert gleich einer Konstanten setzen ($f(x,y) = c$), nach einer bekannten Kurve auflösen und das für verschiedene $c$ wiederholen — es entsteht eine Kurvenschar.

> [!satz] Der Gradient steht senkrecht auf den Höhenlinien
> Bewegt man sich um $d\vec{r}$ entlang der Linie, bleibt der Funktionswert gleich; die Änderung (das totale Differential) lässt sich als Skalarprodukt schreiben:
> $$0 = df = \frac{\partial f}{\partial x}dx + \frac{\partial f}{\partial y}dy + \frac{\partial f}{\partial z}dz = \nabla f\cdot d\vec{r}$$
> Sind beide Vektoren vom Nullvektor verschieden und ist ihr Skalarprodukt null, stehen sie senkrecht zueinander. Bei festem Wertabstand $\Delta f$ beträgt der Abstand der Linien etwa $\Delta f / |\nabla f|$; dicht beieinanderliegende Linien bedeuten also einen großen Gradienten.

> [!example]- $h(x,y) = x^2 + 4y^2$
> Mit $h = c$ erhält man $\frac{x^2}{c} + \frac{y^2}{c/4} = 1$, für $c > 0$ also Ellipsen mit den Halbachsen $\sqrt{c}$ und $\frac{1}{2}\sqrt{c}$. Der Gradient ist $\nabla h = (2x, 8y)$; im Punkt $(1;\,0{,}5)$ gilt $\nabla h = (2,4)^T$, und die Tangente dort hat die Richtung $(1,-\frac{1}{2})$. Das Skalarprodukt ist null, wie es sein muss.

Siehe auch: [[Gradient]], [[Konturplot]], [[Skalarprodukt]], [[Skalarfeld und Vektorfeld]]
