# Lottószámok

**Feladatleírás:**

A Szerencsejáték Zrt. téged bízott meg az év hátralévő részében az Ötöslottó kezelésével és riportok készítésével. Készítsen egy C# konzolos alkalmazást, amivel elvégzi a cég által specifikált feladatokat. A feladatok előtt írja ki a feladat sorszámát a konzolra. Forrásként használja a sorsolas.csv pontosvesszővel elválasztott fájlt!

1.	Olvassa be a mellékelt forrásfájlt egy tetszőleges adatszerkezetbe! Beolvasáskor ellenőrizze, hogy minden dátum csak egyszer szerepeljen!
2.	Ahhoz, hogy megjósoljuk a húzott számokat generáljon le véletlenszerűen 5 db számot 1-90-ig mindegyik olyan dátumra, amihez nem tartoztak a forrásban! Ellenőrizze, hogy kétszer, ugyanazon a napon ne szereplejen ugyanaz a szám és minden dátumnál különbözőek.
3.	Számolja ki metódus segítségével, hogy összesen hány lottószámot húztak ki összesen az év végéig!
4.	A közjegyző kíváncsi arra, hogy mindegyik labda ugyanolyan kerek-e, még a párosok is! Számolja ki, hogy hány páros és páratlan szám lett kihúzva összesen!
5.	A vezérigazgató szeretné tudni, hogy melyik napon kell a 45 alatti számokra fogadni. Írja ki képernyőre azoknak a napoknak a dátumát, ahol a minimum 3 db 45 alatti szám szerepel! Ha nincs ilyen nap, akkor ezt írja ki!
6.	Készítsen egy kimutatást azokról a kihúzott számokról, amiket egynél többször húztak ki az év során. Írja ki a képernyőre számok szerinti csoportosításban a darabszámot.
7.	A logisztikai osztály beszerzésén elkeveredtek a jövő év naptárak. Addig amíg nem érkeznek meg az újak, segítsen kiszámolni a jövő évi sorsolások dátumát.
Számítsa ki a 2023. évben az első 10 lottósorsolás dátumát! A következő év legelső ötöslottó sorsolása január 2-án lesz, a sorsolások minden héten, szombaton történnek. Ezekhez dátumokhoz ne generáljon nyerőszámokat.
8.	Exportálja a sorsolás eredményeit és a jövő évi sorsolás dátumait egy UTF-8 kódolású állományba lottoszamok.csv néven! A fájlban pontosvesszővel válassza el az adatokat. A jövő évi sorsolások lottószámai helyén egy ’X’ karakter szerepeljen.
