---
tags: OE/ALKMAT/Szamelm 
aliases: []
TARGET DECK: 02::Algebra
---
Legyen $\ell$ baloldali egységelem $A$-ban. Az $a ∈ A$ elem balinverzének nevezzük az $\overline{a}_\ell$ -t, ha $\overline{a}_\ell *a = \ell$  teljesül. Tegyük fel, hogy minden $a ∈ A$ rendelkezik balinverzzel. Bizonyítsuk be, hogy $A$ [[csoport]].

- fél [[csoport]], mert
$\overline{b}_\ell * (b * \overline{a}_\ell) * a = (\overline{b}_\ell * b) * (\overline{a}_\ell * a) = \ell * \ell = \ell$

Tehát az $(\overline{b}_\ell * b) * (\overline{a}_\ell * a)$ is $\ell$-el egyenlő, vagyis a művelet zárt.
- monoid, mert
Az állítás szerint minden $a \in A$-nak van balinverze, tehát válasszunk egy tetszőleges elemet $a \in A$-ból, és jelöljük annak balinverzét $\overline{a}_\ell$-el. Az előző pontban láttuk, hogy $\overline{a}_\ell * a = \ell$ minden $a \in A$-ra. Tehát $\ell$ az egységelem, mert minden elemre megfelelően működik.

- [[csoport]], mert
Az állítás szerint minden $a \in A$-nak van balinverze, tehát minden $a \in A$-ra létezik $\overline{a}_\ell$, amelyre $\overline{a}_\ell * a = \ell$. Tehát minden elemnek van balinverze.

START
Basic
Front:
Legyen $\ell$ baloldali egységelem $A$-ban. Az $a ∈ A$ elem balinverzének nevezzük az $\overline{a}_\ell$ -t, ha $\overline{a}_\ell *a = \ell$  teljesül. Tegyük fel, hogy minden $a ∈ A$ rendelkezik balinverzzel. Bizonyítsuk be, hogy $A$ félcsoport
Back:
$\overline{b}_\ell * (b * \overline{a}_\ell) * a = (\overline{b}_\ell * b) * (\overline{a}_\ell * a) = \ell * \ell = \ell$

Tehát az $(\overline{b}_\ell * b) * (\overline{a}_\ell * a)$ is $\ell$-el egyenlő, vagyis a művelet zárt.
<!--ID: 1687373904196-->
END

START
Basic
Front:
Legyen $\ell$ baloldali egységelem $A$-ban. Az $a ∈ A$ elem balinverzének nevezzük az $\overline{a}_\ell$ -t, ha $\overline{a}_\ell *a = \ell$  teljesül. Tegyük fel, hogy minden $a ∈ A$ rendelkezik balinverzzel. Bizonyítsuk be, hogy $A$ monoid, ha tudjuk, hogy a művelet asszociatív (tehát félcsoport)
Back:
Az állítás szerint minden $a \in A$-nak van balinverze, tehát válasszunk egy tetszőleges elemet $a \in A$-ból, és jelöljük annak balinverzét $\overline{a}_\ell$-el. Az előző pontban láttuk, hogy $\overline{a}_\ell * a = \ell$ minden $a \in A$-ra. Tehát $\ell$ az egységelem, mert minden elemre megfelelően működik.
<!--ID: 1687373904205-->
END

START
Basic
Front:
Legyen $\ell$ baloldali egységelem $A$-ban. Az $a ∈ A$ elem balinverzének nevezzük az $\overline{a}_\ell$ -t, ha $\overline{a}_\ell *a = \ell$  teljesül. Tegyük fel, hogy minden $a ∈ A$ rendelkezik balinverzzel. Bizonyítsuk be, hogy $A$ [[csoport]], ha tudjuk, hogy monoid
Back:
Az állítás szerint minden $a \in A$-nak van balinverze, tehát minden $a \in A$-ra létezik $\overline{a}_\ell$, amelyre $\overline{a}_\ell * a = \ell$. Tehát minden elemnek van balinverze.
<!--ID: 1687373904212-->
END