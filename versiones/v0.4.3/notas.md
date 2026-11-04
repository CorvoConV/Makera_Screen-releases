# Makera Z1 Display 0.4.3
- Vista previa de archivos: la lectura ya no se corta por tiempo mientras la máquina siga enviando el archivo (antes había un tiempo máximo calculado a 20 KB/s, cerca del límite del enlace interno de la Z1, y los archivos que llegaban más despacio fallaban). Si falla, se dice por qué y cuánto se leyó.
- Durante la lectura no se pide el diagnóstico, como hace Makera Controller.
