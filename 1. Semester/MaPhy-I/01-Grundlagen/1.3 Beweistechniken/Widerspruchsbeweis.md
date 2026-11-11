---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.3"
keywords: proof by contradiction, irrationality of sqrt 2, infinitely many primes
---

# Widerspruchsbeweis

#maphy1 #foundations #proofs #atomic

**Prinzip.** Man nimmt das **Gegenteil** der Behauptung an und leitet einen Widerspruch her. Logische Grundlage: $\neg(A\to B)\iff A\land\neg B$ → [[Logische Äquivalenzen]].

**Satz: $\sqrt2$ ist irrational.** Annahme $\sqrt2=p/q$ ⇒ $2q^2=p^2$. Mit $p=2^ap_0$, $q=2^bq_0$ ($p_0,q_0$ ungerade): $2^{2b+1}q_0^2=2^{2a}p_0^2$. Links ungerader, rechts gerader Exponent von $2$ — Widerspruch zur eindeutigen Primfaktorzerlegung.

**Satz: unendlich viele Primzahlen.** Annahme nur $p_1,\dots,p_\ell$. $n=p_1\cdots p_\ell+1$ hat einen Primteiler $q$; wäre $q=p_j$, so $q\mid n-\prod p_i=1$ — Widerspruch.

> [!tip] Wann einsetzen?
> Bei Aussagen der Form „es gibt keine …“, „ist irrational“, „unendlich viele …“.

**Baut auf:** [[Logische Äquivalenzen]] · [[Negation quantifizierter Aussagen]]
**Wird gebraucht für:** [[Vollständigkeitsaxiom]] (Lücke von $\mathbb Q$)
