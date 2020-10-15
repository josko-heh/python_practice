### 23.
Napišite program koji za zadani string pronalazi broj podstringova koji se čitaju isto
s lijeva na desno i s desna na lijevo. Na primjer, u stringu istitisak postoje dva takva
podstringa: tit i iti. 

### 24. 
Dva stringa su anagrami ako se od jednog može dobiti drugi premještanjem znakova.
Na primjer, stringovi ”abcb” i ”bcab” su anagrami jer sadrže ista slova, samo u drugačijem redoslijedu, ali ”abcc” i ”abbc” nisu. Napišite funkciju anagram(s1, s2) koja daje True ako su stringovi s1 i s2 anagrami na sljedeće načine:
(a) Sortiranjem
(b) Upotrebom mapa
(c) Upotrebom skupova

### 25.
Implementirajte strukturu podataka sličnu skupu, ali koja dozvoljava duplikate i koja
će se zvati Multiset. Ta struktura podataka treba podržavati sljedeće operacije za
skupove: provjera pripadnosti elementa, unija, presjek, razlika i jednakost. Dva multiseta su jednaka ako imaju isti broj svakog elementa. Nakon implementacije ove strukture podataka iskoristite je za rješenje zadatka 24. Ovaj zadatak riješite na dva
načina:
(a) Kao samostalna klasa.
(b) Kao klasa koja je izvedena (nasljeđuje) od ugrađenog tipa set

### 40.
Napišite funkciju spoji_mape(a, b) koja će ”spojiti” dvije mape, a i b, na sljedeći
način:
(a) Ako za isti ključ vrijednost niti u jednoj od mapa nije tipa list onda za vrijednost
x iz mape a i vrijednost y iz mape b u novoj mapi vrijednost treba biti lista [x,
y].
(b) Ako za isti ključ jedna mapa sadrži listu [e1, e2, ..., en], a druga vrijednost x
nekog drugog tipa, onda nova mapa za taj ključ treba sadržavati [e1, e2, ..., en,
x].
(c) Ako obje mape za dotični ključ sadrže liste onda nova mapa za taj ključ treba
sadržavati listu s vrijednostima iz obje liste.

### 41.
Napišite svoju implementaciju Pythonove funkcije groupby