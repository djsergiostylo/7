# VoiceSeparator Recorder — Android

Proyecto Android independiente para empaquetar la interfaz web de VoiceSeparator Recorder en una aplicación Android mediante WebView.

## Estado

Base Android inicial con compilación automatizada de APK de prueba mediante GitHub Actions. No es todavía una publicación firmada para Google Play ni implementa separación neuronal de voces.

## Compilar

En GitHub: **Actions → Android CI → Run workflow**. Descarga el artefacto `voicesep-debug-apk` al terminar.

## Requisitos

Android Studio/Gradle con JDK 17 para compilar localmente. La compilación en GitHub Actions no requiere configurar un keystore para el APK de prueba.
