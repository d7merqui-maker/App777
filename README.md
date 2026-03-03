# Web AdMob App (Android)

Aplicación Android en Kotlin que funciona como **web app** usando `WebView` y muestra anuncios de Google AdMob con un **banner** en la parte inferior.

## Lo que incluye
- `WebView` con JavaScript y DOM Storage habilitados.
- Banner AdMob (`AdView`) usando IDs de prueba oficiales de Google.
- Manejo del botón atrás para navegar dentro del WebView.

## Configuración rápida
1. Abre el proyecto en Android Studio (Giraffe o superior).
2. Sincroniza Gradle.
3. Reemplaza los IDs de prueba por tus IDs reales de AdMob:
   - `APPLICATION_ID` en `AndroidManifest.xml`
   - `adUnitId` en `activity_main.xml`
4. Cambia la URL en `MainActivity.kt` (`webView.loadUrl(...)`) por la de tu web app.
5. Ejecuta en dispositivo/emulador con Google Play Services.

## IDs de prueba usados
- App ID: `ca-app-pub-3940256099942544~3347511713`
- Banner Unit ID: `ca-app-pub-3940256099942544/6300978111`

> Importante: Nunca publiques en producción con IDs de prueba.
