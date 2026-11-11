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

> [!definition] Bahnkurve und Parametrisierung
> Eine Parametrisierung bildet jeden Parameterwert $t$ eines Intervalls auf einen Punkt $\vec{r}(t)$ ab. Das Intervall gehört zur Angabe dazu, sonst bleibt offen, welcher Teil der Kurve gemeint ist. Eine in Koordinaten beschriebene Bewegung wird zur Bahnkurve, wenn man $\varrho(t)$, $\varphi(t)$, $z(t)$ in die Umrechnungsformeln einsetzt.

> [!satz] Kreisbewegung
> Ist $t$ die Zeit in Sekunden, kann der Winkel nicht einfach $t$ sein, da Winkel keine Einheit tragen:
> $$\varphi(t) = \omega\,t = \frac{2\pi}{T}\,t$$
> Dabei ist $T$ die Umlaufdauer und $\omega = \frac{2\pi}{T}$ die Kreisfrequenz. Kontrolle: Für $t = T$ ergibt sich $\varphi = 2\pi$, also genau ein Umlauf.

> [!example]- Schraubenlinie
> Ein Punkt kreist im konstanten Abstand $R$ um die $z$-Achse mit der Umlaufdauer $T$ und steigt mit konstanter Geschwindigkeit $v_z$: $\varrho(t) = R$, $\varphi(t) = \frac{2\pi t}{T}$, $z(t) = v_z t$. Eingesetzt ergibt sich
> $$\vec{r}(t) = \begin{pmatrix} R\cos(2\pi t/T) \\ R\sin(2\pi t/T) \\ v_z\,t \end{pmatrix}$$
> Kontrollen: $\sqrt{x^2+y^2} = R$; $\vec{r}(0) = (R,0,0)^T$, der Start liegt auf der $x$-Achse; Einheiten $[R] = \mathrm{m}$, $[T] = \mathrm{s}$, $[v_z] = \mathrm{m/s}$, das Argument von Sinus und Kosinus ist einheitenlos. Ganghöhe: Nach $T$ hat sich $\varphi$ um $2\pi$ erhöht (eine Umdrehung) und $z$ um $v_z T$; pro Umdrehung steigt der Punkt also um $h = v_z T$.

Siehe auch: [[Ortsvektor]], [[Geschwindigkeit in Zylinderkoordinaten]], [[Zylinderkoordinaten]], [[Linienintegral]], [[Linienintegral berechnen]]

**Weiterführend (1. Semester):** [[Bahnkurve, Geschwindigkeit und Beschleunigung]]
