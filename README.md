# Praxis-Werkstatt KI: Analysieren

VHS-Tageskurs (9–14 Uhr) für die Verwaltung. Ein durchgehender Fall: Musterstadt, Bürgeranliegen 2025, am Ende eine Entscheidungsvorlage für den Ausschuss. Werkzeuge sind ChatGPT, Mistral Le Chat und Claude, jeweils nur mit kostenlosem Account.

Leitsatz: Die KI bekommt die Beschreibung, der Browser bekommt die Daten. Hochgeladen werden nur anonymisierte beziehungsweise die fiktiven Kursdaten. Die Ampel und die Dienstanweisung gelten.

Kursseite (GitHub Pages): <https://rmdroid.github.io/vhs-werkstatt2/>

## Ordnerstruktur

| Pfad | Zweck |
|---|---|
| `index.html` | Kursseite mit Ablauf, Aufgaben und Downloads |
| `kurs-hero.jpg` | Hero-Bild auf der Kursseite |
| `daten/buergeranliegen.csv`, `.xlsx` | Fiktive Bürgeranliegen Musterstadt 2025 |
| `daten/aufwaermen_mini.csv` | Mini-Tabelle für Station 4 |
| `daten/amtsleiter-mail.txt` | Fiktive Mail für Station 1 |
| `daten/stellungnahme_a.docx`, `.md` | Stellungnahme A (Bürgerinitiative) |
| `daten/stellungnahme_b.docx`, `.md` | Stellungnahme B (Einzelhandelsverband) |
| `daten/ki_ergebnis_fehlerbingo.md`, `.docx` | Plan B der Kursleitung, auf der Kursseite nicht verlinkt |
| `werkzeug/dashboard-prompt.txt` | Prompt für ein lokales HTML-Dashboard |
| `werkzeug/testdaten.csv` | Kleine Testdatei zum Dashboard |
| `werkzeug/buergeranliegen-dashboard.html` | Fertiges lokales Dashboard (Plan B) |
| `bausteine/projektanweisungen/ki-analysieren.txt` | Kurze Projektanweisung (Auswahl und Kurzregeln) |
| `bausteine/projektanweisungen/ki-analysieren.md` | Ausführliche Anweisung für die Projektanlage |
| `bausteine/skills/ki-analysieren.zip` | Derselbe Baustein als Skill-ZIP |
| `bausteine/skills/ki-analysieren/SKILL.md` | Entpackter Skill, im Browser lesbar |
| `screenshots/` | Ältere Stationsbilder, nicht in die Kursseite eingebunden |
| `screenshots2/` | Frame-Bilder eines früheren Boardstands, nicht in die Kursseite eingebunden |

Der aktuelle Baustein heißt `ki-analysieren` (ein Skill, eine kurze TXT, eine ausführliche MD). Beim Start wird gewählt: Auftrag schärfen, Daten auswerten, KI-Ergebnis prüfen oder Werkzeug bauen. Die älteren Einzel-Bausteine bleiben im Ordner, sind auf der Kursseite aber nicht mehr verlinkt.

## Hinweise

- Alle Kursdaten sind fiktiv (Stadt Musterstadt).
- Miro-Board und Teams-Meeting sind auf der Kursseite Platzhalter (`Link folgt`) und werden vor dem Kurs gesetzt.
