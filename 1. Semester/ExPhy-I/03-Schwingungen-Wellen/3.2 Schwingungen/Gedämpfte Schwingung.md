---
modul: ExPhy I
fach: Physik
part: "Kap. 3.2.3"
keywords: damped oscillation, critical damping, logarithmic decrement, creep case
---

# Gedämpfte Schwingung

#exphy1 #oscillations-waves #oscillation #atomic

Reibung $\propto\dot x$: $m\ddot x+r\dot x+Kx=0$. Ansatz $x=ae^{i\omega t}$ ⇒ $\omega=i\gamma\pm\sqrt{\omega_0^2-\gamma^2}$; der Imaginärteil $i\gamma$ erzeugt $e^{-\gamma t}$ (die Folie schreibt $\beta$ statt $\gamma$).

| Fall | Bedingung | Verhalten |
|---|---|---|
| Schwingfall | $\gamma<\omega_0$ | gedämpfte Schwingung, $\omega_d=\sqrt{\omega_0^2-\gamma^2}<\omega_0$ |
| aperiodischer Grenzfall | $\gamma=\omega_0$ | schnellste Rückkehr **ohne** Überschwingen |
| Kriechfall | $\gamma>\omega_0$ | zwei abfallende Exponentialfunktionen $e^{-(\gamma\mp\alpha)t}$, $\alpha=\sqrt{\gamma^2-\omega_0^2}<\gamma$ |

- **Dämpfungsverstimmung:** $\omega_d<\omega_0$. Einhüllende $\pm x_0e^{-\gamma t}$.
- **Logarithmisches Dekrement:** $A_{n+1}=A_ne^{-\gamma T_d}$, $\Lambda=\ln\frac{A_n}{A_{n+1}}=\gamma T_d$ — direkt aus der Abklingkurve messbar.
- **Grenzfall:** technisch wichtig (Zeigermessgerät, Stoßdämpfer); mathematisch unangenehm: doppelte Nullstelle ⇒ nur eine unabhängige Lösung $e^{-\gamma t}$, die zweite per Variation der Konstanten: $x\propto t\,e^{-\gamma t}$.

> [!tip] Verbindung zur Linearen Algebra
> Die doppelte Nullstelle und die Lösung $t\,e^{-\gamma t}$ entsprechen einem Jordanblock der Größe 2 → [[Jordanblock und Jordansche Normalform]].

**Beispiel:** $\omega_0=10\ \mathrm{s^{-1}}$, $\gamma=6\ \mathrm{s^{-1}}$ ⇒ Schwingfall mit $\omega_d=8\ \mathrm{s^{-1}}$.

**Baut auf:** [[Ungedämpfte Schwingung]]
**Wird gebraucht für:** [[Erzwungene Schwingung und Resonanz]]
