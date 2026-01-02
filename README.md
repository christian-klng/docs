# Revisory Documentation

Offizielle Dokumentation für [Revisory](https://revisory.ai) – die KI-gestützte Plattform zur Dokumentenanalyse.

## Struktur

```
docs/
├── de/                  # Deutsche Dokumentation
├── en/                  # English Documentation
├── snippets/            # Wiederverwendbare Komponenten
├── images/              # Bilder und Screenshots
├── logo/                # Logos (light/dark)
└── docs.json            # Mintlify-Konfiguration
```

## Lokale Entwicklung

```bash
# Mintlify CLI installieren
npm i -g mint

# Entwicklungsserver starten
mint dev

# Bei Problemen: CLI aktualisieren
mint update
```

Vorschau unter `http://localhost:3000`

## Neue Seite erstellen

1. MDX-Datei im passenden Ordner anlegen (z.B. `de/dokumente/neue-seite.mdx`)
2. Frontmatter hinzufügen:
   ```yaml
   ---
   title: "Seitentitel"
   description: "Kurzbeschreibung"
   ---
   ```
3. Seite in `docs.json` unter der entsprechenden Gruppe eintragen
4. Änderungen committen und pushen → Auto-Deploy

## Deployment

Änderungen auf dem `main`-Branch werden automatisch zu Mintlify deployed.

## Links

- [Revisory App](https://app.revisory.ai)
- [Mintlify Dokumentation](https://mintlify.com/docs)
