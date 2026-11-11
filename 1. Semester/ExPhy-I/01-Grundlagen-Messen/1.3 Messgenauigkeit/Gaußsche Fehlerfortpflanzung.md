---
modul: ExPhy I
fach: Physik
part: "Kap. 1.3.5"
keywords: Gaussian error propagation, quadratic addition
---

# Gaußsche Fehlerfortpflanzung

#exphy1 #measurement #error-propagation #atomic

Für **unabhängige** Einzelfehler heben sich diese teilweise auf; der absolute mittlere Fehler lautet
$$\sigma_R=\sqrt{\Bigl(\frac{\partial R}{\partial x}\Bigr)^2\sigma_x^2+\Bigl(\frac{\partial R}{\partial y}\Bigr)^2\sigma_y^2+\Bigl(\frac{\partial R}{\partial z}\Bigr)^2\sigma_z^2}$$
Die Beiträge addieren sich **quadratisch**; der größte Einzelbeitrag dominiert. Ist ein Beitrag um Faktor 3 kleiner als der größte, lohnt weiteres Feilen kaum.

> [!warning] Voraussetzung
> Unabhängigkeit der Fehler. Bei korrelierten oder systematischen Fehlern ist der [[Größtfehler]] die sichere Wahl.

**Baut auf:** [[Größtfehler]]
**Wird gebraucht für:** [[Fehler des Mittelwerts]] · [[Fadenpendel - Bestimmung von g]]
