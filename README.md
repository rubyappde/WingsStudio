# Wings Studio – Website

Statische Website für GitHub Pages im Farbstil „Pixel-Flügel in Minze“
(Graphit #0F172A · Minze #10B981 · Hellminze #6EE7B7 · Nebel #F1F5F9).

## Inhalt

| Datei | Zweck |
| --- | --- |
| `index.html` | Startseite: Leistungen, Ablauf, Ruby-Vorschau, Über, Kontakt |
| `projekte.html` | Reiter „Projekte“ mit Ruby und Bildergalerie |
| `impressum.html` | Impressum (Platzhalter ausfüllen!) |
| `datenschutz.html` | Datenschutzerklärung (Vorlage) |
| `assets/css/style.css` | Alle Farben und Layouts |
| `assets/img/` | Logo, Favicon, Ruby-Bilder |

## Vor dem Veröffentlichen ausfüllen

- [ ] `kontakt@deine-domain.de` durch deine echte E-Mail ersetzen (index, impressum, datenschutz)
- [ ] Anschrift `[Straße Hausnummer]`, `[PLZ Ort]` in Impressum und Datenschutz eintragen

## Ruby-Bilder

Die Screenshots liegen in `assets/img/` (`ruby-gruppen.jpg`, `ruby-kalender.jpg`,
`ruby-treffen.jpg`). Für neue Screenshots einfach eine Datei mit gleichem Namen ersetzen.

## Auf GitHub Pages veröffentlichen

1. Auf github.com ein neues Repository anlegen, z. B. `wings-studio` (Public).
2. „Add file → Upload files“: den **Inhalt** dieses Ordners hochladen (nicht den Ordner selbst), dann „Commit changes“.
3. Im Repository: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, Branch `main`, Ordner `/ (root)`, „Save“.
4. Nach 1–2 Minuten ist die Seite unter `https://<dein-github-name>.github.io/wings-studio/` erreichbar.

Eigene Domain später: In Settings → Pages unter „Custom domain“ eintragen und beim Domain-Anbieter die DNS-Einträge setzen, die GitHub dort anzeigt.
