# FlowPros website — publiceren op GitHub Pages

## Bestanden
- `index.html` — de volledige site (één pagina)
- `privacy.html` — privacyverklaring
- `voorwaarden.html` — algemene voorwaarden
- `style.css` — vormgeving
- `img/` — hero.webp, michel.webp, logo.webp, logo-wit.webp

## Publiceren
1. Maak een repository aan, bijvoorbeeld `flowpros-site`.
2. Upload alle bestanden in deze map naar de hoofdmap van de repository (dus `index.html` bovenin, niet in een submap).
3. Ga naar **Settings → Pages**, kies bij Source: **Deploy from a branch**, branch `main`, map `/ (root)`. Opslaan.
4. Na een paar minuten staat de site online op `https://<gebruikersnaam>.github.io/flowpros-site/`.

## Eigen domein (www.flowpros.nl)
1. Zet bij je domeinprovider een CNAME-record: `www` → `<gebruikersnaam>.github.io`.
2. Vul in **Settings → Pages → Custom domain** in: `www.flowpros.nl`. GitHub maakt dan zelf een `CNAME`-bestand aan.
3. Zet **Enforce HTTPS** aan zodra het certificaat klaar is (duurt tot een uur).

## Nog te doen
- De algemene voorwaarden zijn de exacte tekst uit `Algemene Voorwaarden FlowPros - mei 2019.pdf` (23 artikelen, ongewijzigd overgenomen). Controleer of dit nog de actuele versie is.
- De privacyverklaring is nieuw geschreven op basis van je bedrijfsgegevens. Laat die nakijken voordat je publiceert.
- Artikel 18 van de voorwaarden verwees naar `flowpros.nl/privacybeleid/`; die link wijst nu naar `privacy.html`.
