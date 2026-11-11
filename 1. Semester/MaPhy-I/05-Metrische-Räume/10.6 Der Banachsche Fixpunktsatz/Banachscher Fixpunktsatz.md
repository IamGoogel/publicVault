---
modul: MaPhy I
fach: Mathematik
part: "Kap. 10.6"
keywords: Banach fixed point theorem, contraction, error estimate
---

# Banachscher Fixpunktsatz

#maphy1 #metric-spaces #fixed-point #atomic

**Voraussetzungen.** $X$ **vollständig** ([[Vollständigkeit]]), $T:X\to X$ *strikt kontraktiv*: $d(Tx,Ty)\le L\,d(x,y)$ mit $0\le L<1$.

**Theorem.** $T$ hat **genau einen** Fixpunkt $x^*$, und für jedes $x_0$ gilt $T^nx_0\to x^*$.

**Eindeutigkeit.** $d(x,y)=d(Tx,Ty)\le L\,d(x,y)\Rightarrow(1-L)d(x,y)\le0\Rightarrow x=y$.

**Existenz.** $x_n=T^nx_0$; induktiv $d(T^nx,T^ny)\le L^nd(x,y)$ und
$$d(x_{n+k},x_n)\le\bigl(L^{n+k-1}+\dots+L^n\bigr)d(x_1,x_0)\le\frac{L^n}{1-L}\,d(x_1,x_0)\xrightarrow{n\to\infty}0 .$$
⇒ $(x_n)$ Cauchy ⇒ $x_n\to x^*$; $T$ ist stetig (Lipschitz) und $d(Tx_n,x_n)\le L^nd(x_1,x_0)\to0$ ⇒ $Tx^*=x^*$.

> [!important] A-priori-Fehlerabschätzung
> $d(x_n,x^*)\le\dfrac{L^n}{1-L}\,d(Tx_0,x_0)$ — Iterationsverfahren mit kontrollierter Genauigkeit.

**Satz.** Ist $T^n$ kontraktiv für ein $n$, hat $T$ genau einen Fixpunkt. (Fixpunkt $x^*$ von $T^n$; $T^n(Tx^*)=T(T^nx^*)=Tx^*$ ⇒ $Tx^*=x^*$ wegen Eindeutigkeit.)

> [!warning] Beide Voraussetzungen nötig
> - Ohne Vollständigkeit: $X=(0,1]$, $T(x)=x/2$ hat keinen Fixpunkt in $X$.
> - Mit $L=1$: $x\mapsto x+1$ auf $\mathbb R$ hat keinen.

**Baut auf:** [[Vollständigkeit]] · [[Stetigkeit in metrischen Räumen]] · [[Hinreichend und notwendig]]
**Anwendung:** [[Anwendung des Banachschen Fixpunktsatzes]]
