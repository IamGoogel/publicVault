---
modul: ExPhy I
fach: Physik
part: "Kap. 3.3.3"
keywords: wave equation, Laplace operator, partial derivatives
---

# Wellengleichung

#exphy1 #oscillations-waves #waves #atomic

Die Definition geht umgekehrt vor: Eine Differentialgleichung erklärt alles, was sie löst, zur Welle. Für ein Feld $u(\mathbf r,t)$:
$$\frac{\partial^2u}{\partial t^2}=v_\text{ph}^2\,\Delta u,\qquad\Delta=\frac{\partial^2}{\partial x^2}+\frac{\partial^2}{\partial y^2}+\frac{\partial^2}{\partial z^2}$$
Alle Ableitungen sind **partiell**, denn $u$ hängt von Ort und Zeit ab; die Ortskoordinaten sind von $t$ unabhängige Variablen. Auch nicht periodische Vorgänge (einzelner Puls) sind eingeschlossen.

**Probe** mit $u_0\cos(kx-\omega t)$: $\partial_t^2u=-\omega^2u$, $\Delta u=-k^2u$ ⇒ $\omega^2=v_\text{ph}^2k^2$, also genau dann Lösung, wenn $v_\text{ph}=\omega/k$.

**Baut auf:** [[Harmonische Welle und Wellenzahl]] · [[Phasengeschwindigkeit und Dispersion]]
**Wird gebraucht für:** [[Schallgeschwindigkeit in Medien]] (Herleitung im Stab)
