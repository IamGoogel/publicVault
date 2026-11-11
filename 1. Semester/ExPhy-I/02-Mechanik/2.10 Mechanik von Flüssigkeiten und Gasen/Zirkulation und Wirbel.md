---
modul: ExPhy I
fach: Physik
part: "Kap. 2.10.3"
keywords: circulation, vorticity, curl, Stokes theorem
---

# Zirkulation und Wirbel

#exphy1 #mechanics #fluids #atomic

$$Z=\oint_C\mathbf v\cdot d\mathbf s\ \overset{\text{Stokes}}{=}\ \int_A\operatorname{rot}\mathbf v\cdot d\mathbf A\ \approx\ \lvert\operatorname{rot}\mathbf v\rvert\,\lvert A\rvert$$
Aufbau wie das Arbeitsintegral ([[Arbeit und Wegintegral]]), mit $\mathbf v$ statt $\mathbf F$. Rotation = **Wirbeldichte** (Zirkulation pro Fläche), analog Divergenz = Fluss pro Volumen.

- Gleichförmige Parallelströmung: Querstücke $\perp$, Längsstücke heben sich auf ⇒ $Z=0$, wirbelfrei.
- Geschwindigkeit wächst quer zur Strömung ⇒ Rest bleibt, $Z\ne0$: **wirbelbehaftet** — ohne sichtbare Kreisbewegung, auch bei laminarer Strömung.
- Für **reibungsfreie** Fluide gilt $\dfrac{dZ}{dt}=0$: Wirbel bleiben erhalten (Beispiel: „Auge des Jupiters“). Bei Reibung klingen Wirbel ab.

> [!warning] Satz von Stokes
> Voraussetzungen: orientierte, berandete Fläche $A$ mit Rand $C$ (Rechte-Hand-Orientierung), stetig differenzierbares Feld.

**Baut auf:** [[Arbeit und Wegintegral]] · [[Konservative Kräfte und Potential]] (rot = 0)
**Siehe auch:** [[Kontinuitätsgleichung]] (Divergenz)
