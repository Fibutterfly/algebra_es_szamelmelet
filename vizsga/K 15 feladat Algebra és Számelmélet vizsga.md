---
tags: OE/ALKMAT/Szamelm 
aliases: []
TARGET DECK: 02::Algebra
---
A következő struktúrák közül melyek csoportok?
(a) {páros számok}, $+$ ; 
Félcsoport, igen asszociatív
Monoid, ha 0 benne van az a neutrális elem
csoport, ha benne vannak a negatív számok is

(b) {páratlan számok}, $\cdot$ ; 
Nem félcsoport, mert páratlan + páratlan = páros

(c) $n × n$ mátrixok, $+$ ; 
Félcsoport mindenképpen
Monoid, 0 mátrix
csoport, $*-1$, mint inverz elem

(d) n × n mátrixok, $·$ ;
Félcsoport: nem biztos, hogy asszociatív, $det(A)=0$ esetén biztosan nem
monoid: egység mátrix
csoport: inverz mátrixnak illik léteznie

(e) { $1$ abszolút értékű komplex számok}, $·$ ; 

Az abszolút értékű komplex számok halmaza, jelöljük $\mathbb{C}^*$-al, nem alkot csoportot a szorzás műveletére nézve.

Először is, vegyük figyelembe az abszolút érték definícióját:

Az $z \in \mathbb{C}^*$ abszolút értéke, jelölje $|z|$, a következőképpen definiálható:

$$ |z| = \sqrt{\mathrm{Re}(z)^2 + \mathrm{Im}(z)^2} $$

Az abszolút érték tulajdonságai között szerepel, hogy $|z| = 0$ akkor és csak akkor, ha $z = 0$.

Most tekintsük a szorzás műveletét az $\mathbb{C}^*$ halmazon. Vegyünk két elemet, $z_1$-et és $z_2$-t. Ha mindkét szám abszolút értéke nem nulla ($|z_1| \neq 0$ és $|z_2| \neq 0$), akkor a szorzás eredménye nem nulla ($|z_1 \cdot z_2| \neq 0$), mert az abszolút érték nulla csak akkor lehet, ha az adott szám maga is nulla. Tehát a szorzás műveletére nézve az $\mathbb{C}^*$ halmaz nem zárt, vagyis nem alkot csoportot.

Következésképpen az abszolút értékű komplex számok nem alkotnak csoportot a szorzás műveletére nézve.

(f ) $\mathbb{R}^+, +$.
félcsoport: igen az
monoid, 0 miatt
csoport: nem csoport, mert nincs inverz elem

# kártyák
START
Basic
Front:
Ez egy csoport? 
{páros számok}, $+$ ; 
Back:
Félcsoport, igen asszociatív
Monoid, ha 0 benne van az a neutrális elem
csoport, ha benne vannak a negatív számok is
<!--ID: 1687527912593-->
END

START
Basic
Front:
csoport?
{páratlan számok}, $\cdot$ ; 
Back:
Nem félcsoport, mert páratlan + páratlan = páros
<!--ID: 1687527912601-->
END

START
Basic
Front:
csoport?
$n × n$ mátrixok, $+$ ;
Back:
Félcsoport mindenképpen
Monoid, 0 mátrix
csoport, $*-1$, mint inverz elem
<!--ID: 1687527912606-->
END

START
Basic
Front:
csoport?
n × n mátrixok, $·$ ;
Back:
Félcsoport: nem biztos, hogy asszociatív, $det(A)=0$ esetén biztosan nem
monoid: egység mátrix
csoport: inverz mátrixnak illik léteznie
<!--ID: 1687527912612-->
END

START
Basic
Front:
{ $1$ abszolút értékű komplex számok}, $·$ ;  csoportot alkotnak?
Back:
Az abszolút értékű komplex számok halmaza, jelöljük $\mathbb{C}^*$-al, nem alkot csoportot a szorzás műveletére nézve.

Először is, vegyük figyelembe az abszolút érték definícióját:

Az $z \in \mathbb{C}^*$ abszolút értéke, jelölje $|z|$, a következőképpen definiálható:

$$ |z| = \sqrt{\mathrm{Re}(z)^2 + \mathrm{Im}(z)^2} $$

Az abszolút érték tulajdonságai között szerepel, hogy $|z| = 0$ akkor és csak akkor, ha $z = 0$.

Most tekintsük a szorzás műveletét az $\mathbb{C}^*$ halmazon. Vegyünk két elemet, $z_1$-et és $z_2$-t. Ha mindkét szám abszolút értéke nem nulla ($|z_1| \neq 0$ és $|z_2| \neq 0$), akkor a szorzás eredménye nem nulla ($|z_1 \cdot z_2| \neq 0$), mert az abszolút érték nulla csak akkor lehet, ha az adott szám maga is nulla. Tehát a szorzás műveletére nézve az $\mathbb{C}^*$ halmaz nem zárt, vagyis nem alkot csoportot.

Következésképpen az abszolút értékű komplex számok nem alkotnak csoportot a szorzás műveletére nézve.
<!--ID: 1687527912617-->
END

START
Basic
Front:
$\mathbb{R}^+, +$. csoport?
Back:
félcsoport: igen az
monoid, 0 miatt
csoport: nem csoport, mert nincs inverz elem
<!--ID: 1687527912623-->
END