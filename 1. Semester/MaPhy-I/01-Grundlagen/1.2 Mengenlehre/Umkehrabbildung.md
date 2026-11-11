---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.2"
keywords: inverse mapping, bijection, identity
---

# Umkehrabbildung

#maphy1 #foundations #mappings #atomic

**Satz.** $F:M\to N$ ist genau dann bijektiv, wenn es $G:N\to M$ gibt mit
$$G\circ F=\mathrm{id}_M\quad\text{und}\quad F\circ G=\mathrm{id}_N .$$
$G$ ist dann **eindeutig**: $G=F^{-1}$.

Beispiel: $f:\mathbb R_+\to\mathbb R_+$, $x\mapsto x^2$ hat $f^{-1}(y)=\sqrt y$.

> [!warning] Beide Gleichungen
> Eine einseitige Inverse genügt für Bijektivität nicht: $G\circ F=\mathrm{id}$ zeigt nur Injektivität von $F$ (bei Matrizen vgl. [[Rang und voller Rang]]).

**Baut auf:** [[Abbildung und Komposition]] · [[Injektiv, surjektiv, bijektiv]]
**Wird gebraucht für:** [[Umkehrfunktion stetiger monotoner Funktionen]] · [[Invertierbare Matrizen]] · [[Lineare Abbildung]]
