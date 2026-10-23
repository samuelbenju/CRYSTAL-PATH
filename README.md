# Crystal Path 1.4.0 — Mundos de cristal

[Descargar el juego y el proyecto Android Studio](./CrystalPath-PlayStore.zip?raw=true)

Si GitHub muestra una vista del archivo, pulsa **Download raw**. Inicia sesión si este repositorio es privado.

El ZIP contiene:

- **CrystalPath-1.4.0-release-signed.aab**: bundle firmado con la clave de subida del titular, listo para cargar a Play Console.
- **CrystalPath-1.4.0-AndroidStudio.zip**: proyecto portátil. Descomprime todo y abre `CrystalPath/android/`.
- **RELEASE-NOTES.es.txt**: notas para Play Console.
- **LEEME.txt** y **SHA256SUMS.txt**: instrucciones y comprobaciones de integridad.

Package name: `com.samuelbenju.crystalpath` · Release name: `1.4.0 – Mundos de cristal` · Version code: **5**.

Esta versión organiza la aventura en mundos de diez niveles, muestra los niveles superados y las estrellas, y añade recorridos con obstáculos crecientes. Cada mundo contiene los mismos niveles para todos los jugadores. Conserva el vestuario y los anuncios cada dos niveles completados.

El AAB supera la firma estricta y `bundletool validate`. Pasan 217 pruebas de juego y 35 de interfaz, además de la validación final de sesiones. El proyecto extraído compila correctamente. Antes de publicar, realiza la prueba interna en Android y comprueba AdMob en un dispositivo.

No se incluyen claves privadas ni contraseñas. Esta rama distribuye archivos; no publica automáticamente en Google Play.
