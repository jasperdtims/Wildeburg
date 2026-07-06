# Wildeburg webapp voor iOS via GitHub Pages

Deze map is klaar om direct in een GitHub repository te zetten en via GitHub Pages te publiceren.

## Bestanden

- `index.html` - de app
- `manifest.webmanifest` - PWA instellingen
- `sw.js` - service worker voor caching en offline gebruik na de eerste keer laden
- `icons/` - iOS en PWA iconen
- `.nojekyll` - voorkomt dat GitHub Pages Jekyll op de bestanden toepast

## Publiceren op GitHub Pages

1. Maak een nieuwe repository aan op GitHub, bijvoorbeeld `wildeburg-webapp`.
2. Upload alle bestanden uit deze map naar de root van de repository.
3. Ga in GitHub naar `Settings` > `Pages`.
4. Kies bij `Build and deployment` voor `Deploy from a branch`.
5. Kies branch `main` en folder `/root`, en klik op `Save`.
6. Open de GitHub Pages URL op je iPhone in Safari.
7. Tik op het deel-icoon en kies `Zet op beginscherm`.

## Belangrijk voor iOS

- Gebruik Safari om de webapp aan het beginscherm toe te voegen.
- Meldingen werken alleen wanneer iOS en Safari dit ondersteunen en de gebruiker toestemming geeft.
- De app gebruikt `localStorage`, dus logs en favorieten worden lokaal op het apparaat opgeslagen.
- Offline openen werkt pas nadat de app minimaal één keer online is geopend.
