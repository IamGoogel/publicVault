---
modul: MaPhy I
fach: Mathematik
part: "Kap. 10.6.2"
keywords: Banach application, functional equation, Fredholm
---

# Anwendung des Banachschen Fixpunktsatzes

#maphy1 #metric-spaces #fixed-point #atomic

**Beispiel.** Gesucht ist genau eine stetige $f:[0,1]\to\mathbb R$ mit $f(x)=x+\tfrac12\sin f(x)$.

**Lösung.** $Tf(x)=x+\tfrac12\sin f(x)$ auf dem vollständigen Raum $C([0,1];\mathbb R)$ ([[Vollständigkeit]]). Mit $\lvert\sin a-\sin b\rvert\le\lvert a-b\rvert$:
$$\lvert Tf(x)-Tg(x)\rvert\le\tfrac12\lvert f(x)-g(x)\rvert\ \Rightarrow\ d(Tf,Tg)\le\tfrac12d(f,g),\quad L=\tfrac12 .$$
Nach dem [[Banachscher Fixpunktsatz|Banachschen Fixpunktsatz]] gibt es genau einen Fixpunkt.

**Folgerungen.** Auf jedem beschränkten Intervall ⇒ $f\in C(\mathbb R;\mathbb R)$; $f$ ungerade mit $f(0)=0$; $f(x)\sim x$ für $\lvert x\rvert\to\infty$, denn $\bigl\lvert\frac{f(x)}x-1\bigr\rvert=\frac{\lvert\sin f\rvert}{2\lvert x\rvert}\le\frac1{2\lvert x\rvert}$.

Strukturell ähnlich: Fredholmsche Integralgleichung zweiter Art $f(x)=g(x)+\lambda\int_0^1K(x,y)f(y)\,dy$.

**Baut auf:** [[Banachscher Fixpunktsatz]] · [[Metriken und Normen]] (Maximumsnorm)
