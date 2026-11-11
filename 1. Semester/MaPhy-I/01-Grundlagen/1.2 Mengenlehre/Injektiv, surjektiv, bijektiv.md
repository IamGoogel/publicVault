---
modul: MaPhy I
fach: Mathematik
part: "Kap. 1.2.4"
keywords: injective, surjective, bijective
---

# Injektiv, surjektiv, bijektiv

#maphy1 #foundations #mappings #atomic

| Eigenschaft | Definition | Merkregel |
|---|---|---|
| injektiv | $F(x)=F(x')\Rightarrow x=x'$ | jedes $y$ hat **höchstens** ein Urbild |
| surjektiv | $\forall y\in N\,\exists x:F(x)=y$ | jedes $y$ hat **mindestens** ein Urbild |
| bijektiv | injektiv **und** surjektiv | jedes $y$ hat **genau** ein Urbild |

```
injektiv, nicht surj.     surjektiv, nicht inj.     bijektiv
 a ─▶ 1                    a ─▶ 1                    a ─▶ 1
 b ─▶ 2                    b ─┘                      b ─▶ 2
      3 (kein Urbild)      c ─▶ 2                    c ─▶ 3
```

> [!example] Definitionsbereich zählt
> $x\mapsto x^2$ ist auf $\mathbb R_+\to\mathbb R_+$ bijektiv, auf $\mathbb R\to\mathbb R$ aber weder injektiv ($(-1)^2=1^2$) noch surjektiv ($-1$ ohne Urbild).

**Baut auf:** [[Abbildung und Komposition]]
**Wird gebraucht für:** [[Umkehrabbildung]] · [[Mächtigkeit und Abzählbarkeit]] · [[Lineare Abbildung]] (Mono-/Epi-/Isomorphismus)
