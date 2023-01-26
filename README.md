# a) Lisenssit

26.1. klo 9.28 katsoin lataamieni sovellusten lisenssit etsimällä verkosta kyseisten sivujen omat sivut (/tai wikisivut)

FIGlet: New BSD (3) (tuotteella tai sen valmistajien nimillä ei voida mainostaa, tuotteen mukana tulevia ehtoja on noudatettava)

Cowsay: GNU General Public License (oikeus käyttää, tutkia, jakaa ja muokata)

Fortune:  GNU Free Documentation License 1.3 (oikeus kopioida ja jakaa)

Kaikki kolme ovat vapaita lisenssejä

# b) Grep Regex

klo 12.07 käytin grep -komentoa etsiäkseni tietoa tekstitiedosta eri avainsanoilla tai kirjaimilla. Tässä testissä kokeilin etsiä tietoa grep -E -komennolla (regex). Tein sitä varten oman tekstitiedoston, josta hain tietoa.

![kuva](https://user-images.githubusercontent.com/105205141/214809667-b4520b4c-358a-43e2-b34c-8df9842b5ff2.png)

# c) Pipe

Putkilla pystytään syöttämään tietoa yhdestä tiedostosta, scriptistä, tulostuksesta inputiksi toiseen. 

esim. 

    cat esimerkki.txt
    Bob
    Lau
    Kek
    Haha
    Olo
    
tämän tekstitiedoston sisältö voidaan syöttää inputiksi putkella sort-komentoon, jolloin pystytään lajittelemaan teksti eri järjestykseen

    cat esimerkki.txt | sort
    
Jolloin tekstin rivit muuttuvat aakkosjärjestykseen.

![kuva](https://user-images.githubusercontent.com/105205141/214811415-b1d00505-dac3-40e6-a49f-20247b2d2eda.png)

