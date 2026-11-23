# Sofia Kammarkör

En första version av en enkel hemsida för Sofia Kammarkör. Sidan består av en enda sida med avsnitten Aktuellt, Om oss och Kontakt.

## Öppna sidan

1. Ladda ner projektet med **Code → Download ZIP** på GitHub och packa upp filen, eller klona projektet med Git.
2. Öppna projektmappen i VS Code.
3. Dubbelklicka på `dist/index.html` för att visa sidan i webbläsaren.

Inga paket eller installationer behövs. Spara en ändring i VS Code och uppdatera webbläsaren för att se den.

## Filer

```text
dist/
├── index.html          Sidans innehåll och struktur
├── style.css           Färger, typsnitt, layout och mobilanpassning
└── bilder/
    └── korbild.png     Tillfällig AI-genererad exempelbild
```

Ändra texter och länkar i `dist/index.html`. Färgerna är samlade överst i `dist/style.css` under `:root`.

## Status

- Det här är ett designutkast, inte en färdig officiell hemsida.
- Körbilden är AI-genererad och föreställer inte Sofia Kammarkör.
- Slogan och presentation är förslag; konsertuppgifter och kontaktadress återstår.
- Menyn går till avsnitten på sidan. Konsertinformationen kan fällas ut.
- Sidan har CSS för både mobil och dator.
- CMS är ännu inte anslutet. Innehållet ändras tills vidare direkt i HTML-filen.

## Arbeta tillsammans

Skapa gärna en issue för förslag eller fel. Gör kodändringar i en egen branch och öppna en pull request, så kan ändringarna granskas innan de läggs in i `main`.

GitHub-projektet är en separat kopia av utkastets källkod. Att pusha hit uppdaterar inte automatiskt den tidigare privata förhandsvisningen. Publicering eller automatisk driftsättning kan kopplas på senare.
