# MamaMind — полный MVP (с codemagic.yaml)

## Быстрый старт с Codemagic (без Android Studio)
1) Создай пустой репозиторий на GitHub.
2) Залей ВСЕ файлы из этого архива в корень репозитория (в корне должны быть `pubspec.yaml` и `codemagic.yaml`).
3) На https://codemagic.io → Add Application → GitHub → выбери репозиторий.
4) Если спросят путь приложения — укажи `.` (точка).
5) Нажми **Check for configuration file** → **Start new build**.
6) Скачай APK из раздела **Artifacts** (`app-release.apk`).

## Примечания
- Для доступа к камере/галерее добавь в AndroidManifest разрешения (см. код в комментариях канваса).
- Для публикации в Google Play понадобится подпись (keystore) — это отдельный шаг.
