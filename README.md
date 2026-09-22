# HolaYo

Laboratorio 1 y 2 de Aplicaciones Móviles. Muestra mi nombre, un dato mío, y un botón que alterna el saludo en cada toque ("Hola, soy Fede" / "¡Buenas! Acá Fede").

Datos del proyecto:

- Plantilla: Empty Views Activity 
- Lenguaje: Kotlin
- minSdk: 26 (Android 8.0)
- Package: `com.example.holayo`

Ruta del APK: `app\build\outputs\apk\debug\app-debug.apk`
Peso del APK: 6.57 MB

Notas:

Apretar Home (la app queda en fondo):  `onPause` → `onStop`
Volver a la app desde recientes: `onStart` → `onResume`
Apagar la pantalla con el botón de encendido: `onPause` → `onStop`.
Encenderla y desbloquear: `onStart` → `onResume`.
Abrir la cortina de notificaciones completa y cerrarla: no vi nada. 
Recibir algo encima (diálogo de volumen) y volver: tampoco vi nada. 
