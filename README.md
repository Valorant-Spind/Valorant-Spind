<div align="center">

# Valorant-Spind

**Wie viel ist dein Valorant-Account eigentlich wert?**

Ein kostenloses Windows-Tool, das deinen Skin-Inventarwert berechnet,
deine Matches auswertet und dir sagt, woran du wirklich arbeiten musst.

[![Download](https://img.shields.io/badge/Download-itch.io-fa5c5c?style=for-the-badge&logo=itchdotio&logoColor=white)](https://noaimonlyspray.itch.io/valorant-spind)
[![Website](https://img.shields.io/badge/Website-valorant--spind.de-53a8b6?style=for-the-badge)](https://www.valorant-spind.de)
[![Version](https://img.shields.io/badge/Version-1.4-brightgreen?style=for-the-badge)](#changelog)

*Der Download läuft ausschließlich über itch.io. Dieses Repository dient
als Übersicht, Changelog und Anlaufstelle für Fehlermeldungen.*

</div>

---

## Screenshots

<!-- TODO Marc: Bilder in einen Ordner /docs legen und hier verlinken.
     Empfohlene Reihenfolge - der Inventarwert zuerst, der zieht am meisten. -->

| Inventarwert | Kill-Heatmap |
|:---:|:---:|
| ![Inventarwert](docs/inventarwert.png) | ![Heatmap](docs/heatmap.png) |

| Coach | Achievements |
|:---:|:---:|
| ![Coach](docs/coach.png) | ![Achievements](docs/achievements.png) |

---

## Was die App kann

### Inventarwert
Valorant-Spind liest dein Inventar aus dem lokalen Client und rechnet
zusammen, was deine Skins gekostet haben. Waffenskins, Messer, Bundles,
Battlepass-Inhalte. Das Ergebnis in Euro, auf den Cent genau.

### Coach
<!-- TODO Marc: Hier bitte 2-3 echte Beispielausgaben einsetzen.
     Das ist dein wichtigstes Alleinstellungsmerkmal - je konkreter, desto besser. -->
Andere Tools zeigen dir Zahlen. Der Coach sagt dir, was du damit
anfangen sollst: konkrete Hinweise auf wiederkehrende Muster in deinen
Matches, statt einer weiteren Statistik zum Selberdeuten.

### Kill-Heatmap
Wo fallen deine Kills, wo stirbst du? Die Heatmap legt beides auf die
Map und macht Gewohnheiten sichtbar, die dir im Spiel nicht auffallen.

### Match-Statistiken
Detaillierte Auswertung deiner letzten Matches: Trefferquote,
Kopfschuss-Anteil, Economy, Performance pro Agent und pro Map.

### Achievements
Über einhundert Erfolge zum Freischalten. Manche ernst gemeint,
manche weniger.

---

## Installation

1. [Auf itch.io herunterladen](https://noaimonlyspray.itch.io/valorant-spind)
2. ZIP entpacken
3. `Valorant-Spind.exe` starten
4. Valorant-Client öffnen, fertig

Keine Installation, keine Registrierung, kein Account nötig.

**Systemvoraussetzungen:** Windows 10 oder 11, installierter
Valorant-Client. Sprache aktuell Deutsch.

---

## Häufige Fragen

<details>
<summary><b>Ist das erlaubt? Riskiere ich einen Ban?</b></summary>

Valorant-Spind liest ausschließlich Daten, die der Valorant-Client
lokal bereitstellt. Es wird nichts in das Spiel injiziert, nichts
verändert und nichts automatisiert. Die App greift nicht in den
laufenden Spielprozess ein.

</details>

<details>
<summary><b>Windows warnt vor der Datei. Ist das ein Virus?</b></summary>

Nein. Die App ist mit PyInstaller gepackt, und Windows SmartScreen
sowie manche Virenscanner schlagen bei solchen Dateien grundsätzlich
an, solange sie kein gekauftes Code-Signing-Zertifikat haben. Das ist
ein bekanntes Problem aller kleinen Windows-Tools.

Bei SmartScreen: "Weitere Informationen" anklicken, dann "Trotzdem
ausführen".

</details>

<details>
<summary><b>Warum ist der Quellcode nicht hier?</b></summary>

Valorant-Spind ist Closed Source. Dieses Repository ist bewusst nur
Schaufenster, Changelog und Bugtracker. Der Download läuft über itch.io.

</details>

<details>
<summary><b>Werden meine Daten irgendwohin gesendet?</b></summary>

<!-- TODO Marc: Bitte präzise und wahrheitsgemäß ausfüllen.
     Falls der Update-Checker den GitHub-Gist abruft, gehört das hier hin.
     Datenschutz ist bei Drittanbieter-Tools DAS Vertrauensthema. -->

</details>

<details>
<summary><b>Kostet die App etwas?</b></summary>

Nein. Valorant-Spind ist kostenlos.

</details>

---

## Fehler gefunden?

Bitte über den [Issues-Tab](../../issues) melden. Hilfreich sind:

- Was du gemacht hast, als der Fehler auftrat
- Die Version der App
- Ein Screenshot, falls möglich

---

## Changelog

### v1.4
- Achievement-System mit über hundert Erfolgen
- Kill-Heatmap
- Neue Statistik-Karten
- Vollständige Preisdaten für Messer-Skins
- Automatische Update-Prüfung beim Start

<!-- TODO Marc: ältere Versionen ergänzen, falls du sie noch hast -->

---

## Rechtliches

Valorant-Spind ist ein inoffizielles Fan-Projekt und steht in keiner
Verbindung zu Riot Games. Valorant und Riot Games sind Marken oder
eingetragene Marken der Riot Games, Inc.

---

<div align="center">

**[⬇ Jetzt herunterladen](https://noaimonlyspray.itch.io/valorant-spind)**

Entwickelt von NoAimOnlySpray · [www.valorant-spind.de](https://www.valorant-spind.de)

</div>
