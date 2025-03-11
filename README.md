# Squad page

Ontwerp en maak met een team een website met NodeJS en JSON.

De instructie vind je in: [INSTRUCTIONS](https://github.com/fdnd-task/connect-your-tribe-squad-page/blob/main/docs/INSTRUCTIONS.md)

## Inhoudsopgave Squad page

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Gebruik](#gebruik)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
Op deze pagina is een overzicht van alle fdnd studenten. Bij hun wordt allemaal op dynamische wijze hun profielfoto, naam en leeftijd getoont.
Door op de bovenste 3 filters te klikken is het mogelijk om te filteren op bepaalde informatie over de studenten
<img width="1192" alt="image" src="https://github.com/user-attachments/assets/a9011c9a-d526-4e18-9323-030ca17ee6a5" />


## Interactie
Op deze pagina zit een interactie: De filterknoppen. Ook voor deze knoppen is de huisstijl van FDND gebruikt. Wanneer een gebruiker hier overheen hovert met zijn cursor klapt deze uit en kan een filter geselecteerd worden. Ook is hierbij aan feedforward gedacht door wijzende vingers bij de knoppen te zetten. Deze geven aan dat er informatie onder komt te staan.

## Routes en dataverwerking

app.get('/'): Haalt de geboortedatum op en rekend deze om naar een leeftijd. Ook wort hier de naam en profielfoto opgehaald uit de directus API. Mocht een student geen profielfoto hebben, wordt deze vervangen door een placeholder.
app.get('/leeftijd'): Haalt de vorige informatie opnieuw op. Maar nu wordt er gefilterd op leeftijd

## Uitleg NodeJS, Express en Liquid

NodeJS

Met NodeJS kun je JavaScript op een server draaien. Hiermee kun je get request/responses bouwen om met de database te communiceren. Zoals ik in dit project heb gedaan.

Express

Express is een hulpmiddel binnen NodeJS, waarmee een webserver gebouwd kan worden. Je kunt bijvoorbeeld instellen welke pagina's en data getoond wordt.

Liquid

Liquid is een template-engine waarmee je dynamische HTML-pagina's kunt genereren.

## Installatie

Zoals beschreven bij Kenmerken is bij dit project gebruik gemaakt van NodeJS. Om aan dit project te werken moet NodeJS geïnstalleerd zijn. Eenmal geïnstalleerd kan het project geopend worden in de code editor.

Voer in de terminal npm install uit om alle afhankelijkheden te installeren.

Voer vervolgens npm start uit om de server te starten.

Ga in je browser naar http://localhost:8000 om het project te bekijken.


## Bronnen

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
