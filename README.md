# Kaféhemsidor - övning

Detta är ett projekt för att lära mig hur man skapar enkla hemsidor. Denna prototyp är formad som två enkla hemsidor för ett kafé - en introduktion/menysida och en beställnaingssida.

Lista på tekniker som använts i denna övning:
* HTML
* CSS
* Flexbox
* Grid
* Responsiv design
* Variabler
* Git
* Github

## Senaste uppgiften

### Steg 1. Kontrollera kopplingen

I terminalen: `git remote -v`. Du ska se `origin` med adressen till din fork på GitHub. Det kommer från att du klonade den.

### Steg 2. Kontrollera historiken på GitHub

Öppna din fork på GitHub och klicka *Commits*. Dina commits sedan dag 1 ska synas. Det är samma `git push` som du kört hela tiden. Första gången kan GitHub ha bett dig logga in, och det behövs normalt inte igen.

### Steg 3. Gör en commit och push i ett svep

Ändra något litet, kör `git add .`, `git commit -m "..."` och `git push`. Verifiera på GitHub. Du har nu den vanliga arbetsloopen: ändra, add, commit, push.

### Steg 4. Slå på GitHub Pages

På GitHub, i din fork: *Settings → Pages*. Under *Build and deployment*: Source = *Deploy from a branch*, Branch = `main`, mapp `/ (root)`. Spara. Vänta 1–2 minuter.

### Steg 5. Öppna din sida

Överst på Pages-inställningen visas adressen. Öppna den. Fungerar bilderna och CSS:en? Annars: kontrollera att sökvägarna är relativa (`css/base.css`, inte `/css/base.css`).

### Steg 6. Skriv README

Redigera `README.md`: rubrik, en mening om vad sajten är, länk till live-sidan, och vilka tekniker du använt. Commit, push.

## Kontrollista: så vet du att du är klar

- [ ] `git push` har skickat upp alla dina commits.
- [ ] Din fork har GitHub Pages påslaget, och live-länken fungerar.
- [ ] Bilder och CSS laddas på den publicerade sidan.
- [ ] README.md beskriver projektet och innehåller live-länken.
- [ ] Du har skickat in länken till din fork och din live-länk.

## Tips om du fastnar

- 404 på sidan? Vänta några minuter och kontrollera att filen heter exakt `index.html` i rotmappen.
- Bilderna saknas? Sökvägar får inte börja med `/` och filnamn är känsliga för versaler.
- Repot måste vara publikt för att Pages ska fungera på ett gratiskonto.
- Push avvisas? Kör `git pull` först och försök igen.

## Inlämning

**Deadline: imorgon klockan 09.00.** Allt lämnas in i Microsoft Forms. Du behöver inte redovisa något muntligt.

I formuläret fyller du i:

1. Länk till din fork av det här repot.
2. Reflektion: Klistra in live-länken. Vad var det första du tänkte när du öppnade din publicerade sida?

## Vill du mer? (frivilligt)

- Lägg till en `.gitignore`.
- Lägg till en skärmbild av sidan i README.md.
