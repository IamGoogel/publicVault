---
modul: Vorkurs Physik
fach: Physik
semester: 0
part: "Thema Volumen- und Flächenintegrale"
Kurs: Vorkurs Physik
Verstaendnis: 0
gelesen: false
geuebt: false
tags: [vorkurs, vorkurs-physik]
---

> [!definition] Flächenelement der Kugel
> $dA = dx\,dy$ gilt nur für ein ebenes Stück in der $x$-$y$-Ebene. Auf einer Kugeloberfläche ist $r = R$ konstant, und von den drei Kanten des Volumenelements entfällt die radiale:
> $$dA = \underbrace{R\,d\vartheta}_{\text{Längenkreis}}\cdot\underbrace{R\sin\vartheta\,d\varphi}_{\text{Breitenkreis}} = R^2\sin\vartheta\,d\vartheta\,d\varphi$$
> Zum Vergleich: $dV = r^2\sin\vartheta\,dr\,d\vartheta\,d\varphi$ und $dA = R^2\sin\vartheta\,d\vartheta\,d\varphi$. Es fehlt das $dr$, und das variable $r^2$ wird zur Konstanten $R^2$, die man vor das Integral ziehen kann.

> [!note] Häufiger Fehler: Fläche und Volumen verwechseln
> Wer bei einer Kugelfläche $dr\,d\vartheta\,d\varphi$ schreibt, berechnet ein Volumen. Die Rechnung geht problemlos auf und beantwortet die falsche Frage. Über $r$ wird auf einer Fläche nicht integriert, sondern $r = R$ eingesetzt — auch im Integranden. Kontrolle: Differentiale zählen (zwei bei Flächen, drei bei Volumina) und die Einheit prüfen, $[R^2\,d\vartheta\,d\varphi] = \mathrm{m^2}$.

> [!example]- Fläche einer Kugelkappe $0 \leq \vartheta \leq \vartheta_0$
> $\vartheta$ läuft von $0$ bis $\vartheta_0$, $\varphi$ einmal um die Achse, $R^2$ steht vor dem Integral:
> $$A = \int_0^{2\pi}\!\!\int_0^{\vartheta_0}R^2\sin\vartheta\,d\vartheta\,d\varphi = R^2\Big[-\cos\vartheta\Big]_0^{\vartheta_0}\cdot 2\pi = 2\pi R^2\,(1 - \cos\vartheta_0)$$
> Grenzfälle: Für $\vartheta_0 = \pi$ ist $\cos\pi = -1$ und man erhält die ganze Oberfläche $4\pi R^2$; für $\vartheta_0 = \frac{\pi}{2}$ die Hälfte davon.

Siehe auch: [[Volumenelement]], [[Kugelkoordinaten]], [[Fluss durch eine Fläche]]
