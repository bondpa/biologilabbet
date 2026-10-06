# Biologilabbet

Mobilanpassad studieapp på svenska för evolution och ekosystem.

**Öppna appen:** https://bondpa.github.io/biologilabbet/

- 8 områden och 49 korta läsdelar.
- 83 flervalsfrågor med förklaringar och repetition av felsvar.
- Övningsprov: 16 frågor, två från varje område, rättning på slutet.
- 40 begrepp med sökning och vändkort.
- 8 resonemangsfrågor med lokal anteckning, stödpunkter och exempelsvar.
- Interaktiva modeller av naturligt urval och en näringskedja.
- Framsteg sparas i webbläsarens localStorage. Inga elevkonton, ingen egen analys och ingen serverdatabas.

## Material

Nyskrivna förklaringar utifrån inskickade sidor ur Helios NO, kapitlet Evolution och ekosystem (elevboken s. 10–35, tillhörande övningsuppgifter och begreppsblad). Originalfotografier och handskrivna elevsvar publiceras inte. Tidsangivelser är ungefärliga. Externa faktakällor finns under ”Om appen”.

## Kör lokalt

Ingen installation eller byggprocess behövs. Servera katalogen med valfri statisk webbserver, till exempel:

```sh
python3 -m http.server 8765
```

Öppna sedan http://localhost:8765. GitHub Pages publicerar `main` från repositoryns rot.

`data.js` innehåller studiematerialet. `app.js` innehåller gränssnitt och övningar. `style.css` styr mobil- och datorvyn. Alla resurser är lokala; appen kräver inga externa skript eller typsnitt.

## Validering

Innehållets struktur, unika fråge-id:n, täckning av alla områden i övningsprovet, rättning och repetitionsurval har kontrollerats. Träningspass och övningsprov har körts i webbläsare tillsammans med mobilvy, omladdning, begreppskort, anteckningar och interaktiva övningar.
