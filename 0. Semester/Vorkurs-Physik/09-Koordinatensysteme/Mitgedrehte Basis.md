---
modul: Vorkurs Physik
fach: Physik
part: "Thema Koordinatensysteme"
keywords: co-rotating basis, basis vectors, polar coordinates
---

# Mitgedrehte Basis

#vorkurs #vorkurs-physik

> [!definition] Mitgedrehte Basis
> „Radial nach außen“ bedeutet bei $(2\,|\,0)$ nach rechts, bei $(0\,|\,2)$ nach oben — die Richtung hängt also vom Ort ab. In der Ebene gilt:
> $$\hat{e}_\varrho = \begin{pmatrix} \cos\varphi \\ \sin\varphi \end{pmatrix}, \qquad \hat{e}_\varphi = \begin{pmatrix} -\sin\varphi \\ \cos\varphi \end{pmatrix}$$
> Beide haben die Länge 1 und stehen senkrecht aufeinander: $\hat{e}_\varrho\cdot\hat{e}_\varphi = -\cos\varphi\sin\varphi + \sin\varphi\cos\varphi = 0$.

> [!satz] Ableitung nach dem Winkel
> Da die Basisvektoren vom Ort abhängen, kann man sie selbst ableiten:
> $$\frac{\partial\hat{e}_\varrho}{\partial\varphi} = \hat{e}_\varphi, \qquad \frac{\partial\hat{e}_\varphi}{\partial\varphi} = -\hat{e}_\varrho$$
> Eine Ableitung nach dem Winkel dreht um weitere $90^\circ$, zwei Ableitungen um $180^\circ$ — daher das Minuszeichen. Das dient zugleich als Kontrolle.

> [!note] Vorgehen: Basisvektoren krummliniger Koordinaten
> Für jede Koordinate $q$ funktioniert dasselbe Schema (polar, zylindrisch, sphärisch): ableiten, normieren, Orientierung prüfen.
> 1. $\vec{r}$ in kartesischen Komponenten als Funktion aller krummlinigen Koordinaten aufschreiben.
> 2. Partiell nach $q$ ableiten, die anderen Koordinaten dabei konstant halten: Das ergibt den Tangentenvektor der $q$-Koordinatenlinie.
> 3. Seinen Betrag berechnen (dabei hilft [[Trigonometrischer Pythagoras]]).
> 4. Durch den Betrag dividieren: $\hat{e}_q = \frac{\partial\vec{r}/\partial q}{|\partial\vec{r}/\partial q|}$.
> 5. Kontrollen: Länge 1, Skalarprodukte mit den anderen Basisvektoren null.
> 6. Orientierung: In der angegebenen Reihenfolge soll ein Rechtssystem entstehen, $\hat{e}_1\times\hat{e}_2 = \hat{e}_3$ (zyklisch). So sind $(x,y,z)$, $(\varrho,\varphi,z)$ und $(r,\vartheta,\varphi)$ aufgebaut; darum gilt $\hat{e}_\varphi\times\hat{e}_r = \hat{e}_\vartheta$ und nicht das Umgekehrte.

Siehe auch: [[Polarkoordinaten]], [[Zylinderkoordinaten]], [[Kugelkoordinaten]], [[Kreuzprodukt]], [[Geschwindigkeit in Zylinderkoordinaten]], [[Drehmatrix]], [[Einheitsvektor]]

**Weiterführend (1. Semester):** [[Kreisbewegung]], [[Rotierende Bezugssysteme]]
