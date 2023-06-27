---
tags: OE/ALKMAT/Szamelm 
aliases: []
TARGET DECK: 02::Algebra
---

# faktorgyűrű def
- jele: $R/I=\{a + I | a \in R \}$
- $+$-ra [[faktor csoport]]
- $+$ művelet: $(a + I)+(b+I)= (a+b)+I$
- $\cdot$ művelet: $(a+I) \cdot (b + I)=ab +I$

# példa

> [!example]+ miért faktorgyűrű az $I = \{$ páros számok $\}$ a <br> $R = \mathbb{Z}$-n?
> $0 + I = I$
> $1+I = \{$ páratlan számot $\}$
> $R/I=\{ 0+I, 1+I \}$
> ![[Pasted image 20230626122040.png]]
> ![[Pasted image 20230626122050.png]]

> [!example]+ miért lesz faktorgyűrű a <br> $I = \{m$-mel osztható egész számok$\}$, $m > 1$ <br> $R = \mathbb{Z}$-n ?
> - [[ideál]], mert 
> 	- $\ne \emptyset$
> 	- $km-lm=(k-l)m$
> 	- z(km)=(zk)m
> - faktorgyűrű, mert
> 	- $R/I=\left\{ \begin{align}  0+I, 1+I,\\ 2+I, \dots (m-1)+I  \end{align} \right\}$ lényegében $\mod m$
> 	- erre jó a $+, \cdot$ művelet

> [!example]+ mi lesz az $\mathbb{R}[x]/I$ <br> $I=\{ f(x) | f(2)=0 \}$?
> ![[Pasted image 20230626131111.png]]

> [!example]+ miért faktorgyűrű a $R=\mathbb{R}[x]$ <br> $I=\{(x^2+1)$-gyel osztható polinomok $\}=\{ (x^2+1)f(x)|f(x)\in  \mathbb{R}[x] \}$
> - [[ideál]], mert
> 	$$\begin{align}\left.\begin{aligned}
> 	(x^2+1)f(x) \\
> 	(x^2+1)g(x)
> 	\end{aligned}\right\} = (x^2+1)(f(x)-g(x)) \\\in I\end{align}$$
> 	$$x^2+1 \in I$$
> 	$(x^2+1)(f(x)*p(x)) \in I$
> - $\mathbb{R}[x]/I = \{ (c+dx)+I | c,d \in \mathbb{R} \}$
> 	- mellékosztályok reprezentánsai $c+dx$
> 	- ![[Pasted image 20230626132230.png]]
> 	- sokadfokúból letudom szedni a kisebbeket
> 	- ![[Pasted image 20230626132340.png]]
> 	- ![[Pasted image 20230626132457.png]]



# kártyák
START
Basic
Front:
faktorgyűrű def
Back:
- jele: $R/I=\{a + I | a \in R \}$
- $+$-ra [[faktor csoport]]
- $+$ művelet: $(a + I)+(b+I)= (a+b)+I$
- $\cdot$ művelet: $(a+I) \cdot (b + I)=ab +I$
<!--ID: 1687781134431-->
END

START
Basic
Front:
miért faktorgyűrű az $I = \{$ páros számok $\}$ a <br> $R = \mathbb{Z}$-n?
Back:
$0 + I = I$
$1+I = \{$ páratlan számot $\}$
$R/I=\{ 0+I, 1+I \}$
![[Pasted image 20230626122040.png]]
![[Pasted image 20230626122050.png]]
<!--ID: 1687781134437-->
END

START
Basic
Front:
miért lesz faktorgyűrű a <br> $I = \{m$-mel osztható egész számok$\}$, $m > 1$ <br> $R = \mathbb{Z}$-n ?
Back:
- [[ideál]], mert 
	- $\ne \emptyset$
	- $km-lm=(k-l)m$
	- z(km)=(zk)m
- faktorgyűrű, mert
	- $R/I=\left\{ \begin{align}  0+I, 1+I,\\ 2+I, \dots (m-1)+I  \end{align} \right\}$ lényegében $\mod m$
	- erre jó a $+, \cdot$ művelet
<!--ID: 1687781134443-->
END

START
Basic
Front:
mi lesz az $\mathbb{R}[x]/I$ <br> $I=\{ f(x) | f(2)=0 \}$?
Back:
![[Pasted image 20230626131111.png]]
<!--ID: 1687781134448-->
END

START
Basic
Front:
miért faktorgyűrű a $R=\mathbb{R}[x]$ <br> $I=\{(x^2+1)$-gyel osztható polinomok $\}=\{ (x^2+1)f(x)|f(x)\in  \mathbb{R}[x] \}$
Back:
- [[ideál]], mert
 	$$\begin{align}\left.\begin{aligned}
 	(x^2+1)f(x) \\
 	(x^2+1)g(x)
 	\end{aligned}\right\} = (x^2+1)(f(x)-g(x)) \\\in I\end{align}$$
	$$x^2+1 \in I$$
	$(x^2+1)(f(x)*p(x)) \in I$
- $\mathbb{R}[x]/I = \{ (c+dx)+I | c,d \in \mathbb{R} \}$
	- mellékosztályok reprezentánsai $c+dx$
	- ![[Pasted image 20230626132230.png]]
	- sokadfokúból letudom szedni a kisebbeket
	- ![[Pasted image 20230626132340.png]]
	- ![[Pasted image 20230626132457.png]]
<!--ID: 1687781134454-->
END