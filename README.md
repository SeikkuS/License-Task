
# x)

## FSF Free Software Definition

Vapaat ohjelmistot ovat ohjelmistoja, jotka kunnioittavat käyttäjien vapautta ja yhteisöllisyyttä. Se tarkoittaa sitä, että käyttäjillä on vapaus käyttää, kopioida, jakaa, tutkia, muuttaa ja kehittää ohjelmistoa.
    
    Ohjelma katsotaan vapaaksi ohjelmistoksi, jos ohjelman käyttäjillä on neljä olennaista vapautta: 
    
    1. vapaus ajaa ohjelmaa haluamallaan tavalla
    
    2. Vapaus tutkia ja muuttaa ohjelmaa
    
    3. vapaus levittää ja kopioida versioita 
    
    4. Vapaus levittää muokattuja versioita.

## Rise of Open Source: 5 Open Source Licenses as Alternative Governance Mechanisms: 5.1.1 - 5.1.4 (sivu 113 - 121)

Kirjoituksessa käsitellään seuraavia asioita:

    - Avoimen lähdekoodin lisenssien vaatimuksia suhteessa tekijänoikeuslakiin
    
    - Avoimen lähdekoodin lisenssien on sallittava ohjelmiston kopiointi, jakelu ja muokkaaminen, mikä on ristiriidassa ohjelmistoteollisuuden perinteisen ajattelun kanssa
    - Avoimen lähdekoodin lisenssit eivät aseta vaatimuksia lisenssien yhteensopivuuksille, takuille tai muodollisuuksille
    
    - Avoimen lähdekoodin lisenssit eivät aseta vaatimuksia patenteille
    


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

## klo 12.15

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

