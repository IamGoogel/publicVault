---
modul: MaPhy I
fach: Mathematik
part: "Kap. 6.1"
keywords: subspace, span, linear combination
---

# Untervektorraum und Erzeugnis

#maphy1 #linear-algebra #vector-spaces #atomic

**Untervektorraum.** $U\subseteq V$, falls (1) $0\in U$, (2) $u,u'\in U\Rightarrow u+u'\in U$, (3) $\alpha\in K,u\in U\Rightarrow\alpha u\in U$.

Beispiele: Geraden und Ebenen **durch den Ursprung** im $\mathbb R^3$; $C([0,1];\mathbb R)\subseteq\mathbb R^{[0,1]}$.

> [!warning] Ohne Null kein Untervektorraum
> Eine Gerade, die nicht durch den Ursprung geht, verletzt $0\in U$.

- Der Durchschnitt beliebig vieler Untervektorräume ist wieder einer; die **Vereinigung** i. A. nicht.
- **Lemma:** Zu $S\subseteq V$ gibt es einen kleinsten Untervektorraum, der $S$ enthält:
$$\operatorname{span}S=\bigcap\{U\mid S\subseteq U\}=\{\text{endliche Linearkombinationen von Elementen aus }S\}.$$

**Baut auf:** [[Vektorraum]]
**Wird gebraucht für:** [[Linear unabhängig und Basis]] · [[Kern und Bild]]
