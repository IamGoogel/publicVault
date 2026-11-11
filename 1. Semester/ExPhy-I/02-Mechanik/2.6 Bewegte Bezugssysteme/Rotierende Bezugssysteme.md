---
modul: ExPhy I
fach: Physik
part: "Kap. 2.6.2"
keywords: rotating frame, Coriolis, centrifugal, centripetal
---

# Rotierende Bezugssysteme

#exphy1 #mechanics #reference-frames #atomic

Ableitungsregel für einen Vektor $\mathbf A$ (die Basisvektoren von $K^\prime$ rotieren):
$$\frac{d\mathbf A}{dt}=\frac{d^\prime\mathbf A}{dt}+\boldsymbol\omega\times\mathbf A$$
Zweimal angewandt:
$$\frac{d^2\mathbf r}{dt^2}=\frac{d^{\prime2}\mathbf r}{dt^2}+2\boldsymbol\omega\times\mathbf v_\text{rel}+\boldsymbol\omega\times(\boldsymbol\omega\times\mathbf r)$$
Für einen in $K$ unbeschleunigten Körper sieht $K^\prime$ zwei Trägheitskräfte:
$$\mathbf F_C=-2m\,\boldsymbol\omega\times\mathbf v_\text{rel},\qquad\mathbf F_Z=-m\,\boldsymbol\omega\times(\boldsymbol\omega\times\mathbf r)$$
- Coriolis steht **quer zur Relativbewegung**, Zentrifugal zeigt **radial nach außen**.
- **Zentripetalkraft** $=-\mathbf F_Z$: eingeprägte Kraft zum Zentrum; die Zentrifugalkraft ist ihr Gegenstück im mitrotierenden System.
- Ruht der Körper in $K^\prime$: $\mathbf v_\text{rel}=0$, $\mathbf v=\boldsymbol\omega\times\mathbf r$. Ruht er in $K$: $\mathbf v_\text{rel}=-\boldsymbol\omega\times\mathbf r$.

Vorlesungsversuch: Ein Körper läuft über eine rotierende Scheibe nach außen — in $K$ gerade, in $K^\prime$ gekrümmt.

**Baut auf:** [[Kreisbewegung]] · [[Galilei-Transformation]]
**Wird gebraucht für:** [[Corioliskraft auf der rotierenden Erde]] · [[Hauptachsen und Eulersche Kreiselgleichungen]]
