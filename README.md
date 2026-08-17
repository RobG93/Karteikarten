# DevCards – Karteikarten für Software Engineering

Eine selbstständige Web-App zum Lernen von Softwareentwicklung – vom ersten Schritt bis
Cloud Engineering und KI-Entwicklung. Kein Server, kein Framework, keine Installation:
alles läuft in `index.html` im Browser, Fortschritt wird lokal auf dem Gerät gespeichert.

## Live-Version

Nach Aktivierung von GitHub Pages (Settings → Pages → Deploy from branch → `main` → `/ (root)`)
erreichbar unter:

`https://<dein-github-nutzername>.github.io/Karteikarten/`

## Inhalt

259 Karteikarten in 37 Themen, verteilt auf 6 Stufen:

1. **Einsteiger** – Grundbegriffe, Variablen, Kontrollstrukturen, Funktionen, Arrays, Debugging
2. **Fortgeschritten** – OOP, Datenstrukturen, Algorithmen/Big O, Rekursion, Git, Fehlerbehandlung
3. **Professionell** – Clean Code/SOLID, Design Patterns, Testing, SQL, REST-APIs, Agile
4. **Cloud & DevOps** – Netzwerke, Docker, CI/CD, AWS/Azure/GCP, Kubernetes, IaC, Security
5. **Experte (KI)** – ML-Grundlagen, Neuronale Netze, LLMs/Transformer, Prompt Engineering/RAG,
   Embeddings, Agentic AI/MCP, MLOps
6. **Glossar** – 35 reine Begriffsdefinitionen (Karte zeigt nur den Fachbegriff, z. B. "Array"), quer
   über alle Themengebiete, zum schnellen Auffrischen von Vokabular

## Lernmethode

Basierend auf aktueller Lernforschung:

- **Multiple-Choice mit 4 Antwortoptionen** pro Karte (1 richtig, 3 fest hinterlegte Ablenker aus
  demselben Themengebiet) – nutzt den Testing-Effekt, ohne auf dem Handy Freitext eintippen zu müssen.
  Die Ablenker sind bewusst thematisch ähnlich zur richtigen Antwort gewählt, nicht zufällig aus dem
  gesamten Kartenstapel, damit die Auswahl echtes Verständnis statt Ausschlussverfahren erfordert.
- **SM-2 Spaced Repetition** – die Bewertung ergibt sich automatisch aus richtig/falsch; Karten werden
  kurz vor dem vermuteten Vergessen erneut abgefragt
- **Interleaving** – fällige Karten werden themenübergreifend gemischt statt blockweise gelernt
- **Tageslimit für neue Karten** (einstellbar) gegen kognitive Überlastung
- Sofortige Wiedervorlage bei falscher Antwort innerhalb derselben Session

## Nutzung auf dem iPhone

1. Seite in Safari öffnen (lokale Datei über Dateien-App/iCloud Drive, oder die GitHub-Pages-URL)
2. Teilen-Symbol → **Zum Home-Bildschirm**
3. Danach startet die App wie eine eigene App, offline nutzbar

## Lokal testen

Einfach `index.html` per Doppelklick im Browser öffnen, oder mit einem simplen lokalen Server:

```bash
python -m http.server 8934
```

und `http://localhost:8934` aufrufen.
