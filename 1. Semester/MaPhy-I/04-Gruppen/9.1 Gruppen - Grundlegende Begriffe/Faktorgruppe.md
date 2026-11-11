---
modul: MaPhy I
fach: Mathematik
part: "Kap. 9.1"
keywords: quotient group, well-defined
---

# Faktorgruppe

#maphy1 #groups #homomorphism #atomic

Für einen Normalteiler $N\trianglelefteq G$ ist $G/N$ = Menge der Nebenklassen mit
$$(gN)(hN)=(gh)N .$$

> [!important] Wohldefiniertheit
> Die Verknüpfung hängt nicht vom Vertreter ab, **weil** $N$ Normalteiler ist: Für $g'=gn$, $h'=hm$ ($n,m\in N$) gilt
> $(gh)^{-1}g'h'=h^{-1}g^{-1}gnhm=(h^{-1}nh)\,m\in N .$
> Ohne Normalteiler-Eigenschaft bricht das ab: $h^{-1}nh$ liegt dann nicht in $N$.

Die Abbildung $G\to G/N$, $g\mapsto gN$ (*kanonischer Homomorphismus*) ist surjektiv mit Kern $N$.

**Beispiele.** $\mathbb Z/n\mathbb Z\cong\mathbb Z_n$ · $S_n/A_n\cong\mathbb Z_2$ · $GL(n,K)/SL(n,K)\cong K^\times$.

**Baut auf:** [[Untergruppe und Normalteiler]] · [[Nebenklassen und Index]]
**Wird gebraucht für:** [[Kern, Normalteiler und Homomorphiesatz]]
