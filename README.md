# Vaatimusmäärittely 

## Sovelluksen tarkoitus

MassiMatti on henkilökohtaisen talouden seurantaan tarkoitettu sovellus, jonka avulla käyttäjä voi pitää kirjaa menoistaan ja tuloistaan sekä tarkastella kirjaamiaan tapahtumia tapahtumia valitsemallaan ajanjaksolla niin teksimuodossa kuin graafisestikin. Sovellukseen voi rekisteröityä useampi käyttäjä.

## Käyttäjät

Sovelluksessa on alkuvaiheessa ainoastaan yksi käyttäjätyyppi eli normaali käyttäjä. Jatkossa sovellukseen mahdollisesti lisätään pääkäyttäjä asianomaisin oikeuksin.

## Suunnitellut toiminnallisuudet

### Kirjautuminen / Rekisteröityminen

* Sovellus aukeaa kirjautumisnäkymään, josta käyttäjä voi kirjautua sisään järjestelmään käyttäjänimellään ja salasanallaan. Mikäli käyttäjällä ei vielä ole luotuna tunnuksia, aloitusnäytöstä siirrytään rekisteröintinäkymään valitsemalla ‘luo tunnus’.
  * Rekisteröintinäkymässä käyttäjä luo tunnukset antamalla uniikin käyttäjänimen (vähintään 4 merkkiä) ja salasanan (vähintään 8 merkkiä)     ja valitsemalla ‘valmis’. Tästä siirrytään takaisin kirjautumisnäkymään.
  
### Järjestelmässä

Järjestelmän päänäkymässä käyttäjä voi:
  * lisätä uuden tapahtuman
    * päänäkymästä siirrytään tapahtumanäkymään ja lisäyksen ((pvm, tyyppi(meno/tulo), summa, kategoria, kuvaus) jälkeen takaisin           päänäkymään
  * lisätä uuden kategorian
    * päänäkymästä siirrytään katelistata tapahtumatgorianäkymään (kategoria nimi) ja lisäyksen jälkeen takaisin päänäkymään
  * listata tapahtumat
    * päänäkymästä siirrytään listausnäkymään, jossa valitaan ajanjakso, jonka perusteella listataan tulot ja menot vanhimmasta uusimpaan  sekä ilmoitetaan niiden erotus erillisessä tulosnäkymässä, joka suljetaan painikkeella
