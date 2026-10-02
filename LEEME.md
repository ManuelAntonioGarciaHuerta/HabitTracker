# Hábitos — App de seguimiento de hábitos diarios

Proyecto de Android Studio hecho con **Kotlin + Jetpack Compose** y **Material 3**.
Deja marcar tus hábitos del día, lleva una racha (🔥) de cada uno y muestra tu
progreso diario con una barra animada. Puedes agregar o eliminar hábitos libremente.

## Cómo abrirlo

1. Descomprime el archivo `HabitTracker.zip` en cualquier carpeta.
2. Abre **Android Studio** → `File > Open...` → selecciona la carpeta `HabitTracker` (la que contiene `settings.gradle.kts`).
3. Espera a que Android Studio sincronice el proyecto con Gradle (necesita conexión a internet la primera vez para descargar Gradle 8.9 y las dependencias). Si aparece un aviso de "Gradle wrapper no encontrado", elige la opción para generarlo/usar el que se descargue automáticamente.
4. Cuando termine el sync, dale a **Run ▶** con un emulador o un dispositivo físico (Android 8.0 / API 26 en adelante).

## Estructura

- `app/src/main/java/.../MainActivity.kt` — toda la pantalla y lógica (lista de hábitos, progreso, diálogo para agregar).
- `app/src/main/java/.../ui/theme/` — colores, tipografía y tema Material 3 (paleta verde azulado).
- `app/src/main/res/` — nombre de la app, ícono adaptativo y tema base.

## Personalizar

- Cambia el nombre de la app en `res/values/strings.xml`.
- Cambia los colores en `ui/theme/Color.kt`.
- Los hábitos de ejemplo están definidos al inicio de `HabitTrackerApp()` en `MainActivity.kt`.
