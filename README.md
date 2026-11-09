# FlowSub · versiones

Instaladores de **FlowSub**, un editor de subtítulos para traductores audiovisuales.
Para **Windows 10 y 11 (64 bits)**. Está en **beta**.

Este repositorio solo aloja los instaladores; no contiene el código de la aplicación.

## Descargar

[**FlowSub-Setup.exe**](https://github.com/Honcito/flowsub-releases/releases/latest/download/FlowSub-Setup.exe) (última versión).
Todas las versiones y sus notas están en la pestaña [Releases](https://github.com/Honcito/flowsub-releases/releases).

## Instalador sin firmar

El instalador aún no está firmado digitalmente, así que Windows SmartScreen puede avisar de «editor desconocido».
Pulsa **Más información** y después **Ejecutar de todas formas**.

Para comprobar que el archivo no se ha alterado, compara su huella SHA-256 con la que aparece en las notas de cada versión:

```powershell
Get-FileHash .\FlowSub-Setup.exe -Algorithm SHA256
```

## Licencias de terceros

FlowSub incluye [FFmpeg](https://ffmpeg.org/) a través del paquete [ffmpeg-static](https://github.com/eugeneware/ffmpeg-static),
distribuido bajo licencia GPL-3.0. Los textos de licencia se instalan con la aplicación, en la carpeta
`resources\app.asar.unpacked\node_modules\ffmpeg-static` de su directorio de instalación.
