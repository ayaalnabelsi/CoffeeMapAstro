# Week 1
# Woensdag 
# Server Side Rendering
De pagina wordt op de server gemaakt voordat hij zichtbaar is, we krijgen dus een kant en klare website in beeld.

# Client Side Rendering
De browser maakt de pagina zelf met js, dus eerst een lege website daarna wordt de content geladen.

# Web Api =>
Een Web API is een set functies die door de browser beschikbaar wordt gesteld. 

# Voorbeelden
- Storage API
- WebGL API
- Canvas API
- LocalStorage API
- Drag and Drop API

# Content Api =>
Een content API wordt gebruikt om bestaande data van een externe bron op te halen. 

# Voorbeeld
- Spotify API
- The One API
- Poke API
- Giphy API

# Concept 
Ik maak een webapp waarin gebruikers verschillende koffiesoorten kunnen ontdekken. De app helpt gebruikers om nieuwe koffies te leren kennen door een overzichtspagina met verschillende koffiesoorten en een detailpagina met uitleg over een specifieke koffie zoals ingrediënten en hoe de koffie wordt gemaakt.

Daarnaast bevat de app een pagina met cafés waar studenten goed kunnen studeren. Hierbij kun je denken aan cafés met wifi, rustige plekken.

# Donderdag voortgangsgesprek
# Feedback 
- Eerst kijken naar api's welke data er allemaal beschikbaar is.
- Woensdag nog een keer feedback vragen over concept 


# Week 2
# Woensdag 
# Feedback 
Aangezien er geen API bestaat die specifieke cafés bijv Italiaans kan ophalen overweeg ik om een algemene kaart te tonen met de dichtstbijzijnde cafés in de buurt van de gebruiker. De gebruiker kan op de pins klikken om informatie over het café te bekijken.

 Als er tijd over is ga ik de LocalStorage gebruiken om favoriete cafés op te slaan hiervoor is extra tijd nodig om componenten, knoppen en interacties te bouwen, omdat veel tijd naar de kaart en bijbehorende functionaliteiten gaat.

# Concept aanpassing
Webapp waarmee gebruikers cafés in de buurt kunnen vinden en locaties kunnen delen met anderen en als favoriete markeren.

De app toont een kaart met cafés in de buurt van de gebruiker, op de kaart staan pins waarop de gebruiker kan klikken om informatie over het café te bekijken. Gebruikers kunnen vervolgens een café delen met anderen en als favoriete opslaan

# Overzichtspagina 
Een kaart waarop cafés in de buurt worden getoond.

# Detailweergave 
Wanneer een gebruiker op een café pin klikt met informatie over het café.

# Content API:
# Google Maps API 
 Om de kaart te bouwen en locaties te tonen.

# Web API:
# Share API 
Om een café locatie te delen via bijvoorbeeld WhatsApp of andere apps.

# Geolocation:
Gebruiken om het land/locatie te bepalen.

# Donderdag
# Workshop LocalStorage
- LocalStorage slaat data op in de browser en niet op de server.
- Geen gevoelige data opslaan in LocalStorage.
- Alles wordt opgeslagen als string → oplossen met:
JSON.stringify() om data op te slaan
JSON.parse() om data terug te halen

- Werken met keys tussen aanhalingstekens"".
- localStorage.clear() verwijdert alles definitief.
- SessionStorage werkt hetzelfde, maar is tijdelijk → LocalStorage gebruik je voor langdurige opslag.

- Nieuw Astro project aangemaakt.
- Content API ingeladen.
- Kaart gemaakt met pin.
- README aangevuld.

# Bronnen
- https://leafletjs.com/examples/quick-start/ 
