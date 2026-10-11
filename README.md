# Banana OD

**Eine lokale Windows-Arbeitsumgebung für KI-Chat, Agenten, Werkzeuge und Projekte.**

Banana OD verbindet normale KI-Unterhaltungen mit praktischer Arbeit auf dem eigenen PC. Modelle können – innerhalb der erlaubten Bereiche – Dateien bearbeiten, Terminalbefehle ausführen, MCP-Dienste verwenden, Skills laden und größere Aufgaben in kontrollierte Schritte aufteilen.

<p align="center">
  <a href="#was-banana-od-kann">Funktionen</a> ·
  <a href="#schnellstart">Schnellstart</a> ·
  <a href="https://lokitheloki.github.io/banana-od/">Infoseite</a> ·
  <a href="https://github.com/lokitheloki/banana-od/releases">Releases</a>
</p>

<p align="center">
  <img src="assets/banana-od-app.png" width="1280" alt="Banana OD in einem Windows-Fenster mit Chat-Eingabe und Navigation für Tools, Banana Control, Kalender, Recherche, Galerie, Notizen und Aufgaben.">
</p>

> Der Screenshot stammt aus einer sauberen lokalen Demo-Umgebung und enthält keine privaten Chats, Konten oder Zugangsdaten.

## Was Banana OD kann

- **Chat und Agenten** – von einer normalen Antwort bis zu mehrstufigen Aufgaben mit klaren Zuständigkeiten.
- **Lokale und Cloud-Modelle** – Auswahl nach Aufgabe, Leistung, Datenschutz und Kosten.
- **Dateien, Terminal, MCP und Skills** – die KI kann innerhalb freigegebener Bereiche praktisch arbeiten.
- **Banana Control und AI-Hub** – Projekte, Aufgaben, Dienste und lokale Laufzeiten an einem Ort.
- **Recherche und Arbeitsbereiche** – Dokumente, Notizen, Kalender, E-Mail-Entwürfe, Galerie und weitere Werkzeuge.
- **Kontrollierte Rechte** – Desktop Bridge und Agent Council bleiben begrenzt, protokolliert und bei riskanten Aktionen freigabepflichtig.

## Geprüfter Stand

| Bereich | Stand |
| --- | --- |
| Release | Der erste öffentliche geprüfte Stand erscheint unter [Releases](https://github.com/lokitheloki/banana-od/releases) |
| Plattform | Windows, lokale Desktop-App |
| Pakete | Installer und portable Version in Vorbereitung |
| App-Adresse | `http://127.0.0.1:7100/` |
| Qualität | Automatisierte Tests und Funktionsprüfungen vor jedem veröffentlichten Stand |
| Beenden | Das Schließen des App-Fensters beendet auch den lokalen Dienst |

> Bis zum ersten öffentlichen Release enthält dieses Repository bewusst keinen Download. Ungeprüfte Entwicklungsstände bleiben privat.

## Schnellstart

1. Sobald verfügbar, den neuesten öffentlichen Stand unter [Releases](https://github.com/lokitheloki/banana-od/releases) öffnen.
2. Installer oder portable Version herunterladen.
3. Banana OD starten und beim ersten Start das lokale Administratorkonto anlegen.
4. Die gewünschten Modelle und Werkzeuge in den Einstellungen verbinden.

Die App öffnet Banana OD in einem eigenen Fenster. Ein zusätzlicher Browser-Tab ist für die normale Nutzung nicht nötig.

## Idee: Modell-Personen

Geplant ist ein kostenbewusstes Routing mit unterschiedlichen Rollen:

- **Leiter** – ein starkes Modell plant, entscheidet und prüft schwierige Aufgaben.
- **Arbeiter** – ein mittleres oder lokales Modell erledigt klar abgegrenzte Arbeitsschritte.
- **Bote** – ein kleines, dauerhaft verfügbares Modell beantwortet einfache Statusfragen und überwacht Fortsetzungen.

Der vorbereitete Shadow-Router beobachtet zunächst nur, welche Rolle geeignet wäre. Eine automatische Weiterleitung wird erst nach ausreichenden Vergleichstests aktiviert.

## Sicherheit

Banana OD kann mächtige lokale Werkzeuge verwenden. Deshalb gilt:

- Rechte werden passend zur Aufgabe begrenzt.
- Zugangsdaten und private Daten gehören nicht ins Git-Repository.
- Netzwerkzugriff und riskante Desktop-Aktionen benötigen klare Kontrolle.
- Für eine im Netzwerk erreichbare Installation bleibt die Anmeldung aktiviert.

## Projekt und Mitwirkung

- Die ausführlichere Präsentation ist auf der [Banana-OD-Website](https://lokitheloki.github.io/banana-od/) verfügbar.
- Technische Dokumentation und Entwicklungshinweise werden mit den öffentlichen Releases ergänzt.

## Herkunft und Lizenz

Banana OD baut auf [Odysseus](https://github.com/odysseus-dev/odysseus) auf und entwickelt die lokale Windows-Nutzung, kontrollierte Agentenarbeit und die AI-Hub-Integration weiter.

Lizenz: **AGPL-3.0-or-later** – siehe [LICENSE](LICENSE). Jeder veröffentlichte Programmstand wird zusammen mit dem dazugehörigen Quellcode bereitgestellt.
