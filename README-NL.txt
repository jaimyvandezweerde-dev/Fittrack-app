FITTRACK VOOR IPHONE — GRATIS WEBAPP
===================================

Dit is een eerste mobiele webversie op basis van de functies en berekeningsregels uit je aangeleverde FitTrack-project. Dit is geen native iOS-app en vervangt je oorspronkelijke Visual Studio-project niet.

INHOUD
- index.html: schermen en formulieren
- style.css: mobiele vormgeving
- app.js: berekeningen, maaltijden, gewicht en lokale opslag
- manifest.webmanifest en iconen: installeren als webapp
- sw.js: cache voor opnieuw openen na eerste bezoek

GRATIS ONLINE ZETTEN VIA GITHUB PAGES
1. Pak FitTrack-iPhone.zip uit op je Windows-pc.
2. Ga naar https://github.com en maak gratis een account als je er nog geen hebt.
3. Maak een nieuwe repository, bijvoorbeeld fittrack-app. Kies Public.
4. Upload de BESTANDEN uit deze map (niet de map als extra tussenlaag) naar de hoofdmap van de repository.
5. Open in GitHub: Settings → Pages.
6. Bij Build and deployment kies je Deploy from a branch. Branch: main; folder: /(root). Klik Save.
7. Wacht tot GitHub Pages het adres toont, doorgaans https://JOUWGEBRUIKERSNAAM.github.io/fittrack-app/.
8. Open dat adres op je iPhone in Safari.
9. Tik op de deelknop → Zet op beginscherm → Voeg toe.

PRIVACY EN BEPERKINGEN
- Je profiel, maaltijden en metingen worden opgeslagen in de lokale browseropslag op het apparaat. Ze worden niet automatisch met andere apparaten gesynchroniseerd.
- Verwijder je browsergegevens, dan kan lokale data verloren gaan. Gebruik geregeld Gegevens exporteren (JSON) als back-up.
- De calorie- en macroberekeningen volgen de regels uit het aangeleverde C#-bestand BerekeningService.cs; ze zijn schattingen en geen medisch advies.
- Dit is een eerste port van de kernfuncties, niet een pixel-perfecte kopie van alle WPF-schermen. De oorspronkelijke C#-code is niet verwijderd of aangepast.
- GitHub Pages is een publieke statische host. De sitecode is publiek; persoonlijke waarden die je in FitTrack invult worden lokaal opgeslagen en niet naar GitHub verzonden.
