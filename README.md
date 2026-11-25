# Sofia Kammarkör

En första version av en enkel hemsida för Sofia Kammarkör. Sidan består av en enda sida med avsnitten Aktuellt, Om oss och Kontakt.

## Förhandsgranska i webbläsaren

**[Öppna hemsidan](https://jacobingvarsson.github.io/sofia-kammarkor/)**

Länken är offentlig och kräver varken GitHub-konto, nedladdning eller VS Code. Det är ett preliminärt designutkast med exempelbild och platshållartexter.

Förhandsvisningen publiceras via GitHub Pages från `main` och uppdateras automatiskt efter att ändringar har sparats där. Publiceringen kan ta några minuter.

## Öppna och ändra sidan lokalt

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

GitHub Pages visar den senaste publicerade versionen från `main`. Ändringar i en annan branch syns först när de har slagits ihop till `main`.

Den tidigare privata förhandsvisningen i Sites uppdateras separat och följer inte ändringarna i detta repository.

`index.html` i projektets rot leder besökaren till den riktiga sidan i `dist/`. Filen `.nojekyll` gör att GitHub Pages publicerar filerna utan Jekyll-bearbetning. Publiceringskälla under **Settings → Pages**: `main`, `/ (root)`.
