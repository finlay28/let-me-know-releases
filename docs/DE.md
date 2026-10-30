# Let Me Know

**Deine KI arbeitet. Du musst nicht ständig auf den Chat schauen.**

Let Me Know ist eine macOS-Menüleisten-App für Codex und Claude Code. Sie meldet per eigenem Banner und Sound, wenn eine Antwort fertig ist oder deine Eingabe gebraucht wird.

[DMG herunterladen · 0.9.0 Preview](https://github.com/finlay28/let-me-know-releases/releases/download/v0.9.0/Let-Me-Know-0.9.0.dmg)

## Funktionen

- Unterschiedliche Sounds für fertige Antworten und offene Fragen; global oder pro Anbieter.
- Eigene Sounds importieren, benennen und per Wellenform zuschneiden.
- Optional andere Audios sanft absenken und anschließend wiederherstellen.
- Unterstützte lokale Profile erkennen, darunter Codex-Profile aus Layers.
- Projekt und Chat im Banner erkennen und unterstützte Chats per Klick öffnen.
- Einstellungen, Verbindungen, Verlauf und Autostart über die Menüleiste verwalten.

Normale ChatGPT- und Claude-Chats sind noch nicht enthalten. Die App ist unabhängig von OpenAI und Anthropic.

## Installation

1. DMG öffnen und **Let Me Know** nach **Applications / Programme** ziehen.
2. Die App aus Programme öffnen und das Onboarding durchlaufen.
3. Verbindungen einrichten, Sounds wählen und gewünschte Berechtigungen erlauben.
4. Bereits laufende Claude-Code-Sitzungen neu starten und eine echte Anfrage testen.

**Wichtig:** Diese Preview ist mit Developer ID signiert, aber noch nicht von Apple notarisiert. macOS kann das Öffnen blockieren. Falls „Dennoch öffnen“ unter Systemeinstellungen → Datenschutz & Sicherheit angeboten wird, nutze es nur, wenn du dem Download vertraust. Für die unkomplizierte Installation ohne diesen Zusatzschritt bitte die notarisierten Releases abwarten.

## Voraussetzungen

Apple Silicon (M1 oder neuer), macOS 13+. Audio-Ducking benötigt macOS 14.2+. Unter macOS 13 bis 14.1 bleiben Banner und Sounds verfügbar. Intel-Macs sind in dieser Version nicht enthalten. macOS 13 ist als Build-Ziel geprüft, aber noch nicht auf einem echten macOS-13-Gerät getestet.

Audioverarbeitung findet lokal statt; Systemaudio wird nicht gespeichert oder hochgeladen. Updates werden über GitHub geprüft. Bei eingeschaltetem Ducking und fehlender oder fehlgeschlagener Freigabe kann jede neue echte Benachrichtigung erneut zur Freigabe auffordern. Ist Ducking aus, entfallen diese Nachfragen.

[Fehler melden](https://github.com/finlay28/let-me-know-releases/issues/new) · [Englische Hauptseite](../README.md)
