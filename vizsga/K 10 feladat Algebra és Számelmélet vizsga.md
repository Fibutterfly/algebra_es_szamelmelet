---
tags: OE/ALKMAT/Szamelm 
aliases: [""]
TARGET DECK: 02::Algebra
---

Tekintsük a következő kétváltozós [[Művelet|műveleteket]] a megadott halmazokon. Melyek asszociatívak, illetve kommutatívak? Melyeknek van neutrális eleme? Mely halmazokban invertálható minden elem?

(a) $\mathcal{P}(H)$, a $H$ halmaz részhalmazainak halmaza. A [[művelet]] a szimmetrikus differencia $(A \triangle B = (A \backslash B) ∪ (B \backslash A))$;

Asszociatív: igen, mert $(A △ B) △ C = A △ (B △ C)$

Kommutatív, igen, mert: $(B \triangle A = (B \backslash A) ∪ (A \backslash B))$

Neutrális eleme: üres halmaz

Invertálható minden eleme, igen, mert van inverz halmaz

(b) $\mathbb{R}, a ∗ b = ab − ba$;

Asszociatív
$c*(a*b)=c*(ab-ba)=cab -bac -cba-cab$
$(c*a)*b=(ca-ac)*b=cab-bca-acb*bac$
tehát nem az


Kommutatív
$a*b=ab-ba$
$b*a=ba-ab$
tehát az, mert ha belerakok számokat mindig 0 lesz

[[Művelet|Neutrális elem]]
nincs neki

Invertálható minden eleme
nincs neki, mert nincs invertálható eleme

(c) $\mathbb{R}^+ , a ∗ b = a^b$;
Asszociatív
$c*(a*b)=c*a^b=c^{a^b}$
$(c*a)*b=c^a*b=c^{a^b}$
tehát asszociatív

Kommutatív
$a*b=a^b$
$b*a=b^a$
Tehát nem az

[[Művelet|Neutrális elem]], Invertálható minden eleme
csak jobb [[Művelet|neutrális elem]] van (1), nem invertálható minden eleme

(d) $\mathbb{R}, a ∗ b = a + b + 1$;
Asszociatív
$(a * b) * c = (a + b + 1) * c =$ 
$(a + b + 1) + c + 1 = a + b + c + 2$.

$a * (b * c) = a * (b + c + 1) =$
$a + (b + c + 1) + 1 = a + b + c + 2$.
asszociatív

Kommutatív
$a*b=a+b+1$
$b*a=b+a+1$
tehát kommutatív

[[Művelet|Neutrális elem]], Invertálható minden eleme
neutrális elem cél: 
$n*a=a$ és $a*n=a$
$a+n+1=a$ és $n+a+1=a$
neutrális elem -> $-a-1$
inverz elem:
$-2-2a$


(e) $\{1, 3, 5, 7\}, a ∗ b = ab \mod 8$.
Asszociatív
$c*(a*b)=c*(ab \mod 8) = c(ab \mod 8) \mod 8$
$(c*a)*b=(ca \mod 8)*b= (ca \mod 8)b \mod 8$
tehát nem az

Kommutatív
$a*b=ab \mod 8$
$b*a= ba \mod 8$
tehát az

[[Művelet|Neutrális elem]], Invertálható minden eleme
$1$ a [[Művelet|neutrális elem]]
Minden elemnek van inverze a műveletben. Az $a$ elem inverze az a szám, amelyet szorozva az $a$-val, az eredmény 1 modulo 8. Ezt az inverzet jelöljük $a^{-1}$-el.

START
Basic
Front:
a szimmetrikus differencia $(A \triangle B = (A \backslash B) ∪ (B \backslash A))$
asszociatív?
Back:
Igen, mert $(A △ B) △ C = A △ (B △ C)$
<!--ID: 1687300332856-->
END

START
Basic
Front:
a szimmetrikus differencia $(A \triangle B = (A \backslash B) ∪ (B \backslash A))$
kommutatív?
Back:
igen, mert: $(B \triangle A = (B \backslash A) ∪ (A \backslash B))$
<!--ID: 1687300332864-->
END

START
Basic
Front:
a szimmetrikus differencia $(A \triangle B = (A \backslash B) ∪ (B \backslash A))$
neutrális eleme?
Back:
Az üres halmaz
<!--ID: 1687300332870-->
END

