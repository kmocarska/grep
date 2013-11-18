Zadanie 1

W pliku „plik.txt” znajdź wiersze zawierające 
co najmniej jeden znak.
```
egrep "[:alnum:]{1,}" plik.txt
```

Zadanie 2

Znajdź w plikach „pl*” wiersze rozpoczynające się od cyfry.
```
grep ^[0-9] pl*

```
Zadanie 3

Znajdź pliki, w których na 9 pozycji występuje litera „r”.
```
egrep -l "^.{8}r" *
```
Zadanie 4

Policz, ilu użytkowników systemu używa powłoki bash (zgodnie z zapisami 
w pliku /etc/passwd).

```
grep -c bash /etc/passwd
```

Zadanie 5

Znajdź wiersze zawierające liczby rzymskie w pliku „plik.txt”.

```
grep [IVXLCDM] plik.txt
```

Wyświetl wszystkie wiersze pliku grep.txt zawierające literę 'a' 
```
kina@Kina-Linux:~$ grep [a] grep.txt
Ala ma kota
, a
ma ich 3
*A może ma ich
Ta linie zaczyna sie od dwoch spacji...
Powyżej mamy pusta linie.
adres e
mailowy to
wardd@
math.uni.lodz.pl
moim nie jest wardd@math.lodz.com
```

Wyświetl wszystkie wiersze pliku grep.txt zawierające literę 'a' lub 'A 
```
kina@Kina-Linux:~$ grep [aA] grep.txt
Ala ma kota
, a
ma ich 3
*A może ma ich
Ta linie zaczyna sie od dwoch spacji...
Powyżej mamy pusta linie.
Ale dziwny ten plik ... Nic z tego nie rozumiem!!!
adres e
mailowy to
wardd@
math.uni.lodz.pl
A
moim nie jest wardd@math.lodz.com
```

Wyszukaj w pliku grep.txt linie zawierające "ma" 

```
 grep "ma" grep.txt
Ala ma kota
ma ich 3
*A może ma ich
Powyżej mamy pusta linie.
mailowy to
math.uni.lodz.pl
moim nie jest wardd@math.lodz.com
```

Wyszukaj
w pliku grep.txt linie zawierają
ce "?"

```
kina@Kina-Linux:~$ grep "?" grep.txt
?
{o co chodzi?...} Pomocy!!!
```

W pliku grep.txt wyszukaj wszystkie linie w których znajdują się 'za', 'ma', 'ta' 

```
grep "[zmt]a" grep.txt
Ala ma kota
ma ich 3
*A może ma ich
Ta linie zaczyna sie od dwoch spacji...
Powyżej mamy pusta linie.
mailowy to
math.uni.lodz.pl
moim nie jest wardd@math.lodz.com
```

Ile wierszy w pliku grep.txt zawiera słowo "Ala"?

```
grep -c "Ala" grep.txt
1
```

W których wierszach
pliku grep.txt
(które numery wierszy) występują dowolne słowa na litery 'z'
lub 'd 

```
```

Wyszukaj wie
rsze w pliku grep.txt, które na końcu mają liczbę parzystą.

```
```

