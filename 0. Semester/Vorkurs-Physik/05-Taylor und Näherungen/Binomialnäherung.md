---
modul: Vorkurs Physik
fach: Physik
part: "Thema Taylor und Näherungen"
keywords: binomial approximation, Taylor expansion
---

# Binomialnäherung

#vorkurs #vorkurs-physik

> [!satz] Binomialnäherung
> Sie ist der Sonderfall der [[Lineare Näherung|linearen Näherung]] bei $x=0$: $(1+x)^n \approx 1 + n x$ für beliebiges $n$, darunter $n = \frac{1}{2}$ und $n = -1$:
> $$\sqrt{1+x} \approx 1 + \frac{x}{2}, \qquad \frac{1}{1+x} \approx 1 - x$$

> [!example]- Schwerebeschleunigung in der Höhe $h$
> Exakt gilt $g(h) = g_0 \frac{R^2}{(R+h)^2} = g_0\,(1 + h/R)^{-2}$ mit $R \approx 6371\,\mathrm{km}$. Setzt man $n = -2$ und $x = h/R$, erhält man
> $$g(h) \approx g_0\left(1 - \frac{2h}{R}\right)$$
> $g$ nimmt also näherungsweise linear mit der Höhe ab. Kontrollen: $h/R$ hat keine Einheit; bei $h = 0$ ergibt sich $g_0$; bei sehr großem $h$ würde die Formel negativ, sie taugt also nur für $h \ll R$; für $h = 10\,\mathrm{km}$ ist $2h/R = 0{,}00314$, die Abnahme beträgt demnach $0{,}31\,\%$.

Siehe auch: [[Lineare Näherung]], [[Gültigkeitsbereich einer Näherung]]