START
Basic
Front:
a szimmetrikus differencia $(A \triangle B = (A \backslash B) ∪ (B \backslash A))$
invertálható minden elem?
Back:
igen, mert van inverz halmaz
<!--ID: 1687300332875-->
END

START
Basic
Front:
$\mathbb{R}, a ∗ b = ab − ba$;
Asszociatív
Back:
$c*(a*b)=c*(ab-ba)=cab -bac -cba-cab$
$(c*a)*b=(ca-ac)*b=cab-bca-acb*bac$
tehát nem az
<!--ID: 1687300332881-->
END

START
Basic
Front:
$\mathbb{R}, a ∗ b = ab − ba$;
Kommutatív
Back:
$a*b=ab-ba$
$b*a=ba-ab$
tehát az, mert ha belerakok számokat mindig 0 lesz
<!--ID: 1687300332886-->
END

START
Basic
Front:
$\mathbb{R}, a ∗ b = ab − ba$;
[[Művelet|Neutrális elem]],
Invertálható minden eleme
Back:
nincs neki
<!--ID: 1687300332891-->
END

START
Basic
Front:
$\mathbb{R}^+ , a ∗ b = a^b$;
Asszociatív
Back:
$c*(a*b)=c*a^b=c^{a^b}$
$(c*a)*b=c^a*b=c^{a^b}$
tehát asszociatív
<!--ID: 1687300332896-->
END

START
Basic
Front:
$\mathbb{R}^+ , a ∗ b = a^b$;
Kommutatív
Back:
$a*b=a^b$
$b*a=b^a$
Tehát nem az
<!--ID: 1687300332901-->
END

START
Basic
Front:
$\mathbb{R}^+ , a ∗ b = a^b$;
[[Művelet|Neutrális elem]], Invertálható minden eleme
Back:
csak jobb [[Művelet|neutrális elem]] van (1), nem invertálható minden eleme
<!--ID: 1687300332906-->
END

START
Basic
Front:
$\mathbb{R}, a ∗ b = a + b + 1$;
Asszociatív
Back:
$(a * b) * c = (a + b + 1) * c =$ 
$(a + b + 1) + c + 1 = a + b + c + 2$.

$a * (b * c) = a * (b + c + 1) =$
$a + (b + c + 1) + 1 = a + b + c + 2$.
asszociatív
<!--ID: 1687300332911-->
END

START
Basic
Front:
$\mathbb{R}, a ∗ b = a + b + 1$;
Kommutatív
Back:
$a*b=a+b+1$
$b*a=b+a+1$
tehát kommutatív
<!--ID: 1687300332916-->
END

START
Basic
Front:
$\mathbb{R}, a ∗ b = a + b + 1$;
[[Művelet|Neutrális elem]], Invertálható minden eleme
Back:
neutrális elem cél: 
$n*a=a$ és $a*n=a$
$a+n+1=a$ és $n+a+1=a$
neutrális elem -> $-a-1$
inverz elem:
$-2-2a$
<!--ID: 1687300332921-->
END

START
Basic
Front:
$\{1, 3, 5, 7\}, a ∗ b = ab \mod 8$.
Asszociatív
Back:
$c*(a*b)=c*(ab \mod 8) = c(ab \mod 8) \mod 8$
$(c*a)*b=(ca \mod 8)*b= (ca \mod 8)b \mod 8$
tehát nem az
<!--ID: 1687370506418-->
END

START
Basic
Front:
$\{1, 3, 5, 7\}, a ∗ b = ab \mod 8$.
Kommutatív
Back:
$a*b=ab \mod 8$
$b*a= ba \mod 8$
tehát az
<!--ID: 1687370506424-->
END

START
Basic
Front:
$\{1, 3, 5, 7\}, a ∗ b = ab \mod 8$.
[[Művelet|Neutrális elem]], Invertálható minden eleme
Back:
$1$ a [[Művelet|neutrális elem]]
Minden elemnek van inverze a műveletben. Az $a$ elem inverze az a szám, amelyet szorozva az $a$-val, az eredmény 1 modulo 8. Ezt az inverzet jelöljük $a^{-1}$-el.
<!--ID: 1687370506430-->
END