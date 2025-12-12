# 🎄 Julklapp Escape Room

En interaktiv escape room-webbapp som julklapp, byggd med HTML, CSS och JavaScript.

## 🚀 Deployment på Vercel

Detta projekt är konfigurerat för automatisk deployment till Vercel via GitHub.

### Steg för att sätta upp:

1. **Skapa ett nytt repository på GitHub**
   - Gå till [GitHub](https://github.com/new)
   - Skapa ett nytt repository (t.ex. "julklapp-escape-room")
   - **Viktigt:** Välj inte "Initialize with README" eftersom vi redan har filer

2. **Koppla ditt lokala repository till GitHub**
   ```bash
   git remote add origin https://github.com/DITT-ANVÄNDARNAMN/julklapp-escape-room.git
   git branch -M main
   git push -u origin main
   ```

3. **Deploya till Vercel**
   - Gå till [Vercel](https://vercel.com)
   - Logga in med ditt GitHub-konto
   - Klicka på "Add New Project"
   - Välj ditt repository "julklapp-escape-room"
   - Vercel kommer automatiskt upptäcka att det är en statisk webbplats
   - Klicka på "Deploy"

4. **Automatisk deployment**
   - Varje gång du pushar till GitHub kommer Vercel automatiskt att deploya den nya versionen
   - Du kan se deployment-status i Vercel dashboard

### Lokal utveckling

Öppna bara `index.html` i din webbläsare, eller använd en lokal server:

```bash
# Med Python
python -m http.server 8000

# Med Node.js (om du har http-server installerat)
npx http-server
```

Sedan öppna `http://localhost:8000` i webbläsaren.

## 📝 Struktur

- `index.html` - All kod (HTML, CSS, JavaScript) i en fil
- `.gitignore` - Filer som ska ignoreras av Git
- `README.md` - Denna fil

## 🎮 Funktioner

- 5 olika pusseltyper
- Progress sparas i localStorage
- 2-stegs ledtrådar
- Admin/debug-panel (klicka på titeln 7 gånger)
- Mobilvänlig design
- Mörkt juligt tema

## 🔧 Konfiguration

Alla svar och konstanter finns i `CONFIG`-objektet högst upp i JavaScript-sektionen i `index.html`.

