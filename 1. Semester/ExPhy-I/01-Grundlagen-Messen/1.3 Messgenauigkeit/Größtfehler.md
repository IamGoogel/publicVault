---
modul: ExPhy I
fach: Physik
part: "Kap. 1.3.5"
keywords: maximum error, partial derivatives, relative error
---

# Größtfehler

#exphy1 #measurement #error-propagation #atomic

Messresultat $R=R(x,y,z)$ mit Standardabweichungen $\sigma_x,\sigma_y,\sigma_z$. Die **pessimistische** Abschätzung nimmt an, alle Einzelabweichungen überlagern sich ungünstig:
$$\sigma_R\le\Bigl\lvert\frac{\partial R}{\partial x}\Bigr\rvert\sigma_x+\Bigl\lvert\frac{\partial R}{\partial y}\Bigr\rvert\sigma_y+\Bigl\lvert\frac{\partial R}{\partial z}\Bigr\rvert\sigma_z .$$

**Beispiel $g=4\pi^2\ell/T^2$:** $\partial_\ell g=4\pi^2T^{-2}$, $\partial_Tg=-8\pi^2\ell T^{-3}$ ⇒
$$\frac{\sigma_g}g\le\frac{\sigma_\ell}\ell+2\,\frac{\sigma_T}T .$$

> [!important] Merksatz
> **Exponenten wirken als Gewichtsfaktoren.** $T$ geht quadratisch ein ⇒ derselbe relative Fehler in $T$ schlägt doppelt so stark durch wie in $\ell$.

**Baut auf:** [[Normalverteilung]] · Ableitungen
**Wird gebraucht für:** [[Gaußsche Fehlerfortpflanzung]] · [[Fadenpendel - Bestimmung von g]]
