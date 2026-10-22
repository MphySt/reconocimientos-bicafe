# Reconocimientos BICAFE

Encuesta de reconocimiento al personal de BICAFE.

- `index.html`: votación (la abre el código QR).
- `resultados.html`: estadísticas, resultados animados y ganadores (pide la clave de resultados).
- `datos.bin`: fotos y nombres del personal **cifrados** (AES-GCM). Solo se abren con el código de acceso del QR.
- `config.js`: dirección de la aplicación de Google Apps Script que guarda los votos.

Los votos se guardan en una hoja de Google privada del administrador.
