# iPod-loggen

Webbapp för att logga iPods jag köper, reparerar, uppgraderar och säljer.
Statisk sida – ingen backend. Data sparas i localStorage, med export/import som backup.

## Köra lokalt
Öppna `index.html` i en webbläsare, eller:
```
npx serve .
```

## Deploya (GitHub + Vercel)
1. Skapa ett nytt repo på GitHub och pusha filerna:
   ```
   git init
   git add .
   git commit -m "iPod-loggen v1"
   git branch -M main
   git remote add origin https://github.com/DITT-ANVÄNDARNAMN/ipod-loggen.git
   git push -u origin main
   ```
2. På vercel.com: **Add New → Project → importera repot**. Inga inställningar behövs (statisk sida). Deploy.
3. Öppna Vercel-URL:en i Safari på mobilen → Dela → **Lägg till på hemskärmen**.
