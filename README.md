# Sirva Productions — website

Statische website (HTML/CSS/JS, geen build-stap nodig) met vier pagina's:

- `index.html` — Home
- `over.html` — Over
- `diensten.html` — Diensten (met pakketten)
- `contact.html` — Contact (met contactformulier)

## Wat je nog moet invullen

Zoek in de bestanden naar tekst tussen `[ ]` en vul aan:

- `over.html` — achtergrond/bio
- `diensten.html` — prijzen bij elk pakket
- `contact.html` — telefoonnummer, Instagram-link, werkgebied
- Vervang de placeholder-vlakken (`placeholder-media`) door echte foto's/video's

## Op GitHub zetten

1. Maak een nieuwe (lege) repository aan op github.com, bijvoorbeeld `sirva-productions`.
2. Volg de instructies van GitHub om deze map als eerste commit te pushen, bijvoorbeeld:

   ```
   git init
   git add .
   git commit -m "Eerste versie website"
   git branch -M main
   git remote add origin https://github.com/<jouw-account>/sirva-productions.git
   git push -u origin main
   ```

## Op Netlify zetten

1. Log in op netlify.com (of maak een account aan — hetzelfde account als voor Sirva Fotografie kan gewoon).
2. Kies "Add new site" → "Import an existing project" → koppel je GitHub-account → kies de repository `sirva-productions`.
3. Er is geen build-commando nodig: laat "Build command" leeg en zet "Publish directory" op `.` (de hoofdmap).
4. Klik op "Deploy". Na een minuut staat de site live op een tijdelijk Netlify-adres.
5. Wil je een eigen domein (bijvoorbeeld sirvaproductions.nl)? Ga naar "Domain settings" in Netlify en volg de stappen om je domein te koppelen.

## Contactformulier

Het formulier op de contactpagina werkt automatisch zodra de site op Netlify staat — Netlify Forms vangt inzendingen op zonder dat er een aparte backend nodig is. Inzendingen zie je terug onder "Forms" in je Netlify-dashboard. Wil je een e-mailnotificatie bij een nieuwe inzending, zet dat aan bij Forms → Settings.

## Later verplaatsen naar een ander account

Dat kan altijd. GitHub heeft een ingebouwde functie om een repository over te dragen naar een ander account (Settings → Danger Zone → Transfer ownership). Netlify koppel je daarna opnieuw aan de verplaatste repository. Je hoeft dus nu niet al te kiezen tussen één of twee accounts.
