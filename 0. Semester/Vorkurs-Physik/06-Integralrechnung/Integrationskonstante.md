---
modul: Vorkurs Physik
fach: Physik
part: "Thema Integralrechnung"
keywords: constant of integration, indefinite integral
---

# Integrationskonstante

#vorkurs #vorkurs-physik

> [!definition] Integrationskonstante und Anfangsbedingung
> Bei jeder Integration entsteht eine Konstante, die durch eine Zusatzinformation festgelegt wird. Dazu setzt man den Wert der Variablen ein, für den man etwas weiß — meist $t = 0$. Alle Terme mit $t$ verschwinden dann, und es bleiben etwa $h(0) = h_0$ und $v(0) = v_0$: Starthöhe und Startgeschwindigkeit.

> [!example]- Freier Fall: zweimal integrieren
> Gegeben: $a(t) = g = \dot{v}(t) = \ddot{h}(t)$; gesucht: $h$. In jedem Schritt trennt man die Differentiale und integriert beide Seiten:
> $$\frac{dv}{dt} = g \;\Rightarrow\; dv = g\,dt \;\Rightarrow\; \int dv = \int g\,dt \;\Rightarrow\; v(t) = g\,t + v_0$$
> Mit $v = \dot{h}$ liefert derselbe Ablauf
> $$h(t) = \tfrac{1}{2}\,g\,t^2 + v_0\,t + h_0$$
> Kontrolle: Zweimaliges Ableiten ergibt wieder $\ddot{h} = g$.
> Das Umstellen der Differentiale wie Faktoren ist eine Eselsbrücke, keine echte Bruchrechnung. Das Verfahren heißt Separation der Variablen, siehe [[Separation der Variablen]].

Siehe auch: [[Stammfunktion]], [[Allgemeine und spezielle Lösung]], [[Zweite Ableitung]], [[Differentialgleichung durch Integration]], [[Potential aus Kraftfeld bestimmen]]
