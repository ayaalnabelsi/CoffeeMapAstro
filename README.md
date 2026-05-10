# Week 1
## Woensdag 
### Server Side Rendering
De pagina wordt op de server gemaakt voordat hij zichtbaar is, we krijgen dus een kant en klare website in beeld.

### Client Side Rendering
De browser maakt de pagina zelf met js, dus eerst een lege website daarna wordt de content geladen.

### Web Api =>
Een Web API is een set functies die door de browser beschikbaar wordt gesteld. 

### Voorbeelden
- Storage API
- WebGL API
- Canvas API
- LocalStorage API
- Drag and Drop API

### Content Api =>
Een content API wordt gebruikt om bestaande data van een externe bron op te halen. 

### Voorbeeld
- Spotify API
- The One API
- Poke API
- Giphy API

### Concept 
Ik maak een webapp waarin gebruikers verschillende koffiesoorten kunnen ontdekken. De app helpt gebruikers om nieuwe koffies te leren kennen door een overzichtspagina met verschillende koffiesoorten en een detailpagina met uitleg over een specifieke koffie zoals ingrediënten en hoe de koffie wordt gemaakt.

Daarnaast bevat de app een pagina met cafés waar studenten goed kunnen studeren. Hierbij kun je denken aan cafés met wifi, rustige plekken.

### Reflectie
Ik heb  mij verdiept in Server Side Rendering en Client Side Rendering, ik heb onderzocht wat de verschillen zijn tussen deze technieken en hoe websites data laden en tonen aan gebruikers. Daarnaast heb ik onderzoek gedaan naar verschillende soorten web en content API’s en voorbeelden daarvan opgezocht. Ook ben ik gaan nadenken over mijn concept. Mijn eerste idee was een webapp waarin gebruikers verschillende koffiesoorten kunnen ontdekken via een overzichtspagina en detailpagina met informatie over ingrediënten en de bereidingswijze. Daarnaast wilde ik een pagina toevoegen met cafés die geschikt zijn voor studenten om te studeren, bijvoorbeeld cafés met wifi en rustige werkplekken.

## Donderdag voortgangsgesprek
### Feedback
Ik heb tijdens de feedbacksessie mijn concept besproken, hierdoor kreeg ik meer inzicht in hoe realistisch en haalbaar mijn idee was en of er geschikte API’s beschikbaar waren voor de data die ik nodig had.

De feedback die ik heb meegenomen was dat ik eerst goed moest onderzoeken welke API’s beschikbaar zijn en welke data deze precies aanbieden. Daarnaast kreeg ik het advies om op woensdag opnieuw feedback te vragen over mijn concept, zodat ik beter kon beoordelen of het haalbaar genoeg was om verder uit te werken.

# Week 2
## Woensdag 
### Feedback 
ik heb verder onderzoek gedaan naar API’s voor mijn koffieconcept. Tijdens dit onderzoek kwam ik erachter dat er geen geschikte API beschikbaar was die specifieke koffiedata of cafés, zoals Italiaanse koffie ondersteunde op de manier die ik voor ogen had. Hierdoor ben ik opnieuw gaan nadenken over de haalbaarheid van mijn concept.

Tijdens de feedbacksessie kreeg ik het advies om mijn idee eenvoudiger en realistischer te maken. Daarom ben ik gaan overwegen om in plaats van specifieke koffiesoorten een algemene kaart te maken met cafés in de buurt van de gebruiker. Op deze kaart kan de gebruiker op pins klikken om meer informatie over een café te bekijken.

### Concept aanpassing
Na de feedback en het onderzoek naar beschikbare API’s heb ik mijn concept aangepast. In plaats van een app gericht op specifieke koffiesoorten ben ik verder gegaan met een realistischer en haalbaar concept.

Mijn aangepaste concept is een webapp waarmee gebruikers cafés in de buurt kunnen vinden, locaties kunnen delen met anderen en cafés als favoriet kunnen opslaan.

De app toont een interactieve kaart met cafés in de omgeving van de gebruiker. Op de kaart staan pins waarop gebruikers kunnen klikken om meer informatie over een café te bekijken. Daarnaast kunnen gebruikers een café delen met anderen en favoriete locaties opslaan voor later gebruik.

Voor het bouwen van de kaart maak ik gebruik van de Leaflet API hiermee kan ik de kaart kan maken, markers en popups kan toevoegen aan de kaart hierdoor kunnen gebruikers eenvoudig cafés bekijken en ermee interacteren.

Daarnaast gebruik ik verschillende Web API’s binnen mijn project. Met de Share API kunnen gebruikers een café locatie delen. Ook gebruik ik de Geolocation API om de locatie van de gebruiker op te halen. Eerst vraagt de browser toestemming om de locatie te delen. Daarna wordt de huidige locatie gebruikt om cafés in de buurt van de gebruiker te tonen. Hiervoor gebruik ik navigator.geolocation.getCurrentPosition() om de locatiegegevens op te halen.

