---
tags: OE/ALKMAT/Szamelm 
aliases: ["ciklkus csoportot"]
TARGET DECK: 02::Algebra
---
# ciklikus [[csoport]]
- jele: $<\alpha >$
- Onnan vesszük észre, hogy ahogyan mennek hatványban vagy valahogyan a dolgok körbe lesz benne újra egy $1$
- $G=\{ 1, \alpha, \alpha^2, \alpha^3, \dots, \alpha^{m-1}\}, \alpha^m=1$
- szorzás értelmezve rajta: $a^k*a^l = a^{k+l \mod n}$
- inverze: $a^{-k}=a^{n-k}$

# ciklikus csoport rendje
- Neki állunk iterálni annak, hogy mikor kapjuk meg az $1$-et
![[Pasted image 20230622212600.png]]
- VAGY $o(g^s)= \dfrac{n}{lnko(s,n)}$

# kártyák
START
Basic
Front:
ciklikus [[csoport]] def
Back:
- jele: $<\alpha >$
- Onnan vesszük észre, hogy ahogyan mennek hatványban vagy valahogyan a dolgok körbe lesz benne újra egy $1$
- $G=\{ 1, \alpha, \alpha^2, \alpha^3, \dots, \alpha^{m-1}\}, \alpha^m=1$
<!--ID: 1687375263995-->
END

START
Basic
Front:
ciklikus csoport szorzása
Back:
$a^k*a^l = a^{k+l \mod n}$  
<!--ID: 1687375264004-->
END

START
Basic
Front:
ciklikus csoport inverze
Back:
$a^{-k}=a^{n-k}$
<!--ID: 1687375264012-->
END

START
Basic
Front:
ciklikus csoport rendje
Back:
- Neki állunk iterálni annak, hogy mikor kapjuk meg az $1$-et
![[Pasted image 20230622212600.png]]
- VAGY $o(g^s)= \dfrac{n}{lnko(s,n)}$
<!--ID: 1687462716359-->
END