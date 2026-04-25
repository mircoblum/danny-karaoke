# Danny-Karaoke online stellen – Schritt für Schritt

## 🚀 Variante 1: GitHub Pages (Empfehlung)

**Vorteile:** Kostenlos, eigene URL, dauerhaft, schnell, keine Werbung

### Schritt 1: GitHub-Account
1. github.com → "Sign up"
2. Username, E-Mail, Passwort
3. Bestätigungs-Mail klicken

### Schritt 2: Repository anlegen
1. Oben rechts auf "+" → "New repository"
2. Repository name: `danny-karaoke`
3. **Public** auswählen (wichtig für GitHub Pages gratis!)
4. "Create repository"

### Schritt 3: Dateien hochladen
1. Im neuen Repo: "uploading an existing file"
   (oder "Add file" → "Upload files")
2. Diese beiden Dateien per Drag & Drop reinziehen:
   - `index.html`  ← (das ist deine danny-karaoke.html, einfach umbenennen!)
   - `danny.m4a`   ← (deine fertige MP3, EXAKT diesen Namen verwenden!)
3. Unten: "Commit changes"

### Schritt 4: GitHub Pages aktivieren
1. Im Repo: Tab "Settings" (oben rechts)
2. Links im Menü: "Pages"
3. Bei "Source": "Deploy from a branch"
4. Branch: `main`, Folder: `/ (root)`
5. "Save"
6. ⏱️ 1-2 Minuten warten
7. Oben erscheint: "Your site is live at https://DEIN-USERNAME.github.io/danny-karaoke/"

### Schritt 5: Aufrufen!
- Link funktioniert auf jedem Gerät weltweit
- Auf der Feier einfach im Browser öffnen → F11 für Vollbild → "Abspielen & Starten"

---

## 🌐 Variante 2: Netlify Drop (am schnellsten, ohne Account)

1. netlify.com/drop öffnen
2. Beide Dateien (`index.html` + `danny.m4a`) in den großen Drop-Bereich ziehen
3. ⏱️ 30 Sekunden warten
4. Zufällige URL erscheint, z.B. `https://wonderful-pony-12345.netlify.app`
5. Fertig!

**Nachteil:** URL ist hässlich, Site verschwindet nach 7 Tagen ohne Account

---

## 📁 Dateinamen WICHTIG

In der HTML steht: `src="danny.m4a"`

Deine MP3 MUSS genau so heißen: **`danny.m4a`**

Falls deine M4A-Datei anders heißt:
- Entweder: M4A umbenennen zu `danny.m4a`
- Oder: in der HTML den Dateinamen anpassen (Suche `danny.m4a`, ersetzen)

---

## 🎬 Auf der Feier nutzen

1. Laptop an TV/Beamer anschließen
2. Browser öffnen → deine URL eingeben
3. **F11** für Vollbild
4. **"Abspielen & Starten"** klicken
5. 🎤 Mitsingen!

**Tipp:** Vorher zuhause testen! Bei langsamer Internetverbindung lieber auf der Feier vorab laden.

---

## ❓ Fragen zur Auswahl?

| Aspekt | GitHub Pages | Netlify Drop |
|--------|-------------|--------------|
| Account nötig | ✓ | ✗ |
| Dauer | dauerhaft | 7 Tage |
| URL | schön | zufällig |
| Setup | 10 Min | 1 Min |
| Kostenlos | ✓ | ✓ |

Für eine Feier reicht **Netlify Drop** völlig. Für was Dauerhaftes (z.B. um es Familie/Freunden zu schicken) → **GitHub Pages**.
