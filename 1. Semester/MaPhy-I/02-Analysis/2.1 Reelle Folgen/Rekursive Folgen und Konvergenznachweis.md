---
modul: MaPhy I
fach: Mathematik
part: "Kap. 2.1, Beispiel"
keywords: recursive sequence, Heron, convergence proof
---

# Rekursive Folgen und Konvergenznachweis

#maphy1 #analysis #sequences #atomic

**Vorgehen.**
1. *Beschränktheit* zeigen (meist [[Beweistechniken|Induktion]]).
2. *Monotonie* zeigen (Vorzeichen von $b_{n+1}-b_n$).
3. [[Monotoniekriterium]] ⇒ Grenzwert $b$ existiert.
4. Grenzwert in die Rekursion einsetzen (benutzt [[Grenzwertsätze für Folgen]]) und nach $b$ auflösen.
5. Lösung auswählen (Schranke schließt falsche Lösung aus).

**Beispiel.** $b_1=3$, $b_{n+1}=\frac{b_n}2+\frac3{b_n}$.
- $b_n>\sqrt6$ (Induktion; AM–GM: $\frac{b_n}2+\frac3{b_n}\ge2\sqrt{\frac32}=\sqrt6$ → [[Ungleichungen und Mittelwerte]]).
- $b_{n+1}-b_n=\frac{6-b_n^2}{2b_n}<0$, also fallend.
- Limes: $b=\frac b2+\frac3b\Rightarrow b^2=6$; wegen $b\ge\sqrt6>0$ folgt $b=\sqrt6$.

> [!warning] Vorab-Existenz
> Die Gleichung für $b$ liefert den Grenzwert nur, *wenn* zuvor die Konvergenz gesichert ist. Ohne Schritt 3 darf man den Limes nicht einsetzen.

**Baut auf:** [[Monotoniekriterium]] · [[Grenzwertsätze für Folgen]]
