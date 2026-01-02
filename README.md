# Revisory Documentation

Die offizielle Dokumentation für [Revisory](https://revisory.ai) – KI-gestützte Dokumentenanalyse.

## Struktur

```
docs/
├── de/                    # Deutsche Dokumentation
│   ├── erste-schritte/    # Schnelleinstieg
│   ├── dokumente/         # Dokumentenmanagement
│   ├── analysen/          # Bewertungen & Ergebnisse
│   ├── organisation/      # Team & Einstellungen
│   ├── konto/             # Persönliche Einstellungen
│   ├── datenschutz/       # Daten & Sicherheit
│   └── hilfe/             # Fehlerbehebung
│
├── en/                    # English Documentation
│   ├── getting-started/
│   ├── documents/
│   ├── analyses/
│   ├── organization/
│   ├── account/
│   ├── privacy/
│   └── help/
│
├── docs.json              # Mintlify Konfiguration
└── images/                # Bilder
```

## Deployment

Änderungen auf dem `main` Branch werden automatisch deployed.

## Neue Seite hinzufügen

1. MDX-Datei im passenden Ordner erstellen
2. Frontmatter hinzufügen:
   ```yaml
   ---
   title: "Titel"
   description: "Beschreibung"
   icon: "icon-name"
   ---
   ```
3. Sprachlink zur Gegenseite einfügen
4. In `docs.json` unter der passenden Gruppe registrieren

## Ressourcen

- [Mintlify Dokumentation](https://mintlify.com/docs)
- [Font Awesome Icons](https://fontawesome.com/icons)
