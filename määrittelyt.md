## Projektisuunnitelma


## Ydintoiminnallisuus (Kirjautumaton käyttäjä)

1. Käyttäjänä voin selata sivuston sisältöä (elokuvat, sarjat) ilman kirjautumista.
2. Käyttäjänä voin käyttää hakupalkkia löytääkseni elokuvia ja sarjoja.
3. Käyttäjänä näen alkusivulla "Recent reviews" -listauksen.
4. Käyttäjänä, jos yritän tehdä kirjautumista vaativan toimenpiteen (esim. arvostelun kirjoittaminen), näen pop-up-ikkunan, joka kehottaa kirjautumaan sisään tai luomaan tunnuksen.
5. Käyttäjänä voin tarkastaa Finnkinon näytösajat (integraatio Finnkino-API:hin).
6. Käyttäjänä voin nähdä listauksen olemassa olevista ryhmistä, mutta en näe niiden sisältöä, jos ne ovat yksityisiä.
7. Käyttäjänä voin lukea arvosteluita ja nähdä arvostelun kirjoittajan käyttäjänimen.

## Käyttäjähallinta & Profiili

8. Käyttäjänä voin luoda käyttäjätunnuksen.
9. Käyttäjänä voin kirjautua sisään ja ulos.
10. Käyttäjänä voin nollata unohdetun salasanani ("Unohditko salasanasi").
11. Käyttäjänä voin ladata kaikki minua koskevat tiedot (GDPR-data export). *
12. Käyttäjänä voin poistaa käyttäjätilini pysyvästi (GDPR-oikeus poistoon).

## Sisällön hallinta & Interaktio

13. Kirjautuneena käyttäjänä voin kirjoittaa arvostelun elokuvasta/sarjasta.
14. Kirjautuneena käyttäjänä voin lisätä tai poistaa elokuvan/sarjan suosikeistani.
15. Kirjautuneena käyttäjänä voin tykätä (Like) tai ei tykätä (Dislike) muiden arvosteluista. *
16. Kirjautuneena käyttäjänä voin jakaa pikalinkin elokuvan/sarjan/ryhmän sivusta sosiaaliseen mediaan. *

## Yhteisö (Faniryhmät)

17. Kirjautuneena käyttäjänä voin luoda uuden julkisen tai yksityisen faniryhmän.
18. Kirjautuneena käyttäjänä voin liittyä tai poistua faniryhmistä.
19. Kirjautuneena käyttäjänä voin muokata omistamani ryhmän ulkoasua (esim. profiilikuva, teemat).
20. Ryhmän omistajana tai moderaattorina voin antaa eri rooleja (admin, moderaattori) ryhmän jäsenille. *
21. Ryhmän omistajana tai moderaattorina voin estää käyttäjän pääsyn ryhmään. *
22. Kirjautuneena käyttäjänä voin raportoida sopimattomia ryhmiä, arvosteluja, kommentteja tai käyttäjiä. *

## Listaukset & Suositukset

23. Käyttäjänä voin selata ja suodattaa elokuva-/sarjalistauksia eri kriteereillä (esim. suosituimmat, uusimmat, genre, ikäraja).
24. Kirjautuneena käyttäjänä voin nähdä listauksen, jossa näkyvät ystävieni suosittelemat elokuvat/sarjat. *

## Ylläpito & Moderaatio

25. Ylläpitäjänä voin hallinnoida kaikkia käyttäjiä, arvosteluja, kommentteja ja ryhmiä (lisätä, muokata, poistaa). *
26. Ylläpitäjänä voin estää käyttäjän kirjautumisen. *
27. Ylläpitäjänä voin nähdä kaikki raportoidut kohteet ja toimia niiden perusteella. *
28. Ylläpitäjänä voin käyttää moderaationäkymää sisällön hallintaan. *
29. Ylläpitäjänä voin asettaa sivustolle huoltokatkotilan, jossa näytetään asianmukainen viesti kävijöille. *

## Sivuston hallinta

30. Ylläpitäjänä voin asettaa evästehallinnan (Cookies), jossa käyttäjät voivat hyväksyä evästeet. *
31. Ylläpitäjänä voin ylläpitää Tietosuojaselosteen ja Käyttöehtojen sivuja. *
32. Ylläpitäjänä voin ottaa käyttöön sanasuodattimen ("natsifiltteri"), joka sensuroi loukkaavat sanat. *

## Käyttöliittymä (UI) & Lokalisointi

33. Kaikkina käyttäjinä näemme käyttöliittymän englanniksi.
34. Kaikkina käyttäjinä meillä on mahdollisuus vaihtaa sivuston kieltä kielivalikon (Google Translate) kautta. *
35. Sivu on responsiivinen ja toimii suosituimmilla laitteilla.
36. Käyttäjänä näen kirjautumis/uloskirjautumis/profiili-napin.
37. Käyttäjänä näen etusivulla sattumanvaraisesti valitun kuvan/bannerin.

---

## Lisäominaisuudet ja tekninen toteutus

### UI-komponentit
- Haku-palkki ylätunnisteessa
- Recent reviews -osio alkusivulla
- Kirjautumis/profiili-navigaatio
- Responsiivinen layout (toimii mobiili, tabletti, desktop)

### Integraatiot
- Finnkino API (näytösajat)
- Google Translate API (kielivalikko) *
- Sosiaalisen median jako-ominaisuudet (pikalinkit) *

### Tekninen infrastruktuuri
- Evästeiden hallinta ja suostumusten keruu
- GDPR-yhteensopivuus (tietojen lataus ja poisto)
- Huoltokatkotila kriittisten virheiden varalle
- Sanasuodatin (loukkaavien sanojen sensurointi)

