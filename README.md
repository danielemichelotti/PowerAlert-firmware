# PowerAlert – firmware

Questo repository contiene **solo i firmware compilati** di PowerAlert (allarme mancanza corrente su Arduino Nano 33 IoT), pubblicati nelle [Release](../../releases):

- `PowerAlert-X.Y.Z.bin` – immagine del firmware
- `manifest.json` – versione, dimensione e CRC32 del `.bin`

Le schede PowerAlert controllano `releases/latest/download/manifest.json`, segnalano quando è disponibile una nuova versione e la installano solo su comando.
Il codice sorgente non è pubblico.
