IRY HUB - простое APK приложение (WebView)

Вариант 1: GitHub Actions (без установки чего-либо)
1. Создайте репозиторий на github.com и загрузите в него ВСЕ файлы этого проекта
   (включая папку .github).
2. Откройте вкладку Actions -> Build APK -> дождитесь зелёной галочки.
3. Внутри запуска скачайте артефакт IryHub-apk -> app-debug.apk -> установите на телефон.

Вариант 2: Android Studio
1. File -> Open -> выберите папку проекта.
2. Дождитесь Gradle sync.
3. Build -> Build APK(s). Файл: app/build/outputs/apk/debug/app-debug.apk

Сменить адрес сайта: app/src/main/java/com/iryhub/app/MainActivity.java (константа URL).
