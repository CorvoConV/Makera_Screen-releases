# Makera Z1 Display: versiones publicadas

Firmware de la pantalla táctil Makera Z1 Display (Waveshare ESP32-P4-WIFI6-Touch-LCD-7B) para la
CNC Makera Z1 Pro. Interfaz no oficial: Makera Z1 y Makera Studio son de Makera. El código está en
un repositorio aparte. Aquí solo se publican los binarios **firmados y cifrados** que la pantalla instala por
WiFi.

- `versiones/vX.Y.Z/`: `Makera_Z1_Display.bin`, `manifiesto.txt` y `notas.md` de cada versión.
- Cada etiqueta `vX.Y.Z` crea su release (`.github/workflows/release.yml`). La pantalla lee
  `releases/latest/download/manifiesto.txt`.
- Un `.bin` sin la firma del propietario se rechaza en la pantalla aunque esté publicado aquí.

No edites estos archivos a mano: los genera `tools/publicar_version.py` del repositorio del firmware.
