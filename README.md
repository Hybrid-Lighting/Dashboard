# Dashboard

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.


## Installation

1. Download windows binary van https://nodejs.org/en/download/ en pak het bestand uit op een eigen gekozen locatie.
2. Open een powershell windows in de map van het uitgepakte zip bestand.
3. Voer het volgende commando uit om het node red dashboard te installeren
   ```sh
   .\npm install -g --unsafe-perm node-red node-red-dashboard
   ```
4. In je User map zal ook een map genaamd .node-red verschijnen, zet de inhoud van deze git repository in deze map.
5. Voer vervolgens in het powershell van het uitgepakte zip bestand het volgende commando uit:
   ```sh
   .\node-red
   ```
6. Het dashboard wordt gestart en is vervolgens te vinden op http://localhost:1880/ui/
7. Het dashboard kan eventueel aangepast worden via http://localhost:1880/