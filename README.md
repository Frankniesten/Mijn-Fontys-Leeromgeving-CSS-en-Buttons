# Mijn-Fontys-Leeromgeving-CSS-en-Buttons
Buttons en stylesheets van de mijn Fontys Leeromgeving. Deze code en specifiek gemaakt voor gebruik binnen de SharePoint omgeving van Fontys Hogescholen. Het is echter vrij te gebruiken binnen andere SharePoint omgevingen.

##Requirements
- Code editor bijvoorbeeld NotePad++.
- Toegang tot SharePoint via webdav.
- Download deze repository van Github.

##Kopiëren van de CSS-Style files
- benader de de SharePoint omgeving via WebDav middles een File-client of rechtstreeks via de Windows verkenner.
- Open de map ‘style library’. Deze bevindt zich op het hoogste niveau van de betreffende site collectie.
- Maak in de map ‘style library’ een nieuwe map aan met de naam 'flex'.
- Kopieer de mappen 'ccs' en 'Font' uit de eerder gedownloade repository plaats deze in de map 'flex'.
- Kopieer het URL pad van de css-file. Dit heb je straks nog nodig.

##Inladen van CSS style in SharePoint
- Open het SharePoint in je browser.
- Ga naar ‘site settings’ (hoogste niveau).
- Klik op ‘Master Page’.
- Klik onderaan de pagina op ‘Alternate CSS URL’.
- Selecteer ‘Specify a CSS file to be used by this site and all sites that inherit from it’.
- Vul het pad in naar de CSS file. /instituten/<eigen instituut>/Style Library/flex/css/flex.css
- Klik ‘ok’

##Toevoegen Tiles bestanden aan pagina's
De HTML van de tiles laden we in via een apart .txt bestand wat we opslaan in een document bibliotheek. Vervolgens wordt dit .txt bestand middels de webpart 'inhoudseditor' ingeladen in de betreffende pagina. Het is ook mogelijk om de HTML rechtstreeks in een pagina te plakken. De ervaring is echter dat de SharePoint HTML editor zelf markup aantoevoegd die meestal ervoor zorgt dat zaken stuk gaan.

###Opslaan van tiles.txt
- Ga naar de betreffende site waar de hoofdnavigatie moet komen.
- Maak binnen deze site een nieuwe document library aan en noem deze ‘tiles’.
- Voeg de drie .txt bestanden uit de gedownloade map 'tiles' toe aan de document library tiles.

###Tiles zichtbaar maken in Front-end
- Ga naar de betreffende portal pagina.
- Zorg dat de pagina indeling staat op Fontys Webpart 
- Klik ‘edit page’
- Voeg een nieuw webpart toe onder koptekst.
- Kies webpart ‘media en inhoud > inhoudseditor’
- Klik op webonderdeel bewerken.
- Vul in het vak koppeling naar inhoud de url van de file tiles.txt in
-Zet de titel van de webpart uit
- klik op toepassen.
- Sla de pagina op.

##Leeractiviteiten pagina toevoegen
De knop leeractiviteiten op de hoofdnavigatie pagina moet doorlinken naar een tweede SharePoint pagina. Waar vervolgens een apart script wordt geladen.

- Kies uit het edit menu ‘pagina toevoegen’ en noem deze leeractiviteiten.
- Zorg dat de pagina indeling staat op Fontys Webpart 
- Klik ‘edit page’
- Voeg een nieuw webpart toe onder koptekst.
- Kies webpart ‘media en inhoud > inhoudseditor’
- Klik op webonderdeel bewerken.
- Vul in het vak koppeling naar inhoud de url van de file leeractiviteiten.txt in
- Zet de titel van de webpart uit
- klik op toepassen.
- Sla de pagina op.

##Mijn Portfolio pagina toevoegen
De knop ‘mijn portfolio’ op de hoofdnavigatie pagina moet doorlinken naar een tweede SharePoint pagina. Waar vervolgens een apart script wordt geladen.

- Kies uit het edit menu ‘pagina toevoegen’ en noem deze mijn ‘portfolio’.
- Zorg dat de pagina indeling staat op Fontys Webpart 
- Klik ‘edit page’
- Voeg een nieuw webpart toe onder koptekst.
- Kies webpart ‘media en inhoud > inhoudseditor’
- Klik op webonderdeel bewerken.
- Vul in het vak koppeling naar inhoud de url van de file portfolio.txt in
- Zet de titel van de webpart uit
- Klik op toepassen.
- Sla de pagina op

##Doorlinken Hoofdnavigatie
Pas de betreffende URL’s van de hoofdpagina navigatie aan zodat deze doorlinken naar de betreffende subpagina’s die eerder aangemaakt zijn of naar de betreffende toepassingen.

<<<<<<< HEAD
=======
##Requirements
- Code editor bijvoorbeeld NotePad++
- Toegang tot SharePoint via webdav
>>>>>>> 50cf9a97011e19e7e151ebaa70e28e5ecf7a14fd

