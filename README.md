# helpdesk-cli
Helpdesk CLI -ohjelma

# Helpdesk CLI – IT-tukipyyntöjärjestelmä

## Esittely
**Helpdesk CLI** on interaktiivinen, tekstipohjainen Python-konsolisovellus IT-tukipyyntöjen (tikettien) hallintaan. Sovelluksen avulla IT-tukihenkilö voi kirjata uusia tukipyyntöjä, selata kaikkia tai vain avoimia tikettejä, hakea tikettejä avainsanalla sekä kuitata tukipyyntöjä ratkaistuiksi.

## Toteutustapa ja rakenne
Ohjelma on toteutettu Pythonilla hyödyntäen modulaarista rakennetta:
* **Tietorakenteet:** Tukipyynnöt tallennetaan ohjelman suorituksen ajaksi listaan (`list`), jonka sisällä jokainen tiketti on tallennettu sanakirjana (`dict`).
* **Silmukat ja ehtolauseet:** Päävalikko pyörii `while True` -silmukassa, ja tikettien läpikäyntiin sekä suodattamiseen käytetään `for`-silmukoita ja `if/else`-ehtolauseita.
* **Aliohjelmat:** Jokainen päätoiminto (luonti, listaus, haku, tilan päivitys) on jaettu omaan aliohjelmaansa (funktioon), jotka on dokumentoitu PyDoc-yhteensopivilla `docstring`-kommenteilla.

## Ohjelman toimintalogiikka (Vuokaavio)
Alla oleva vuokaavio kuvaa ohjelman pääsilmukan ja aliohjelmien toimintalogiikan:

<img width="1024" height="765" alt="image" src="https://github.com/user-attachments/assets/7577fa52-21ef-49f3-b2b4-dc3bb25cadd4" />
![Ohjelman vuokaavio](vuokaavio.png)

## Käynnistysohje


   git clone [https://github.com/CharllesC78.git](https://github.com/CharllesC78/helpdesk-cli.git)
   cd helpdesk-cli

   

