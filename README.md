# dogemotions-sitemap

Dieses Repository stellt eine öffentlich erreichbare `sitemap.xml` über **GitHub Pages** bereit,
damit Google & Co. deine Adobe-Portfolio-Seite crawlen können.

---

## 📦 Inhalt
- `sitemap.xml` – die eigentliche Sitemap (bereits erzeugt)
- `.nojekyll` – verhindert, dass GitHub Pages Dateien „versteckt“
- `index.html` – kleine Info-/Testseite mit Link zur Sitemap

> Hinweis: Die URLs in `sitemap.xml` zeigen auf **https://dogemotions.de/**.
> Du kannst diese Datei jederzeit ersetzen oder aktualisieren.

---

## 🚀 Veröffentlichung mit GitHub Pages

1. **Repository anlegen (public)**
2. **Dateien hochladen** (diese ZIP entpacken und gesamten Ordnerinhalt hochladen)
3. **GitHub Pages aktivieren:**  
   - Settings → Pages  
   - Source: `main`  
   - Folder: `/ (root)`  
   - Save
4. **Deine URL prüfen:**  
   - `https://<DEIN_USERNAME>.github.io/dogemotions-sitemap/`  
   - `https://<DEIN_USERNAME>.github.io/dogemotions-sitemap/sitemap.xml`

---

## 🧭 Google Search Console

1. Öffne Search Console → *dogemotions.de* auswählen
2. Links **„Sitemaps“** → folgende URL eintragen:
   ```
   https://<DEIN_USERNAME>.github.io/dogemotions-sitemap/sitemap.xml
   ```
3. **Senden** – fertig ✅

---

## 🔁 Aktualisieren der Sitemap

Wenn du neue Seiten hast:
1. `sitemap.xml` lokal aktualisieren/neu generieren
2. Im Repo ersetzen
3. Commit → GitHub Pages aktualisiert automatisch

Viel Erfolg! 💪