# Donderdag
Tijdens de workshop over LocalStorage heb ik geleerd hoe data lokaal in de browser wordt opgeslagen in plaats van op een server. Ik heb geleerd dat je geen gevoelige informatie in LocalStorage moet bewaren, omdat gebruikers dit zelf kunnen bekijken. Ook ontdekte ik dat LocalStorage alles als string opslaat. Daarom JSON.stringify() gebruikem om data op te slaan en JSON.parse() om data weer terug om te zetten naar bruikbare JavaScript data.
Daarnaast heb ik geleerd dat werken met keys tussen aanhalingstekens en dat localStorage.clear() alle opgeslagen data definitief verwijdert. Ook heb ik het verschil geleerd tussen SessionStorage en LocalStorage. SessionStorage is tijdelijk en verdwijnt wanneer de browser wordt gesloten, terwijl LocalStorage data langer bewaart.
Naast de workshop heb ik verder gewerkt aan mijn project. Ik heb een nieuw Astro project aangemaakt, de Content API ingeladen en een eerste kaart met een pin gebouwd.

# Week 3
## Woensdag
Ik ben begonnen met het inladen van de Leaflet API, Daarna heb ik GeoSearch toegevoegd, zodat gebruikers binnen de kaart kunnen zoeken naar plekken. Ik heb ook geprobeerd om de Google Maps API te gebruiken, maar dit lukte niet omdat je hiervoor een creditcard nodig hebt. Tijdens dit onderzoek kwam ik er ook achter dat veel andere API’s om cafés op te halen betaald zijn of een betaalmethode vereisen, daardoor kon ik mijn idee niet verder uitvoeren zoals gepland.
Daarnaast heb ik gewerkt aan een zoekfunctie en heb ik gekeken naar extra functies zoals de Share API om locaties te delen en de Geolocation API om de locatie van de gebruiker op te halen. Hierdoor kon ik mijn project toch verder uitbreiden en interactiever maken.
## Donderdag 
ik ben overgestapt naar de content API van Open Data Amsterdam ik heb hiervoor gekozen omdat er geen gratis API beschikbaar was waarmee ik cafés kon ophalen, waardoor mijn eerste idee niet haalbaar bleek.
Met deze nieuwe API heb ik data opgehaald van barbecueplekken in Amsterdam, zoals de naam van het park, de status en een toelichting. Deze informatie gebruik ik om de locaties op de kaart weer te geven en er extra context aan te geven. Ook heb ik de huisstijl van de gemeente Amsterdam toegepast in mijn ontwerp om het geheel beter te laten aansluiten bij de data.
Daarnaast heb ik ervoor gekozen om de detailinformatie niet op een aparte pagina te tonen, maar op dezelfde pagina onder de kaart. Hierdoor blijft de gebruiker in dezelfde pagina en wordt de ervaring overzichtelijker en sneller.
Wanneer een gebruiker op een locatie klikt, verschijnen de details van het park direct onder de kaart. Vanuit daar kan de gebruiker een locatie opslaan of verwijderen hiervoor gebruik ik de LocalStorage API, zodat opgeslagen parken bewaard blijven ook wanneer de pagina opnieuw wordt geladen.

## Vrijdag
### Feedback
De applicatie moet responsief zijn voor op mobiel en desktop. Ook werd geadviseerd om de locatie toestemming pas via een popup te vragen met een duidelijke uitleg in plaats van direct bij het openen van de pagina.

Daarnaast moet de kaart beperkt worden tot Amsterdam, zodat gebruikers niet verder kunnen inzoomen dan de stad zelf. Voor de detailpagina is het beter om de kaart te laten inzoomen op de gekozen locatie.
Verder kreeg ik de feedback om de Amsterdam huisstijl beter toe te passen inclusief het logo. Op de homepage moet duidelijkere uitleg komen en de status van BBQ plekken moet beter zichtbaar zijn waar wel en niet gebarbecued mag worden.

Verder meer aandacht besteden aan de UX, zodat de applicatie overzichtelijker en gebruiksvriendelijker wordt.

# Week4
## Woensdag
Ik heb mijn README verder aangevuld en de bronvermelding gecontroleerd en netjes gedocumenteerd.

Daarnaast heb ik opnieuw gekeken naar de voorwaarden van de API’s die ik gebruik. Ook heb ik de code doorgenomen om deze beter te begrijpen en beter te kunnen uitleggen hoe alles werkt.

Tijdens de feedback kreeg ik de tip om de logica uit mijn map bestand te verplaatsen naar de index en om de LocalStorage file te verwijderen. Ook werd aangeraden om gebruik te maken van SSR en om toch een tweede detailpagina te maken, zodat ik hiermee kan oefenen en mijn routing beter kan begrijpen en toepassen.

 # Bronnen
- https://leafletjs.com/examples/quick-start/ 
- https://leafletjs.com
- https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API 
- https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage
- https://maps.amsterdam.nl/open_geodata/
- https://tile.openstreetmap.org
- https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage
- https://developer.mozilla.org/en-US/docs/Web/SVG/Reference/Attribute/fill-opacity
- https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage
- https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage
- https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/calc 
