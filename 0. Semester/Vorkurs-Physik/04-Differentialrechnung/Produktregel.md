---
modul: Vorkurs Physik
fach: Physik
part: "Thema Differentialrechnung"
keywords: product rule, derivative
---

# Produktregel

#vorkurs #vorkurs-physik

> [!satz] Produktregel
> $$(u\,v)' = u'\,v + u\,v'$$

> [!example]- $f(x) = x^2 e^{-x}$
> 1. Zwei Faktoren hängen von $x$ ab: $u = x^2$, $v = e^{-x}$.
> 2. Jeder Faktor für sich: $u' = 2x$ nach der Potenzregel, $v' = -e^{-x}$ nach der Kettenregel mit $g(x) = -x$.
> 3. In die Produktregel einsetzen:
> $$f'(x) = 2x\,e^{-x} + x^2\,(-e^{-x}) = (2x - x^2)\,e^{-x} = x\,(2-x)\,e^{-x}$$
> 4. Plausibilität: Da $e^{-x}$ stets positiv ist, entscheidet nur $x(2-x)$ über das Vorzeichen von $f'$ — positiv für $0<x<2$, danach negativ. Das passt zum Graphen, der bei null beginnt, ansteigt und wieder gegen null abfällt.

Siehe auch: [[Ableitungsregeln]], [[Kettenregel]], [[Quotientenregel]], [[Partielle Integration]], [[Geschwindigkeit in Zylinderkoordinaten]]
