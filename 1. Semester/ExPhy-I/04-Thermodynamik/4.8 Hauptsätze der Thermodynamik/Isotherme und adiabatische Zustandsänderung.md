---
modul: ExPhy I
fach: Physik
part: "Kap. 4.8.3"
keywords: isothermal, adiabatic, Poisson equations, p-V diagram
---

# Isotherme und adiabatische Zustandsänderung

#exphy1 #thermodynamics #laws #atomic

**Isotherm** ($T=$ const., $\Delta U=0$ beim idealen Gas): zugeführte Wärme = geleistete Arbeit,
$$\Delta Q=-\Delta W=nRT\ln\frac{V_2}{V_1},\qquad pV=\text{const.}$$

**Adiabatisch** ($\delta Q=0$; thermisch isoliert oder so schnell, dass kein Austausch stattfindet): $dU=-p\,dV$, also $\tfrac f2nR\,dT=-\tfrac{nRT}V\,dV$ ⇒ $\tfrac f2\tfrac{dT}T=-\tfrac{dV}V$. Integration:
$$TV^{\kappa-1}=\text{const.},\qquad pV^\kappa=\text{const.},\qquad\kappa=\frac{C_p}{C_V}$$
Wegen $\kappa>1$ verlaufen Adiabaten im $p$-$V$-Diagramm **steiler** als Isothermen: Bei Ausdehnung ohne Wärmezufuhr fällt zusätzlich die Temperatur.

```
 p │ ╲
   │  ╲╲  Isotherme pV = const
   │   ╲ ╲╲ Adiabate pV^κ = const (steiler)
   └──────────── V
```

**Baut auf:** [[Erster Hauptsatz]] · [[Wärmekapazität und Adiabatenindex]] · [[Ideale Gasgleichung]]
**Wird gebraucht für:** [[Carnot-Prozess]] · [[Schallgeschwindigkeit in Medien]]
