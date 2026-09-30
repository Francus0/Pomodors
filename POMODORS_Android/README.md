# POMODORS — Android APK

Este proyecto empaqueta la versión actual de POMODORS dentro de una aplicación Android nativa mediante WebView.

## APK automático

El workflow `.github/workflows/build-apk.yml` compila un `app-debug.apk` y lo deja como artefacto de GitHub Actions.

## También se puede abrir con Android Studio

Abre esta carpeta como proyecto Gradle y ejecuta la variante `debug`.

## Qué conserva

- Interfaz actual de POMODORS.
- Revisión normal y modo “Explícaselo a un niño”.
- Dictado por voz (cuando el WebView/Android System WebView lo soporta).
- Carga de PDF/PPTX/ODP/imágenes/texto.
- Gemini y Groq mediante sus API Keys.
- Conversión a PDF.
- Tres temas y personaje pixel art.
