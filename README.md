# Astrion · Descargas de la beta

Instaladores de la beta de **Astrion** para Windows y macOS. La web con la descripción de cada herramienta está en [astrionmusic.com](https://astrionmusic.com).

| Herramienta | Windows | macOS |
| --- | --- | --- |
| [Sample Record](https://github.com/astrionmusic/downloads/releases/tag/sample-record-1.0.5-beta.2) | Instalador y versión portable | Apple Silicon e Intel |
| [Astrion Library](https://github.com/astrionmusic/downloads/releases/tag/astrion-library-0.2.0) | Instalador | Próximamente |
| [Astrion Map](https://github.com/astrionmusic/downloads/releases/tag/astrion-map-0.4.0) | Dispositivo para Ableton Live 12 (Max for Live) | El mismo archivo |

## Importante: es una beta

- Los instaladores **no están firmados**. Windows puede mostrar «Windows protegió su PC» (**Más información → Ejecutar de todas formas**) y macOS puede pedir que autorices la app en **Ajustes del Sistema → Privacidad y seguridad**.
- Sample Record en Mac: para grabar el audio del sistema hace falta una entrada virtual (por ejemplo BlackHole), configurada por separado.
- Astrion Map necesita Ableton Live 12 con Max for Live.

## Verificar la descarga

Cada release trae `SHA256SUMS.txt`. Para comprobar un archivo:

- Windows (PowerShell): `Get-FileHash .\archivo -Algorithm SHA256`
- macOS: `shasum -a 256 archivo`

El resultado debe coincidir con la línea de ese archivo en `SHA256SUMS.txt`.

## ¿Algo no anda?

Abrí un [issue](https://github.com/astrionmusic/downloads/issues) (indicá herramienta, versión y sistema) o escribí a astriondj@gmail.com.

---

# Astrion · Beta downloads (English)

Beta installers for **Astrion** (Windows and macOS). The installers are **unsigned**: Windows may show a SmartScreen warning and macOS may ask you to allow the app under System Settings → Privacy & Security. Each release includes `SHA256SUMS.txt` to verify your download. Problems? Open an [issue](https://github.com/astrionmusic/downloads/issues) or write to astriondj@gmail.com.
