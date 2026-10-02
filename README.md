# InvoiceFlow Desktop

Installationsdateien der Desktop-App von [InvoiceFlow](https://invoiceflowz.de)
für Windows und macOS. Dieses Repository enthält nur die Installer, der
Quellcode ist nicht öffentlich.

Die Desktop-App öffnet dieselbe Anwendung wie https://invoiceflowz.de.
Zusätzlich kann sie Belege mit einem **KI-Modell auf Ihrem eigenen Rechner**
auslesen (Ollama oder LM Studio); die Belege verlassen dafür den Rechner
nicht.

## Herunterladen

Unter [Releases](https://github.com/nobasicshick-cyber/invoiceflow-releases/releases/latest)
die neueste Version öffnen:

| System | Datei |
|---|---|
| Windows 10/11 (64 Bit) | `InvoiceFlow-Setup-<Version>.exe` |
| macOS (Intel und Apple Silicon) | `InvoiceFlow-<Version>-universal.dmg` |

Die übrigen Dateien (`.zip`, `.blockmap`, `latest*.yml`) braucht nur die
automatische Aktualisierung.

## Installation

Die Installer sind derzeit noch nicht mit einem Herausgeber-Zertifikat
signiert. Ihr System warnt deshalb beim ersten Start.

**Windows:** Erscheint "Der Computer wurde durch Windows geschützt", auf
"Weitere Informationen" und dann "Trotzdem ausführen" klicken.

**macOS:** DMG öffnen und InvoiceFlow in den Ordner "Programme" ziehen.
Beim ersten Start meldet macOS, dass die App nicht überprüft werden kann.
Dann:

1. Meldung mit "Fertig" schliessen.
2. Systemeinstellungen -> Datenschutz & Sicherheit öffnen.
3. Unten bei InvoiceFlow auf "Dennoch öffnen" klicken und bestätigen.

Das ist nur beim ersten Start nötig.

## Updates

Die App prüft bei jedem Start, ob es in diesem Repository eine neuere
Version gibt, und lädt sie im Hintergrund. Unter macOS funktioniert die
automatische Aktualisierung erst mit signierten Versionen; bis dahin bitte
neue Versionen von hier herunterladen.

## Datenschutz

Für Download und Update-Prüfung ruft die App Daten von GitHub (GitHub, Inc.,
USA) ab; GitHub erhält dabei Ihre IP-Adresse und technische Angaben zum
Abruf. Belegdaten werden dabei nicht übertragen. Details in der
[Datenschutzerklärung](https://invoiceflowz.de/legal/datenschutz).

## Kontakt

[Impressum](https://invoiceflowz.de/legal/impressum)
