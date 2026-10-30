# notholt lighting design · Website-Entwurf

Statische Seite, eine Datei (`index.html`), kein Build nötig.

| Datei | Zweck |
|---|---|
| `index.html` | Die komplette Website (HTML, CSS, JS in einer Datei, Logo eingebettet) |
| `img/` | 84 Bilder von notholt.de (1200 x 600, Award-Bilder 2000 x 1000) |
| `.nojekyll` | GitHub Pages liefert die Dateien unverändert aus |

## Lokal öffnen

Doppelklick auf `index.html`. Der Ordner `img/` muss daneben liegen.

## Auf GitHub Pages veröffentlichen

1. Auf github.com ein neues Repository anlegen, z. B. `notholt-website`.
2. "uploading an existing file" wählen und den Inhalt dieses Ordners hochladen (`index.html`, `img/`, `.nojekyll`, `README.md`). Versteckte Dateien im Finder mit `Cmd + Shift + .` einblenden.
3. Commit.
4. Settings → Pages → Source: "Deploy from a branch", Branch `main`, Ordner `/ (root)` → Save.
5. Nach ca. 1 Minute ist die Seite unter `https://<benutzername>.github.io/notholt-website/` erreichbar.

## Schrift

Gotham wird genutzt, wenn sie auf dem Rechner installiert ist. Sonst Montserrat (Google Fonts). Für den Livegang Gotham als Webfont lizenzieren und einbinden.

## Hinweis

Entwurf, nicht öffentlich verlinken. Bilder und Texte stammen von notholt.de.
