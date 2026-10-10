<p align="center"><img src="icon.png" width="96" alt=""></p>

<h1 align="center">Летчик-переводчик</h1>

<p align="center">Самолётик поверх всех окон, который переводит выделенный текст.<br>
Выделил текст где угодно → кликнул по самолётику → перевод перед глазами, а под ним оригинал.</p>

## ⬇️ Скачать

| Система | Файл |
|---|---|
| **macOS** 13+ (Apple Silicon и Intel) | [PilotTranslator-1.1-macOS.dmg](https://github.com/abendryu/pilot-translator-releases/releases/latest/download/PilotTranslator-1.1-macOS.dmg) — 1,6 МБ |
| **Windows** 10 / 11 (64-bit) | [PilotTranslator-1.1-Windows-x64.exe](https://github.com/abendryu/pilot-translator-releases/releases/latest/download/PilotTranslator-1.1-Windows-x64.exe) — 70 МБ |
| **Ubuntu / Debian / Mint** | [pilot-translator_1.1_all.deb](https://github.com/abendryu/pilot-translator-releases/releases/latest/download/pilot-translator_1.1_all.deb) — 0,3 МБ |
| **Другой Linux** (Fedora, Arch…) | [pilot-translator-1.1.tar.gz](https://github.com/abendryu/pilot-translator-releases/releases/latest/download/pilot-translator-1.1.tar.gz) — 0,3 МБ |

Все версии — на странице [релизов](https://github.com/abendryu/pilot-translator-releases/releases).

## Что умеет

- **Перевод выделенного текста** в любом приложении — мышкой, двойным кликом или Shift+стрелками
- **Перевод области экрана** — картинки, кадры видео, PDF-сканы; текст распознаётся прямо на компьютере
- **Уборщик** — раскладывает скопированную кашу из комментариев и лент: убирает «Ответить», счётчики лайков
- **Горячая клавиша** — ⌥⌘T на Mac, Ctrl+Alt+T на Windows, Ctrl+Alt+Y на Linux; можно назначить свою
- **Озвучка** перевода и копирование в один клик
- 9 языков с автоопределением, три размера самолётика, запуск вместе с системой

## Установка

**macOS.** Открой DMG и перетащи летчика в «Программы». Первый запуск — правый клик по приложению →
«Открыть» → «Открыть» (оно не нотаризовано Apple). Если не открывается: Системные настройки →
Конфиденциальность и безопасность → внизу «Всё равно открыть». Потом разреши «Универсальный доступ»
(чтобы летчик видел выделенный текст), а для перевода области — «Запись экрана».

**Windows.** Просто запусти exe — устанавливать ничего не нужно. Windows покажет «Windows защитила
компьютер» (программа не подписана): «Подробнее» → «Выполнить в любом случае».

**Ubuntu / Debian / Mint.** `sudo apt install ./pilot-translator_1.1_all.deb` — всё нужное подтянется само.

**Другой Linux.** Распакуй архив и запусти `./install.sh` — поставит в домашнюю папку без sudo
(какие пакеты нужны для Fedora и Arch — написано в начале `install.sh`).

## Приватность

- Выделенный текст отправляется на перевод в Google Translate.
- Пароли, токены, ключи и номера карт **не отправляются**; менеджеры паролей летчик не читает.
- Снимки экрана распознаются на компьютере, никуда не уходят и не хранятся.
