# Русская локализация Live Data

- Идентификатор приложения: `live_data_ru`.
- Язык сборки задаётся в `mgu-repo.json`: `--language ru`.
- При ручной сборке: `python kit/tools/build.py --language ru live_data_ru`.
- Для проверки без SDK: `python kit/tools/build.py --language ru --preview-only live_data_ru`.
- `builtin/DME8FF_R.ru.json` содержит отображаемые русские подписи полей DME8FF_R; технические идентификаторы, DID, смещения, типы и коэффициенты преобразования не изменены.
- Кириллический атлас подключается штатным русским профилем сборщика `kit/tools/build.py`.

Предпросмотр не является установочным пакетом. Для создания `.mgu` необходим совместимый OAP SDK.
