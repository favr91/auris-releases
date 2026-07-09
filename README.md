# Auris — releases

Manifiesto de actualización y APKs de **Auris**, un lector de EPUB con voz
neuronal en el dispositivo (offline).

- **[Descargar la última versión](https://github.com/favr91/auris-releases/releases/latest)**
- La app consulta [`latest.json`](latest.json) al abrir y avisa cuando hay una versión nueva.

## Publicar una nueva versión
1. En el proyecto, sube `versionCode` y `versionName` en `app/build.gradle.kts`.
2. Genera el APK firmado (`assembleRelease`).
3. Crea un Release aquí con el tag `vX.Y.Z` y sube el APK como `Auris-X.Y.Z.apk`.
4. Actualiza `latest.json` (`versionCode`, `versionName`, `apkUrl`, `notes`).
