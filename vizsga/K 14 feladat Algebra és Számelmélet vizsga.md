---
tags: OE/ALKMAT/Szamelm 
aliases: []
TARGET DECK: 02::Algebra
---
Legyen $·$ egy asszociatív kétváltozós [[művelet]] a $G$ nem-üres halmazon. Tegyük fel, hogy az $a · x = b$ és az $y · a = b$ egyenletek tetszőleges $a, b ∈ G$ esetén megoldhatók. Bizonyítsuk be, hogy $G$ csoport.

Félcsoport by def
monoid, mert van egységeleme:
Az állítás szerint az $a \cdot x = b$ egyenlet tetszőleges $a, b \in G$ esetén megoldható. Válasszunk egy tetszőleges $a \in G$-t, és jelöljük annak megoldását $e$-vel, azaz $a \cdot e = e \cdot a = a$. Tehát $e$ az egységelem, mert minden elemre megfelelően működik.

És csoport, mert van benne inverz:
Az állítás szerint az $a \cdot x = b$ és $y \cdot a = b$ egyenletek tetszőleges $a, b \in G$ esetén megoldhatók. Tehát minden $a \in G$-ra létezik olyan $x, y \in G$, amelyekre $a \cdot x = b$ és $y \cdot a = b$. Tehát minden elemnek van bal- és jobbinverze.

START
Basic
Front:
Legyen $·$ egy asszociatív kétváltozós [[művelet]] a $G$ nem-üres halmazon. Tegyük fel, hogy az $a · x = b$ és az $y · a = b$ egyenletek tetszőleges $a, b ∈ G$ esetén megoldhatók. Bizonyítsuk be, hogy $G$ félcsoport.
Back:
definíció alapján
<!--ID: 1687374344145-->
END

START
Basic
Front:
Legyen $·$ egy asszociatív kétváltozós [[művelet]] a $G$ nem-üres halmazon. Tegyük fel, hogy az $a · x = b$ és az $y · a = b$ egyenletek tetszőleges $a, b ∈ G$ esetén megoldhatók. Bizonyítsuk be, hogy $G$ monoid, ha tudjuk, hogy félcsoport.
Back:
monoid, mert van egységeleme:
Az állítás szerint az $a \cdot x = b$ egyenlet tetszőleges $a, b \in G$ esetén megoldható. Válasszunk egy tetszőleges $a \in G$-t, és jelöljük annak megoldását $e$-vel, azaz $a \cdot e = e \cdot a = a$. Tehát $e$ az egységelem, mert minden elemre megfelelően működik.
<!--ID: 1687374344151-->
END

START
Basic
Front:
Legyen $·$ egy asszociatív kétváltozós [[művelet]] a $G$ nem-üres halmazon. Tegyük fel, hogy az $a · x = b$ és az $y · a = b$ egyenletek tetszőleges $a, b ∈ G$ esetén megoldhatók. Bizonyítsuk be, hogy $G$ csoport, ha tudjuk, hogy monoid
Back:
És csoport, mert van benne inverz:
Az állítás szerint az $a \cdot x = b$ és $y \cdot a = b$ egyenletek tetszőleges $a, b \in G$ esetén megoldhatók. Tehát minden $a \in G$-ra létezik olyan $x, y \in G$, amelyekre $a \cdot x = b$ és $y \cdot a = b$. Tehát minden elemnek van bal- és jobbinverze.
<!--ID: 1687374344158-->
END