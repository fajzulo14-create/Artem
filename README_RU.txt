КОСМИЧЕСКИЙ КУРЬЕР — APK PROJECT

Это готовая структура Android Studio для упаковки игры в APK.

Что внутри:
- app/src/main/assets/index.html — игра
- MainActivity.kt — Android WebView-обёртка
- launcher icon — иконка игры
- landscape orientation — горизонтальный режим
- JavaScript + DOM Storage включены

Как собрать APK:
1. Откройте папку KosmicheskiyKurier в Android Studio.
2. Дождитесь синхронизации Gradle.
3. Выберите Build → Build APK(s).
4. APK будет в:
   app/build/outputs/apk/debug/app-debug.apk

Для релизного APK:
Build → Generate Signed Bundle / APK → APK.

Интернет игре не нужен: HTML-файл находится внутри APK.
