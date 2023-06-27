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

> [!example]+ $C_\infty \to C_{20}$  <br> milyen leképezés ez?
> ![[Pasted image 20230624232810.png]]
> ![[Pasted image 20230624232818.png]]
> ![[Pasted image 20230624232909.png]]
> ![[Pasted image 20230624233026.png]]

> [!example]+ $G = GL_n(q)$  <br> $H=\mathbb{F}_q$ <br>  milyen leképezés ez?
> ![[Pasted image 20230624233245.png]]
# homomorfizmus képe
$$Im(\phi) = R_\phi = \{ \phi(x) | x \in G \}$$

# Homomorfizmus magja
$$Ker(\phi) =\{ \phi(x) = 1_H \}$$
$$\begin{align}\phi^{-1}(h) = \{ x \in G | G(x) = h\}=\\=Ker(\phi)\text{ egy mellékosztálya}\end{align}$$

# homomorfizmus tétel
$$\phi: G \to H$$
$$G/Ker(\phi) \cong Im(\phi)$$
## homomorfizmus tételének bizonyítása
![[Pasted image 20230624233632.png]]
![[Pasted image 20230624233835.png]]
![[Pasted image 20230624234325.png]]

# példák a homomorfizmus tételhez
> [!example]+ $C_6 \to C_4$ <br> homomorfizmus-tétel bemutatása
> ![[Pasted image 20230624234601.png]]
> ![[Pasted image 20230624234645.png]]

> [!example]+ $D_4 \to S_2$ <br> homomorfizmus-tétel bemutatása
> ![[Pasted image 20230624235118.png]]
> ![[Pasted image 20230624235130.png]]
> ![[Pasted image 20230624235213.png]]

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
<!--ID: 1687626005462-->
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
<!--ID: 1687626005470-->
END

START
Basic
Front:
homomorfizmus tételének második része
Back:
$x \in G$
$y = \phi(x)$
$r = o(y)|o(x)$
<!--ID: 1687644395786-->
END


START
Basic
Front:
homomorfizmus tételének második részének bizonyítása
Back:
![[Pasted image 20230624173953.png]]
<!--ID: 1687644395794-->
END


START
Basic
Front:
$D_3 \to S_3$ definiáld a leképezést <br> milyen leképezés ez?  
Back:
![[Pasted image 20230624171759.png]]
![[Pasted image 20230624171806.png]]
![[Pasted image 20230624171812.png]]
![[Pasted image 20230624171819.png]]
<!--ID: 1687644395800-->
END

START
Basic
Front:
$D_n \to S_n$ <br> milyen leképezés ez?
Back:
![[Pasted image 20230624172659.png]]
Monomorfizmus, mert az egység képe csak az egység $n>3$ esetén
![[Pasted image 20230624172816.png]]
<!--ID: 1687644395806-->
END

START
Basic
Front:
$C_6 \to C_2$ <br> milyen leképezés ez?
Back:
![[Pasted image 20230624173259.png]]
![[Pasted image 20230624173437.png]]
![[Pasted image 20230624173308.png]]
![[Pasted image 20230624173330.png]]
![[Pasted image 20230624173336.png]]
Epimorfizmus, mert
![[Pasted image 20230624173400.png]]
<!--ID: 1687644395811-->
END

START
Basic
Front:
$C_7 \to C_2$ <br> milyen leképezés ez?
Back:
![[Pasted image 20230624173529.png]]
![[Pasted image 20230624173535.png]]
![[Pasted image 20230624173549.png]]
![[Pasted image 20230624173611.png]]
semmilyen, mert ellent mond a második tételnek
<!--ID: 1687644395816-->
END

START
Basic
Front:
$C_6 \to C_4$ <br> milyen leképezés ez?
Back:
![[Pasted image 20230624174051.png]]
![[Pasted image 20230624174156.png]]
![[Pasted image 20230624174305.png]]
![[Pasted image 20230624174312.png]]
<!--ID: 1687644395821-->
END

START
Basic
Front:
$C_\infty \to C_{20}$  <br> milyen leképezés ez?
Back:
![[Pasted image 20230624232810.png]]
![[Pasted image 20230624232818.png]]
![[Pasted image 20230624232909.png]]
![[Pasted image 20230624233026.png]]
<!--ID: 1687644395826-->
END

START
Basic
Front:
$G = GL_n(q)$  <br> $H=\mathbb{F}_q$ <br>  milyen leképezés ez?
Back:
![[Pasted image 20230624233245.png]]
<!--ID: 1687644395831-->
END

START
Basic
Front:
homomorfizmus képe
Back:
$$Im(\phi) = R_\phi = \{ \phi(x) | x \in G \}$$
<!--ID: 1687644395836-->
END

START
Basic
Front:
Homomorfizmus magja
Back:
$$Ker(\phi) =\{ \phi(x) = 1_H \}$$
$$\begin{align}\phi^{-1}(h) = \{ x \in G | G(x) = h\}=\\=Ker(\phi)\text{ egy mellékosztálya}\end{align}$$
<!--ID: 1687644395842-->
END

START
Basic
Front:
homomorfizmus tétel
Back:
$$\phi: G \to H$$
$$G/Ker(\phi) \cong Im(\phi)$$
<!--ID: 1687644395847-->
END

START
Basic
Front:
homomorfizmus tételének bizonyítása
Back:
![[Pasted image 20230624233632.png]]
![[Pasted image 20230624233835.png]]
![[Pasted image 20230624234325.png]]
<!--ID: 1687644395852-->
END

START
Basic
Front:
$C_6 \to C_4$ <br> homomorfizmus-tétel bemutatása
![[Pasted image 20230624234601.png]]
![[Pasted image 20230624234645.png]]
<!--ID: 1687644395857-->
END

START
Basic
Front:
$D_4 \to S_2$ <br> homomorfizmus-tétel bemutatása
Back:
![[Pasted image 20230624235118.png]]
![[Pasted image 20230624235130.png]]
![[Pasted image 20230624235213.png]]
<!--ID: 1687644395862-->
END