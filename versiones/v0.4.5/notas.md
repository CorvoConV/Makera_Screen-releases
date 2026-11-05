# Makera Z1 Display 0.4.5
- Husillo: con el husillo girando ya se puede aplicar otra velocidad sin pararlo (la Z1 informa "Run" mientras gira y la pantalla lo tomaba por máquina ocupada).
- Vista previa de archivos: la orden "download" va en la trama propia de las descargas, como en Makera Controller; antes la Z1 no contestaba. Se aceptan bloques de hasta 8 KB (antes se descartaban los de más de 2 KB) y sin respuesta se pide repetir como hace Makera.
- Corregido: seleccionar un archivo hacía perder la conexión. Durante la descarga no se pide el estado y a los 5 segundos de silencio se cerraba el enlace; ahora espera lo que dure la descarga.
