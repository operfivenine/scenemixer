<p align="center"><img src="assets/readme/scenemixer-logo.png" width="174" alt="SceneMixer — логотип"></p>

<h1 align="center">SceneMixer</h1>
<h3 align="center">Найди сцены. Собери микс.</h3>

<p align="center">
  <img src="assets/readme/badge-windows.svg" alt="Windows desktop">
  <a href="https://ffmpeg.org/"><img src="assets/readme/badge-ffmpeg.svg" alt="FFmpeg / ffprobe"></a>
</p>

<p align="center">
  <a href="https://github.com/operfivenine/scenemixer/releases/download/v21.0-r4-win01/SceneMixer-21.0-R4-WIN01-Setup-x64.exe"><img src="assets/readme/button-download.ru.svg" alt="Скачать для Windows"></a>
  <a href="docs/user-guide.ru.md"><img src="assets/readme/button-guide.ru.svg" alt="Руководство пользователя"></a>
  <a href="https://boosty.to/oper59"><img src="assets/readme/button-support.ru.svg" alt="Поддержать SceneMixer"></a>
</p>

<p align="center"><a href="README.md">English</a> · <a href="README.ru.md">Русский</a></p>

**SceneMixer помогает превращать локальные видео в новые монтажи из сцен.** Находите сцены автоматически или выбирайте точные фрагменты в Cutter, объединяйте материал из нескольких источников, проверяйте микс и экспортируйте готовый ролик. Исходные файлы остаются без изменений.

**Добавить видео → Найти или нарезать сцены → Собрать микс → Проверить → Экспортировать**

<a id="download"></a>

## Загрузка

**SceneMixer 21.0 R4 · WIN01 · Windows x64 · Предварительный релиз**

**[Скачать установщик — 167,2 МиБ](https://github.com/operfivenine/scenemixer/releases/download/v21.0-r4-win01/SceneMixer-21.0-R4-WIN01-Setup-x64.exe)** · [Описание релиза](https://github.com/operfivenine/scenemixer/releases/tag/v21.0-r4-win01) · [Контрольные суммы SHA-256](https://github.com/operfivenine/scenemixer/releases/download/v21.0-r4-win01/SHA256SUMS.txt)

Скачайте и запустите установщик, затем следуйте его шагам. Перед обновлением закройте SceneMixer. WIN01 — публичный тестовый пакет; матрица проверенных систем и минимальные требования к оборудованию ещё готовятся.

Сборка уже установлена? Начните с [первого монтажа](docs/tutorials/01_First_Mix.ru.md).

## Что можно сделать

Соберите моменты из нескольких видео в один монтаж, сохраните вручную выбранные фрагменты или сравните разные порядки сцен перед экспортом.

| Найти сцены | Отобрать и упорядочить | Собрать ролик |
| --- | --- | --- |
| Автопоиск с настройкой чувствительности | Точные границы фрагментов в Cutter | Сборка выбранных сцен в Scene Mixer |
| Несколько локальных исходников | Правка границ и объединение соседних сцен в SCM | Проверка порядка через Quick Preview |
| Дополнительный детектор TransNetV2 | Проекты `.smx` и карты сцен `.scm` | Выбор кодека, качества, разрешения и FPS |

## Видео, проекты и карты сцен

| Файл | Что хранит |
| --- | --- |
| Исходное видео | Ваш материал; редактирование проекта его не перезаписывает. |
| Проект `.smx` | Ссылки на видео, выбранные сцены, правки, настройки и состояние Mix. |
| Карта `.scm` | Границы сцен и связанные данные одного источника. |

Проекты и карты сцен **не содержат сами видео**. Сохраняйте исходники; если они перемещены, используйте **«Проект → Файлы проекта… → Заменить расположение…»**. [Подробнее о проектах и SceneMaps →](docs/project-files.ru.md)

## Дополнительные инструменты

Включите нужные инструменты в **«Настройки → Дополнительные функции»**:

- **Варианты Mix:** сравнивайте монтажи из одного набора сцен, закрепляйте удачные и пересобирайте остальные. Ограничение пересечений уменьшает повторы; при малом наборе сцен соблюсти его может быть невозможно.
- **Find Originals:** сопоставляйте фрагменты монтажа с качественными исходниками, проверяйте результат или назначайте совпадения вручную.
- **Converter:** преобразуйте видео отдельно от экспорта Mix проекта.

Интерфейс и встроенный FAQ с поиском доступны на русском и английском. Нажмите **F1**, чтобы открыть справку. [Дополнительные инструменты →](docs/optional-tools.ru.md)

## Справка в приложении

Нажмите **F1**, чтобы открыть встроенный **FAQ с поиском** на русском или английском языке. Для пошаговых инструкций используйте [руководство](docs/user-guide.ru.md), для типовых затруднений — [решение проблем](docs/troubleshooting.ru.md).

## Технологии

SceneMixer использует PySide6 / Qt, PySceneDetect, OpenCV и [FFmpeg](https://ffmpeg.org/) / [ffprobe](https://ffmpeg.org/ffprobe.html). Дополнительный детектор TransNetV2 работает через ONNX Runtime. [Благодарности →](docs/credits.ru.md)

## Обратная связь и поддержка

[Поддержать oper59 на Boosty](https://boosty.to/oper59). Поддержка разработки добровольна.

Нашли ошибку? [Создайте обращение в Issues](https://github.com/operfivenine/scenemixer/issues). Укажите версию программы, Windows и шаги воспроизведения — [подробнее](docs/troubleshooting.ru.md#report-a-problem).

**Оператор: oper59.**

---

<p align="center"><strong>Найди сцены. Собери микс.</strong></p>
