---
modul: Vorkurs Physik
fach: Physik
semester: 0
part: "Thema Koordinatensysteme"
Kurs: Vorkurs Physik
Verstaendnis: 0
gelesen: false
geuebt: false
tags: [vorkurs, vorkurs-physik]
---

> [!definition] Zylinderkoordinaten
> Zu den ebenen [[Polarkoordinaten]] kommt als dritte Koordinate die kartesische Höhe $z$. Es gilt $\varrho \in [0,\infty)$, $\varphi \in [0,2\pi)$, $z \in (-\infty,\infty)$:
> $$\vec{r} = \begin{pmatrix} \varrho\cos\varphi \\ \varrho\sin\varphi \\ z \end{pmatrix}, \qquad \varrho = \sqrt{x^2+y^2}, \qquad \varphi = \mathrm{atan2}(y,x), \qquad z = z$$
> Die Basisvektoren der Ebene erhalten eine dritte Komponente $0$; hinzu kommt $\hat{e}_z = (0,0,1)^T$:
> $$\hat{e}_\varrho = (\cos\varphi, \sin\varphi, 0)^T, \quad \hat{e}_\varphi = (-\sin\varphi, \cos\varphi, 0)^T, \quad \vec{r} = \varrho\,\hat{e}_\varrho(\varphi) + z\,\hat{e}_z$$

> [!note] $\varrho$ ist nicht der Abstand zum Ursprung
> Unter der Wurzel steht kein $z^2$: $\varrho$ ist der Abstand zur $z$-Achse. Den Abstand zum Ursprung bezeichnet man mit $r = \sqrt{x^2+y^2+z^2}$; stets gilt $\varrho \leq r$. Beispiel: $(0\,|\,0\,|\,5)$ hat $\varrho = 0$, aber $r = 5$.
> Im Ortsvektor erscheint kein $\hat{e}_\varphi$: Der Winkel ist in der Richtung von $\hat{e}_\varrho$ enthalten, weshalb dieser Vektor sein Argument $\varphi$ behält. Aus $R\,\hat{e}_\varrho(\varphi) + h\,\hat{e}_z$ wird $(R\cos\varphi, R\sin\varphi, h)^T$, ein Kreis mit Radius $R$ in der Höhe $h$. Bleibt eine Koordinate konstant, liegt die Bahn vollständig in der entsprechenden Koordinatenfläche.

Siehe auch: [[Kugelkoordinaten]], [[Mitgedrehte Basis]], [[Volumenelement]], [[Geschwindigkeit in Zylinderkoordinaten]], [[Bahnkurve]], [[Winkelbestimmung mit atan2]]
