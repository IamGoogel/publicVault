---
modul: Vorkurs Physik
fach: Physik
part: "Thema Differentialgleichungen"
keywords: separation of variables, differential equation
---

# Separation der Variablen

#vorkurs #vorkurs-physik

> [!definition] Separation der Variablen
> Anwendbar auf Gleichungen erster Ordnung, die sich als $y' = g(x)\cdot h(y)$ schreiben lassen, also als Produkt eines reinen $x$-Anteils und eines reinen $y$-Anteils. Ob die Gleichung linear ist, spielt keine Rolle.
> Der Kniff liegt in der Notation: $y'$, $\dot{n}$ und $\frac{dy}{dx}$ meinen dasselbe, doch nur in Bruchform lassen sich die beiden Differentiale getrennt auf verschiedene Seiten bringen.

> [!note] Vorgehen in fünf Schritten
> 1. Ableitung als Bruch notieren: $y'$ wird $\frac{dy}{dx}$, $\dot{n}$ wird $\frac{dn}{dt}$.
> 2. Trennen: mit $dx$ multiplizieren und umstellen, sodass links nur $y$ und $dy$, rechts nur $x$ und $dx$ stehen. Lässt sich das nicht erreichen, ist das Verfahren nicht anwendbar.
> 3. Beide Seiten integrieren, jede nach ihrer Variablen. Eine einzige Konstante $C$ reicht aus.
> 4. Nach $y$ auflösen: Wurzel ziehen, Exponentialfunktion anwenden, Kehrwert bilden.
> 5. Kontrolle: Ergebnis ableiten, einsetzen, vergleichen.
> In Schritt 2 liegt die einzige Fehlerquelle, Schritt 5 findet sie. Für Schritt 4 genügen drei Logarithmusregeln: $\ln a + \ln b = \ln(ab)$, $-\ln a = \ln(1/a)$, $C = \ln e^C$. Die Konstante darf umbenannt werden: Aus $4C$, $-C$ oder $e^C$ wird wieder $C$, weil dieselbe Lösungsschar beschrieben wird.

> [!example]- $y'\,y^3 = x^2$ (nichtlinear)
> Trennen: $\frac{dy}{dx}\,y^3 = x^2$ führt auf $y^3\,dy = x^2\,dx$. Beide Seiten mit der Potenzregel integrieren, dann mit $4$ multiplizieren ($4C$ heißt wieder $C$):
> $$\frac{y^4}{4} = \frac{x^3}{3} + C \;\Rightarrow\; y^4 = \frac{4}{3}x^3 + C \;\Rightarrow\; y(x) = \left(\frac{4}{3}x^3 + C\right)^{1/4}$$
> Erste Ordnung, eine Konstante — das passt zur Abzählregel. Kontrolle an $y^4 = \frac{4}{3}x^3 + C$: Ableiten nach $x$ ergibt links $4y^3y'$, rechts $4x^2$, nach Kürzen $y'y^3 = x^2$. Der Exponentialansatz der [[Schwingungsgleichung]] würde hier scheitern, die Separation nicht.

Siehe auch: [[Exponentielles Wachstum und Zerfall]], [[Lösungsverfahren auswählen]], [[Integrationskonstante]]
