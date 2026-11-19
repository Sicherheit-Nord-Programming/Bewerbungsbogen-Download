# Bewerbungsbogen-Download

Hier liegt die vollständige Windows-Desktop-App für den Bewerbungsbogen von
Sicherheit Nord. Für Installation und Updates sind kein GitHub-Konto, keine
Anmeldung und kein Terminal erforderlich.

## Installation

[Bewerbungsbogen-Setup.exe herunterladen](https://github.com/Sicherheit-Nord-Programming/Bewerbungsbogen-Download/releases/latest/download/Bewerbungsbogen-Setup.exe)

Die EXE installieren und anschließend das Desktop-Symbol **Bewerbungsbogen**
öffnen. Beim ersten Start wird nur die Niederlassung des PCs abgefragt. Der
Mailversand ist danach automatisch freigeschaltet.

Neue Versionen werden in der App über den Button **Update** geladen. Nach dem
vollständigen Download installiert die App das Update und startet automatisch
neu.

## Veröffentlichung

Jeder erfolgreich geprüfte Commit auf `main` stößt den öffentlichen Build mit
genau dieser Commit-ID an. Windows-Setup und Update-Metadaten werden vollständig
geprüft, bevor der Release in einem Schritt als `latest` sichtbar wird. Schlägt
der Build oder Upload fehl, bleibt der vorherige vollständige Windows-Release
aktiv. Die Linux-App wird anschließend ergänzt; dabei wird die Binärdatei vor
ihren Update-Metadaten hochgeladen.
