# NorrNote21FE v0.7.0 — контрольный список выпуска

## Выполнено

- [x] Отдельный проект FE; личную NorrNote21 не менять.
- [x] Android Release ID `su.norrvind.norrnote.fe`, minSdk 29.
- [x] Отдельный ключ FE, APK успешно собран и проверен `apksigner` (v2, код 0); SHA-1 `FC:9C:28:11:2A:0C:67:66:4C:E4:75:FD:90:46:C3:8D:EC:99:BB:93`.
- [x] Windows self-contained ZIP, проверен на другом компьютере с новым Google-аккаунтом.
- [x] Google Drive папка `NorrNote21FE`, независимая от личного проекта.
- [x] Hotfix Sync21 собран на Windows и Android.
- [x] Семь пользовательских сценариев передачи/удаления вложений пройдены 11.10.2026.
- [x] Опубликованы страницы homepage, privacy, terms на norrvind.app.

## Завершить в существующем GitHub Release v0.7.0 (не создавать v0.7.1)

- [ ] Получить окончательные файлы Windows ZIP после hotfix и подписанный Android APK после hotfix.
- [ ] Проверить, что Windows ZIP включает EXE и OAuth-конфигурацию, но не содержит PDB, токенов, баз и ключей; архив протестировать после распаковки.
- [ ] Для Android подтвердить manifest package `su.norrvind.norrnote.fe`, versionName `0.7.0`, подпись и SHA-1.
- [ ] Вычислить SHA-256 обоих окончательных файлов.
- [ ] Заменить старый Windows asset в том же релизе и добавить Android APK; обновить release notes, ссылки и контрольные суммы.
- [ ] Сверить, что загружаемые из GitHub Assets файлы по SHA-256 идентичны проверенным локальным файлам.

## Не изменять

Личную `C:\Projects\NorrNote21`, личные Google Drive данные, личный OAuth, личные signing keys.

**Напоминание:** изменение текста README не заменяет двоичные Assets релиза.
