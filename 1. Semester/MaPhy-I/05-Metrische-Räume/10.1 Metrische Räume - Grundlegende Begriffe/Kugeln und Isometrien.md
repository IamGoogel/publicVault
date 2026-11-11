---
modul: MaPhy I
fach: Mathematik
part: "Kap. 10.1"
keywords: open ball, closed ball, isometry
---

# Kugeln und Isometrien

#maphy1 #metric-spaces #metric-basics #atomic

- *Offene Kugel* $B(\bar x,r)=\{x\mid d(x,\bar x)<r\}$, *abgeschlossene Kugel* $\bar B(\bar x,r)=\{x\mid d(x,\bar x)\le r\}$.
- *Isometrie*: bijektive Abbildung mit $d(x,y)=d'(f(x),f(y))$. Isometrische Räume sind als metrische Räume ununterscheidbar; die Umkehrung einer Isometrie ist eine Isometrie.

> [!warning] Offen ≠ abgeschlossen
> In der diskreten Metrik ist $B(x,1)=\{x\}$, aber $\bar B(x,1)=X$.

> [!example] Beispiel
> $X=(-\frac\pi2,\frac\pi2)$ mit Standardmetrik und $X'=\mathbb R$ mit $d'(x',y')=\lvert\arctan x'-\arctan y'\rvert$: $f=\tan$ ist eine Isometrie.

**Baut auf:** [[Metriken und Normen]]
**Wird gebraucht für:** [[Offene und abgeschlossene Mengen in metrischen Räumen]] · [[Beschränkte Folgen und Cauchyfolgen in metrischen Räumen]]
