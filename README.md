# LotusGauges Firmware

Fertige Firmware-Dateien der beiden LotusGauges-Displays (G-Meter und Tempo/Drehzahl) für das automatische Update.
Die Displays lesen `manifest.txt` (je Display: Name, Version, Größe, SHA-256, Datei) und laden bei neuerer Version
die genannte `*_ota.bin`. Erzeugt mit `tools/release.sh` aus dem (privaten) Quell-Repo; nicht von Hand ändern.
