# Mole App

[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · Deutsch · [Français](README.fr.md) · [Español](README.es.md) · [Italiano](README.it.md) · [Português (Brasil)](README.pt-BR.md)

Offizielle Dokumentation und Community-Support für **Mole for Mac** und **Mole for Windows**.

Die Mac- und die Windows-App sind kostenpflichtige native Desktop-Apps, der Kauf einer Lizenz finanziert Entwicklung und Updates. Dieses Repository dient für Dokumentation, Fragen und Feedback und enthält keinen Quellcode der Apps. Die [Mole CLI](https://github.com/tw93/Mole) bleibt kostenlos und Open Source.

## Mole holen

| App | Voraussetzungen | Download | Anleitung |
| --- | --- | --- | --- |
| Mole for Mac | macOS 14 oder neuer, Apple Silicon oder Intel | [Mac-Website](https://mole.fit/de/?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Mac-Hilfe](https://mole.fit/de/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Mole for Windows | Windows 10 22H2 oder Windows 11, x64 oder ARM64 | [Windows-Website](https://mole.fit/de/windows?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Windows-Hilfe](https://mole.fit/de/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

Beide Apps vereinen Bereinigung, App-Verwaltung, Wartung, Datenträgeranalyse und den Live-Systemstatus in einer Oberfläche.

### Mole for Mac

Mole for Mac ist eine native SwiftUI-App, die von [Tw93](https://github.com/tw93) entwickelt und gepflegt wird, mit schnellen Werkzeugen in der Menüleiste.

![Bereinigungsansicht von Mole for Mac](https://mole.fit/img/de/clean.jpg)

| Werkzeug | Was Sie damit tun können | Anleitung |
| --- | --- | --- |
| Bereinigen | App- und Browser-Caches, Protokolle und Build-Dateien von Entwicklertools ansehen, bevor Sie entscheiden, was entfernt wird | [Mac-Bereinigung](https://mole.fit/de/mac-cleaner?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Apps | Apps deinstallieren, ihre Reste prüfen, nach Updates suchen und Startobjekte verwalten | [App-Verwaltung](https://mole.fit/de/mac-app-uninstaller?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Optimieren | macOS-Wartung ausführen, Bildschirm wischen oder Bildschirm anlassen nutzen | [Mac-Wartung](https://mole.fit/de/mac-optimizer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Analyse | Große Dateien und Ordner in einer Treemap finden, im Finder anzeigen oder ausgewählte Objekte in den Papierkorb legen | [Datenträgeranalyse](https://mole.fit/de/mac-disk-analyzer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Status | CPU, Arbeitsspeicher, Speicherplatz, Netzwerk und Temperatur ansehen, ausgewählte Werte auch in der Menüleiste | [Systemmonitor](https://mole.fit/de/mac-system-monitor?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

#### KI-Bereinigung

Die stabile Version Mole for Mac 1.16.0 enthält unter Bereinigen die KI-Bereinigung und -Pflege. Sie prüft Caches, alte Versionen, alte Sitzungen, aufräumbare Worktrees und ungenutzte Kommandozeilen-Tools von Claude Code, Codex, Cursor und anderen KI-Tools. Caches sind vorausgewählt, Sitzungen und Tools müssen Sie selbst prüfen. Erinnerungen, Pläne und Skills sind ausgenommen. Bei lokalen Modellen werden nur Ollama-Modelle aufgelistet, die seit einem Monat nicht benutzt wurden, die Sie auswählen und über Ollama entfernen. Details stehen in der [Anleitung zur KI-Bereinigung](https://mole.fit/de/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#docs-ai).

### Auf dem Mac loslegen

1. Laden Sie das DMG von der Mac-Website oben herunter, ziehen Sie Mole in den Ordner „Programme“ und öffnen Sie es. Wenn Sie schon Homebrew nutzen, installiert `brew install --cask mole-app` die Mac-App.
2. Starten Sie einen Scan und prüfen Sie die Ergebnisse, bevor Sie etwas entfernen. Meldet Mole fehlenden Festplattenzugriff, folgen Sie der Anleitung zu den Berechtigungen weiter unten und starten Sie Mole neu.
3. Öffnen Sie nach dem Kauf mit `Cmd + Shift + L` das Lizenzfenster, fügen Sie den Schlüssel aus der E-Mail von Dodo Payments ein und klicken Sie auf Aktivieren.

[Mac-Artikel](https://mole.fit/de/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Mac-Release-Notes](https://mole.fit/de/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

### Ausgewählte Mac-Anleitungen

- [Mole CLI vs. Mac-App](https://mole.fit/de/blog/mole-cli-vs-mac-app?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): worin sich das kostenlose Terminal-Tool und die kostenpflichtige native App unterscheiden.
- [Ist Mole sicher für den Mac?](https://mole.fit/de/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): was in den Papierkorb kommt, was endgültig gelöscht wird und was geschützt bleibt.
- [Was sind Systemdaten auf dem Mac?](https://mole.fit/de/blog/what-is-system-data-on-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): herausfinden, was Speicherplatz belegt, bevor Sie etwas löschen.
- [Reste nach der Deinstallation prüfen](https://mole.fit/de/blog/mac-uninstall-leftovers-review-before-delete?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): vor dem Entfernen Dateibesitz und gemeinsam genutzte Daten kontrollieren.
- [Ollama- und LM-Studio-Modelle löschen](https://mole.fit/de/blog/how-to-remove-ai-tool-leftovers-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): heruntergeladene Modelle, Caches und persönliche Daten auseinanderhalten.
- [Mac-Apps für Mole testen](https://mole.fit/de/blog/testing-mac-apps-one-by-one?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): was echte Installationen und Deinstallationstests zeigen.

### Mole for Windows

Die Windows-App wird mit jedem Release weiter verbessert.

![Bereinigungsansicht von Mole for Windows](https://mole.fit/img/windows-de/clean.jpg)

[Windows-Artikel](https://mole.fit/de/windows/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Windows-Release-Notes](https://mole.fit/windows/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

## Feedback

- [Fehler in der Mac-App melden](https://github.com/tw93/Mole-App/issues/new?template=mac_bug.yml)
- [Fehler in der Windows-App melden](https://github.com/tw93/Mole-App/issues/new?template=windows_bug.yml)
- [Funktion vorschlagen](https://github.com/tw93/Mole-App/issues/new?template=feature_request.yml)
- [Frage stellen oder mitdiskutieren](https://github.com/tw93/Mole-App/discussions)

Issues und Diskussionen sind öffentlich. Bei Fragen zu Kauf, Aktivierung oder Rückerstattung schreiben Sie an [hi@mole.fit](mailto:hi@mole.fit). Sicherheitsmeldungen senden Sie über den [privaten Meldeweg](.github/SECURITY.md).

Für Mac-Diagnosen öffnen Sie das Mole-Logo-Menü und wählen Diagnose starten. Senden Sie den Bericht privat an [hi@mole.fit](mailto:hi@mole.fit), zusammen mit der App-Version und einer Beschreibung, was passiert ist.

Für CLI-Fehler und Funktionswünsche nutzen Sie [tw93/Mole](https://github.com/tw93/Mole/issues).

## FAQ

### Heißt ein öffentliches GitHub-Repository, dass die Apps Open Source sind?

Dieses Repository enthält Dokumentation und Community-Feedback. Der Quellcode der Mac- und der Windows-App ist privat. Die [Mole CLI](https://github.com/tw93/Mole) ist kostenlos und Open Source.

### Muss ich die CLI installieren, um die Apps zu nutzen?

Nein. Mole for Mac und Mole for Windows sind eigenständige Desktop-Apps. Die Installation der CLI installiert keine der beiden Apps.

### Sind die Apps kostenlos?

Die Apps werden mit einer einmaligen Lizenz verkauft. Mole for Mac kostet **$19 USD für zwei Macs**, ohne Abo und mit kostenlosen Updates, auch für Hauptversionen. Die [offizielle Preisseite](https://mole.fit/pricing.md?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) nennt die aktuellen Bedingungen. Preise und Verfügbarkeit für Windows stehen auf der zugehörigen Produktwebsite. Die Open-Source-CLI ist kostenlos.

### Kann ich die Mac-App vor dem Kauf ausprobieren?

Das Scannen ist kostenlos, und jedes kostenpflichtige Werkzeug lässt sich zweimal testen. Datenträgeranalyse und Systemstatus können Sie ohne Lizenz ansehen. Die [Mac-Hilfe](https://mole.fit/de/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) erklärt, wie Sie die App herunterladen, testen und aktivieren.

### Kann ich meine Mac-Lizenz auf einen neuen Computer übertragen?

Öffnen Sie auf dem alten Mac mit `Cmd + Shift + L` das Lizenzfenster, deaktivieren Sie die Lizenz und aktivieren Sie denselben Schlüssel dann auf dem neuen Mac. Ist der alte Mac nicht mehr verfügbar, melden Sie sich mit Ihrer Kauf-E-Mail im [Dodo-Payments-Kundenportal](https://customer.dodopayments.com/) an und deaktivieren ihn dort. Wie viele Geräte erlaubt sind, hängt von der gekauften Lizenz ab. Die aktuelle Edition gilt für zwei Macs.

### Wo finde ich meinen Lizenzschlüssel und die Rechnung?

Suchen Sie in Posteingang und Spam-Ordner nach Dodo Payments, oder melden Sie sich mit der beim Bezahlen verwendeten E-Mail-Adresse im [Dodo-Payments-Kundenportal](https://customer.dodopayments.com/) an, um Schlüssel, Bestellung und Rechnung zu finden. Wenn Sie weiter Hilfe brauchen, schreiben Sie mit Ihrer Kauf-E-Mail oder Payment-ID an [hi@mole.fit](mailto:hi@mole.fit). Posten Sie diese Angaben nicht in öffentlichen Issues.

### Was, wenn die Mac-App nichts für mich ist?

Schreiben Sie innerhalb von 14 Tagen nach dem Kauf mit Ihrer Payment-ID oder Kauf-E-Mail an [hi@mole.fit](mailto:hi@mole.fit). Die vollständigen Bedingungen stehen in der [Rückerstattungsrichtlinie](https://mole.fit/de/refund?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme).

### Lädt die Mac-App meine Dateien oder Scan-Ergebnisse hoch?

Scannen und Bereinigen laufen lokal auf Ihrem Mac. Mole lädt weder Dateiinhalte noch Dateinamen oder Scan-Ergebnisse hoch, und das lokale Vorgangsprotokoll wird nicht automatisch hochgeladen. Die [Datenschutzerklärung](https://mole.fit/de/privacy?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) erklärt, welche Funktionen wie Lizenzaktivierung und Updates Online-Dienste kontaktieren.

### Warum verlangt Mole Festplattenzugriff?

macOS schränkt den Zugriff auf einige App-Daten ein. Mit Festplattenzugriff kann Mole diese Orte prüfen. Geschützte Pfade und Ihre Whitelist gelten weiterhin, die Freigabe macht also nicht jede Datei zum Bereinigungskandidaten. Siehe die [Anleitung zu den Berechtigungen](https://mole.fit/de/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#doctor-permission-fda).

### Kann ich Dateien nach der Mac-Bereinigung wiederherstellen?

Deinstallierte Apps und ihre ausgewählten Reste landen im Papierkorb und lassen sich wiederherstellen, solange sie dort liegen. Die Cache-Bereinigung löscht standardmäßig endgültig, in den Einstellungen gibt es eine Option für den Papierkorb. Einige Wartungsaktionen entfernen Daten direkt und lassen sich nicht rückgängig machen. Die [Sicherheitsanleitung](https://mole.fit/de/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) erklärt jeden Vorgang.

### Wie funktionieren Mac-Updates und Preview-Funktionen?

Mole hat einen integrierten Updater, und die [offiziellen Release-Notes](https://mole.fit/de/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) beschreiben jedes Release. Funktionen, die in der Dokumentation als Preview gekennzeichnet sind, erfordern den Preview-Build, bis sie in einem stabilen Release erscheinen.

### Kann ich Mole mit der Tastatur oder mit VoiceOver bedienen?

Mole unterstützt Tastaturbedienung und VoiceOver. Die Treemap ist visuell, dieselben Dateien lassen sich aber in der Liste Größte Dateien mit Tastatur oder VoiceOver durchsuchen. Details und aktuelle Einschränkungen stehen in der [Anleitung zur Bedienungshilfe](https://mole.fit/de/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme).

### Welche Website ist die offizielle?

**mole.fit** ist die offizielle Website der Apps. Aktuelle Pakete finden Sie über die Download-Links oben. Die kostenlose CLI liegt unter [tw93/Mole](https://github.com/tw93/Mole).

### Wo finde ich ausführliche Anleitungen?

Die [Mac-Dokumentation](https://mole.fit/de/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) erklärt die Werkzeuge und ihre Sicherheitsregeln. Der [Katalog getesteter Apps](https://mole.fit/de/tested-apps?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) enthält Hinweise zu Installation, Deinstallation und Resten einzelner Apps. Bei Einrichtung, Aktivierung oder Fehlersuche hilft die [Mac-Hilfe](https://mole.fit/de/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) oder die [Windows-Hilfe](https://mole.fit/de/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme). Die Lizenzbedingungen stehen in den [Nutzungsbedingungen](https://mole.fit/de/terms?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme).
