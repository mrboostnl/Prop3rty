# Prop3rty — export voor GitHub / Vercel / Netlify

Statische site, geen build nodig. `index.html` is de homepage.

## Pagina's
- `index.html` — homepage (service-landing)
- `diensten.html`, `platform.html`, `tarieven.html`, `over-ons.html`, `contact.html`
- `portaal.html` — eigenarenportaal
- `404.html` — foutpagina
- `landing-alt.html` — oudere software-landingspagina (optioneel, nergens gelinkt)
- `assets/` — afbeeldingen, logo's en favicon (verplicht mee-uploaden)

## Naar GitHub
1. Maak een repo aan op github.com.
2. Upload de VOLLEDIGE inhoud van deze map (incl. de map `assets/`) naar de root, of via git:
   ```
   git init
   git add .
   git commit -m "Prop3rty site"
   git branch -M main
   git remote add origin <jouw-repo-url>
   git push -u origin main
   ```

## Hosten
- **GitHub Pages**: repo → Settings → Pages → deploy from branch `main` / root.
- **Vercel/Netlify**: importeer de repo, framework "Other", deploy.

`index.html` wordt automatisch de homepage.
