---
tags: OE/ALKMAT/Szamelm 
aliases: ["homomorf", "homomorfizmust", "homomorfizmus képe","homomorfizmus képét","homomorfizmus magja","Homomorfizmus magját" ]
TARGET DECK: 02::Algebra
---

# homomorfizmus
Van egy 
$$\phi: G -> H$$
leképezésünk
- tiszteletben tartja a csoportbéli műveleteket 
- $x*y \to \phi(x*y) = \phi(x)*\phi(y)$

# fontos állítások homomorfizmushoz
- $\phi(1_G)=1_H$
- $\phi(x^{-1})= \phi(x)^{-1}$
- $Im(\phi) \le H$
- $Ker(\phi) \triangleleft G$  

# homomorfizmus tételének második része
$x \in G$
$y = \phi(x)$
$r = o(y)|o(x)$

## bizonyítása
![[Pasted image 20230624173953.png]]

# Példák

> [!example]+ $D_3 \to S_3$ definiáld a leképezést <br> milyen leképezés ez?  
> ![[Pasted image 20230624171759.png]]
> ![[Pasted image 20230624171806.png]]
> ![[Pasted image 20230624171812.png]]
> ![[Pasted image 20230624171819.png]]

> [!example]+ $D_n \to S_n$ <br> milyen leképezés ez?
> ![[Pasted image 20230624172659.png]]
> Monomorfizmus, mert az egység képe csak az egység $n>3$ esetén
> ![[Pasted image 20230624172816.png]]

> [!example]+ $C_6 \to C_2$ <br> milyen leképezés ez?
> ![[Pasted image 20230624173259.png]]
> ![[Pasted image 20230624173437.png]]
> ![[Pasted image 20230624173308.png]]
> ![[Pasted image 20230624173330.png]]
> ![[Pasted image 20230624173336.png]]
> Epimorfizmus, mert
> ![[Pasted image 20230624173400.png]]

> [!example]+ $C_7 \to C_2$ <br> milyen leképezés ez?
> ![[Pasted image 20230624173529.png]]
> ![[Pasted image 20230624173535.png]]
> ![[Pasted image 20230624173549.png]]
> ![[Pasted image 20230624173611.png]]
> semmilyen, mert ellent mond a második tételnek

> [!example]+ $C_6 \to C_4$ <br> milyen leképezés ez?
> ![[Pasted image 20230624174051.png]]
> ![[Pasted image 20230624174156.png]]
> ![[Pasted image 20230624174305.png]]
> ![[Pasted image 20230624174312.png]]

> [!example]+ $C_\infty \to C_20$

# homomorfizmus képe
$$Im(\phi) = R_\phi = \{ \phi(x) | x \in G \}$$

# Homomorfizmus magja
$$Ker(\phi) =\{ \phi(x) = 1_H \}$$
$$\begin{align}\phi^{-1}(h) = \{ x \in G | G(x) = h\}=\\=Ker(\phi)\text{ egy mellékosztálya}\end{align}$$



# kártyák
START
Basic
Front:
homomorfizmus definíciója
Back:
Van egy 
$$\phi: G -> H$$
leképezésünk
- tiszteletben tartja a csoportbéli műveleteket 
- $x*y \to \phi(x*y) = \phi(x)*\phi(y)$
<!--ID: 1687614691837-->
END

START
Basic
Front:
Bizonyítsd, hogy $\phi(1_G)=1_H$
ahol $\phi$ homomorfizmust jelöl
Back:
![[Pasted image 20230624155713.png]]
<!--ID: 1687615315135-->
END

START
Basic
Front:
bizonyítsd, hogy
$\phi(x^{-1})= \phi(x)^{-1}$
ahol $\phi$ homomorfizmust jelöl
Back:
![[Pasted image 20230624160119.png]]
<!--ID: 1687615315141-->
END

START
Basic
Front:
Homomorfizmus fontos tulajdonságai
Back:
- $\phi(1_G)=1_H$
- $\phi(x^{-1})= \phi(x)^{-1}$
- $Im(\phi) \le H$
- $Ker(\phi) \triangleleft G$  
<!--ID: 1687615315146-->
END

START
Basic
Front:
bizonyítsd, hogy
$Im(\phi) \le H$
ahol $\phi$ homomorfizmust jelöl
Back:
![[Pasted image 20230624162902.png]]
END

START
Basic
Front:
bizonyítsd, hogy
$Ker(\phi) \triangleleft G$  
ahol $\phi$ homomorfizmust jelöl
Back:
![[Pasted image 20230624163119.png]]
![[Pasted image 20230624163750.png]]
jobbra is igaz ez
END