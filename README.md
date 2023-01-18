# Dashboard

In deze repository staat de code van het dashboard dat gemaakt is om de waarde van de microcontroller op afstand uit te lezen.
Ook kan vanaf hier de stroombron via de microcontroller gewisseld worden tussen de accu en de netstroom.
In de installatiehandleiding hier onder is te zien hoe de benodigde software geinstalleerd kan worden.
Vervolgens is te zien hoe het dashboard gestart kan worden en hoe er aanpassingen te maken zijn.


## Installatie

1. Download de windows binary van https://nodejs.org/en/download/ en pak het bestand uit op een eigen gekozen locatie.
2. Open een powershell window in de map van het uitgepakte zip bestand.
3. Voer het volgende commando uit om het node red dashboard te installeren
   ```sh
   .\npm install -g --unsafe-perm node-red node-red-dashboard
   ```
4. In je User map zal ook een map genaamd .node-red verschijnen, zet de inhoud van deze git repository in deze map.
   Hierbij gaat het vooral om het bestand "flows.json" waarin de opmaak van het dashboard zit.

## Gebruik

1. Om het dashboard te gebruiken voer je het volgende commando uit in het powershell window van het uitgepakte zip bestand:
   ```sh
   .\node-red
   ```
2. Het dashboard wordt gestart en is vervolgens te vinden op http://localhost:1880/ui/

## Development

Het dashboard kan eventueel aangepast worden via http://localhost:1880/
Hier kunnen knoppen worden toegevoegd die aan MQTT kanalen kunnen worden gekoppeld.
Ook kunnen er tekst of visualisaties gekoppeld worden aan inkomende MQTT kanalen.