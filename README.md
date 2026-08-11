# Prop3rty — export voor GitHub/Vercel

Drie zelfstandige HTML-bestanden, elk werkt los (geen build nodig):

- `index.html` — service-landingspagina (nieuwe, dienstverlening-gerichte homepage)
- `landing-software.html` — oorspronkelijke software/platform-landingspagina
- `portaal.html` — eigenarenportaal (let op: één pandfoto laadt pas als er echte data aan gekoppeld is — in de huidige demo staat daar een placeholder-hole)

## Naar GitHub

1. Maak een nieuwe repo aan op github.com (of gebruik een bestaande).
2. Upload deze drie bestanden (Add file → Upload files) naar de root van de repo, of via git:
   ```
   git init
   git add index.html landing-software.html portaal.html
   git commit -m "Prop3rty export"
   git branch -M main
   git remote add origin <jouw-repo-url>
   git push -u origin main
   ```

## Naar Vercel

1. Ga naar vercel.com → New Project → importeer de GitHub-repo.
2. Geen framework nodig — kies "Other" als framework preset.
3. Deploy. Vercel serveert de HTML-bestanden direct als statische site.
4. `index.html` wordt automatisch de homepage; de andere twee zijn bereikbaar op `/landing-software.html` en `/portaal.html`.
