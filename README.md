# locl Website – Screenshot-Anleitung

## 📸 Screenshot einbinden

Der Screenshot ist bereits in die Website integriert!

### Was du jetzt tun musst:

1. **Speichere den Screenshot** aus dem Chat/Projekt als PNG-Datei
2. **Benenne ihn um** zu: `app-screenshot.png`
3. **Platziere ihn** im Ordner: `/assets/`

```
locl_website/
├── assets/
│   └── app-screenshot.png  ← Hier den Screenshot speichern
├── index.html
├── support/
└── privacy/
```

### Alternative:

Wenn du den Screenshot anders benennen oder platzieren möchtest, ändere in `index.html` Zeile 77:

```html
<img src="assets/app-screenshot.png" alt="locl App Screenshot" class="w-full rounded-3xl shadow-2xl">
```

zu deinem Pfad, z.B.:
```html
<img src="bilder/mein-screenshot.png" alt="locl App Screenshot" class="w-full rounded-3xl shadow-2xl">
```

---

## ✅ Content-Updates

Basierend auf deinem Screenshot wurden folgende Anpassungen vorgenommen:

### Hero-Section:
- **H1:** "Spots in deiner Nähe" (statt "Entdecke relevante Spots...")
- **Subline:** "Kuratierte Highlights – lokale Cafés, Events und mehr."

### Visual Section:
- Screenshot-Integration statt Placeholder
- Kategorien angepasst auf "Cafés" und "Schnell was essen"

### Features:
- Feature 3 geändert zu "Events & Highlights" (passend zum Screenshot)
- Text angepasst auf "von LocalSpots" (wie in der App sichtbar)

### How it works:
- Step 3 angepasst: "Stream öffnen" statt "Losgehen"
- Begriffe aus der App übernommen (Stream, Deutschland-Beispiel)

---

## 🚀 Deployment

Die Website ist fertig für:
- Netlify
- Vercel
- GitHub Pages
- Jeden anderen Static Hosting Service

Das Formular funktioniert automatisch auf Netlify (data-netlify="true").

