---
modul: Vorkurs Physik
fach: Physik
part: "Thema Differentialgleichungen"
keywords: solution methods, differential equations
---

# Lösungsverfahren auswählen

#vorkurs #vorkurs-physik

> [!note] Entscheidungsweg in vier Fragen
> 1. Fehlt die gesuchte Funktion auf der rechten Seite? Dann wird direkt integriert, so oft wie die Ordnung angibt ([[Differentialgleichung durch Integration]]).
> 2. Ist die Gleichung von erster Ordnung und lässt sich als Produkt aus einem $x$- und einem $y$-Faktor schreiben? Dann hilft [[Separation der Variablen]] — linear oder nicht.
> 3. Ist sie linear (Funktion und Ableitungen nur in erster Potenz), zweiter Ordnung, homogen, mit konstanten Koeffizienten? Dann Exponentialansatz und reelle Form ([[Schwingungsgleichung]]).
> 4. Passt nichts davon, lässt sich die Gleichung mit den Mitteln dieses Kurses nicht geschlossen lösen. Auch das ist ein Ergebnis.
> Am Ende immer zwei Dinge: die Integrationskonstanten mithilfe der gegebenen Anfangs- bzw. Randwerte festlegen (ihre Zahl entspricht der Ordnung) und die Lösung probeweise in die Ausgangsgleichung einsetzen.

> [!example]- Fall 4 ist in der Physik der Normalfall
> Realistische Bewegungsgleichungen lassen sich meist nicht geschlossen lösen; man rechnet sie in kleinen Zeitschritten numerisch. Ein Beispiel ist ein rotierender Ball mit Magnus-Kraft als gekoppeltes nichtlineares System, siehe [[Magnus-Experiment]]. Kommt Dämpfung hinzu, $\ddot{x} + 2\delta\dot{x} + \omega_0^2 x = 0$, trägt derselbe Ansatz noch: Er liefert eine Schwingung, deren Amplitude wie $e^{-\delta t}$ abnimmt. Mit einer äußeren Anregung wird die Gleichung inhomogen, und es entsteht Resonanz.

Siehe auch: [[Differentialgleichung]], [[Allgemeine und spezielle Lösung]]
