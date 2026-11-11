---
modul: ExPhy I
fach: Physik
part: "Kap. 4.9, 4.9.1"
keywords: cyclic process, Carnot cycle, work balance
---

# Carnot-Prozess

#exphy1 #thermodynamics #cycles #atomic

**Kreisprozess:** periodische Folge von Zustandsänderungen, die das System in den Ausgangszustand zurückführt (Stirling-, Otto-Motor). Grundform ist der **Carnot-Prozess** aus zwei Isothermen ($T_w$, $T_k$) und zwei Adiabaten ([[Isotherme und adiabatische Zustandsänderung]]).

| Schritt | Art | Wärme | Arbeit |
|---|---|---|---|
| 1→2 | isotherme Expansion bei $T_w$ | aufgenommen $\Delta Q_w=nRT_w\ln\frac{V_2}{V_1}$ | $\Delta U=0$ |
| 2→3 | adiabatische Expansion | $0$ | $\Delta W_{23}=nC_V(T_k-T_w)<0$ |
| 3→4 | isotherme Kompression bei $T_k$ | abgegeben $-nRT_k\ln\frac{V_2}{V_1}$ | $\Delta U=0$ |
| 4→1 | adiabatische Kompression | $0$ | $\Delta W_{41}=nC_V(T_w-T_k)>0$ |

```
 p │ 1 ╲___ T_w
   │       ╲  2
   │ 4      ╲
   │  ╲___ T_k ╲ 3
   └───────────── V      Fläche = Arbeit pro Umlauf
```
- Die Adiabatenarbeiten heben sich auf (gleiche Temperaturdifferenz, $C_V$ konstant).
- Aus den Adiabaten: $V_2/V_1=V_3/V_4$.
- Gesamtarbeit (vom System geleistet): $-\Delta W=nR\,(T_w-T_k)\ln\dfrac{V_2}{V_1}$.

**Baut auf:** [[Isotherme und adiabatische Zustandsänderung]] · [[Erster Hauptsatz]]
**Wird gebraucht für:** [[Wirkungsgrad und Carnotscher Satz]] · [[Satz von Clausius]]
