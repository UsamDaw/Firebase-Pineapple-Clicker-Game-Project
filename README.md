# Pineapple Clicker Game

<br/>

### Introduksjon
Dette er en klikkerspill-app hvor brukeren kan samle poeng ved å klikke på en ananas. Poengene blir lagret i Firebase, og brukeren kan logge inn for å holde styr på sin fremgang. Spillet er responsivt og fungerer godt på forskjellige skjermstørrelser.


### Funksjoner
- Brukere kan registrere seg og logge inn med sin e-post.
- Poeng blir lagret i Firebase og koblet til brukerens konto.
- Spill elementer er tilpasset for å fungere godt på forskjellige skjermstørrelser.
- Bruk av "vw" på game.html sikrer at elementer holder en stabil størrelse, uansett zoomnivå.
- Knappene reagerer på hover og klikk, spesielt "buttonPineapple" som gir en tilfredsstillende klikkrespons.
- Brukervennlige tilbakemeldinger for feil og suksessmeldinger.
- En leaderboard med data sanntidslagring som viser de 10 beste brukerne med flest poeng fra høy til lav.


### Teknologier og programvarer brukt
- HTML, CSS, JavaScript for frontend.
- Firebase for autentisering og datalagring.

<br/>

### Krav for å kjøre nettstedet
#### Programvarekrav:
- En moderne nettleser (Chrome, Firefox, Edge, Safari, etc)
- Ditt eget Firebase konto for backend tjenester

<br/>

### Konfigurasjon:
#### Opprett en Firebase prosjekt og aktiver:
- Authentication (E-post/passord innlogging)
- Firestore Database

#### Konfigurer Firebase:
- Oppdater firebaseConfig i JavaScript filene med dine egne Firebase API nøkler.

#### Kjør nettsiden:
- Åpne index.html i en nettleser, eller bruk en live server som VS Code Live Server Extension i Visual Studio Code programvare.

<br/>

## Læring og utfordringer, og konklusjon:

<br/>

#### Hva jeg har lært:
- Bruke Firebase til å lagre og hente data.
- Strukturere og optimalisere CSS for responsivt design.
- Lage animasjoner og interaktive UI elementer.
- Hvordan håndtere tilbakemeldinger til brukeren.

<br/>

### Utfordringer:
- Den største utfordringen var å lagre brukerens poeng i Firebase og vise e-post ID-en for å bekrefte pålogging. Det tok mye tid å feilsøke og få databasen til å oppdatere riktig.
- En annen utfordring var JavaScript koden. Jeg brukte mye tid på å fikse den, men til slutt måtte jeg bruke AI for å rydde opp i strukturen, rette opp feil og få tilbakemeldingene til å fungere skikkelig.

<br/>

### Stolthet
Jeg er stolt av at jeg har laget all CSS stylingen for hånd uten hjelp fra AI eller YouTube tutorials. Det var mye arbeid, men jeg lærte masse om styling og responsivt design. Derimot brukte jeg AI til å hjelpe med JavaScript-koden fordi den var rotete og vanskelig å feilsøke alene.

Jeg er også fornøyd med at jeg modifiserte og tilpasset to bilder (ananas-knappen og palmtrærne), som passet veldig bra med bakgrunnsfargene. 

<br/>

### Konklusjon
Dette prosjektet har vært en stor læringsopplevelse. Jeg er fornøyd med hvordan game.html håndterer skjermstørrelser med 'vw' mens index.html ikke fungerte like bra med det. Spillopplevelsen er jevn, og brukeren får en god respons på klikk og hover-effekter.

Selv om Firebase integrasjonen var et utfordring, er jeg fornøyd med sluttresultatet og hvordan jeg har klart å løse de fleste problemene underveis. 👍

<br/>

### Øyeblikksbilder:
![](https://github.com/UsamDaw/Firebase-Pineapple-Clicker-Game/blob/main/Screenshot%202025-02-05%20134107.png)  ![](https://github.com/UsamDaw/Firebase-Pineapple-Clicker-Game/blob/main/Screenshot%202025-02-05%20134034.png) 
