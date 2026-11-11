---
modul: ExPhy I
fach: Physik
part: "Kap. 2.5, 2.5.1"
keywords: work, line integral, parametrization
---

# Arbeit und Wegintegral

#exphy1 #mechanics #energy #atomic

$$W=\int_C\mathbf F\cdot d\mathbf r$$
Steht $\mathbf F\perp d\mathbf r$, ist $W=0$ — z. B. Zentripetalkraft bei Kreisbewegung; ebenso magnetische Kräfte.

**Berechnung durch Parametrisierung.** Weg $C$: $\mathbf r(t)$, $t\in[t_1,t_2]$ (stetig, stückweise stetig differenzierbar, richtiger Durchlaufsinn). Mit $d\mathbf r=\mathbf r^\prime(t)\,dt$:
$$W=\int_{t_1}^{t_2}\mathbf F\bigl(\mathbf r(t)\bigr)\cdot\mathbf r^\prime(t)\,dt$$
Merkregel: *zerlegen – multiplizieren – aufsummieren*. Die Parametrisierung ist nicht eindeutig; alle zulässigen mit gleichem Durchlaufsinn liefern dasselbe $W$. Tipps: Graph $y=g(x)$ → $x=t$, $y=g(t)$; Gerade → lineare Interpolation; Kreis → $\cos^2t+\sin^2t=1$.

> [!warning] Ersatzweg nur bei konservativen Feldern
> Nur wenn $\mathbf F$ konservativ ist, ist $W$ wegunabhängig und ein bequemerer Weg erlaubt ([[Konservative Kräfte und Potential]]). Sonst muss der tatsächliche Weg ausgewertet werden.

**Wird gebraucht für:** Zirkulation ([[Zirkulation und Wirbel]]), später Spannungs- und Umlaufintegrale.
**Mathematik:** [[Stetigkeit einer Funktion]]
