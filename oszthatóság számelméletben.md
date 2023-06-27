---
tags: OE/ALKMAT/Szamelm 
aliases: ["ostzhatóság"]
TARGET DECK: 02::Algebra
---

# oszthatóság számelméletben
- $a,b \in R$
	- $R$ = [[integritás tartomány]]
- $a|b$, ha $\exists c \in R$, hogy $b = c*a$

# példa az oszthatóságra

> [!example]+ $R=$ Gauss egészek <br> osztói $1+i|2$,$i+2i|5$
> $1+i|2$, mert $2 = (1+i)(1-i)$
> $i+2i|5$, mert $5 = i+2i(1-2i)$

> [!example]+ $R = \{ a + b*\sqrt{2} | a,b \in \mathbb{Z} \}$ <br> osztói $\sqrt{2}|2$,
> $\sqrt{2}|2$, mert $2 = \sqrt{2}*\sqrt{2}$

> [!example]+ $R = \mathbb{R}[x]$ <br> osztói $x-1|x^2-1$,
> $x-1|x^2-1$, mert $x^2-1 = (x-1)(x+1)$

> [!example]+ $R = \mathbb{C}[x]$ <br> osztói $x-i|x^2+1$,
> $x-i|x^2+1$ mert $x^2+1 = (x-i)(x+i)$

> [!example]+ $R =$Gauss-egészek <br> osztói $i|1$,
> $i|1$ mert $1 = (-i)(+i)$

> [!example]+ $R = \{ a + 2b*i | a,b \in \mathbb{Z} \}$ <br> osztói $2i|-4$,$2|2i$
> $2i|-4$, mert $-4 = 2i*2i$
> $2i \not{|} -4$, mert $2 \ne 2i*(a+2bi)$

