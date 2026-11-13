<p align="center"><img src="icon.png" width="128" alt=""></p>

# Учебник101 Python

Редактор Python для уроков и ЕГЭ. Внутри настоящий Python 3.14, интернет не нужен.

- Справочник Python и «Что написать?» — подсказка команды по описанию своими словами.
- «По шагам»: программа рассказывает, что делает каждая строка.
- Черепашка (рисует пингвин) с сеткой и осями для задания 6.
- `open("24.txt")` читает файл рядом с программой; глубокая рекурсия с `@lru_cache`.
- Вкладки файлов, папка с файлами, дзен-режим, тёмная тема.

## Скачать последнюю версию

| Система | Файл |
|---|---|
| Windows | [uchebnik101-python-win-x64.exe](https://github.com/iCookiess/uchebnik101-python/releases/latest/download/uchebnik101-python-win-x64.exe) |
| Mac с процессором Apple (M1–M4) | [uchebnik101-python-mac-arm64.dmg](https://github.com/iCookiess/uchebnik101-python/releases/latest/download/uchebnik101-python-mac-arm64.dmg) |
| Mac с процессором Intel | [uchebnik101-python-mac-x64.dmg](https://github.com/iCookiess/uchebnik101-python/releases/latest/download/uchebnik101-python-mac-x64.dmg) |
| Linux (Ubuntu, Debian) | [uchebnik101-python-linux-amd64.deb](https://github.com/iCookiess/uchebnik101-python/releases/latest/download/uchebnik101-python-linux-amd64.deb) |
| Linux (другие) | [uchebnik101-python-linux-x86_64.AppImage](https://github.com/iCookiess/uchebnik101-python/releases/latest/download/uchebnik101-python-linux-x86_64.AppImage) |

Все версии — в разделе [Releases](https://github.com/iCookiess/uchebnik101-python/releases).

## Первый запуск

У программы нет платной цифровой подписи, поэтому система при первом запуске переспрашивает. Это нужно сделать один раз.

**Windows.** Запустите установщик. Если появится окно «Windows защитил ваш компьютер», нажмите «Подробнее», затем «Выполнить в любом случае».

**Mac.** Откройте .dmg и перетащите программу в «Программы». Запустите её. Если Mac пишет, что не может проверить разработчика, откройте «Системные настройки» → «Конфиденциальность и безопасность», внизу нажмите «Всё равно открыть» и подтвердите паролем. Если Mac пишет, что программа «повреждена», откройте «Терминал», выполните команду и запустите снова:

```
xattr -cr "/Applications/Учебник101 Python.app"
```

**Linux.** Файл .deb: двойной щелчок или `sudo apt install ./uchebnik101-python-linux-amd64.deb`. Файл .AppImage: в свойствах файла разрешите запуск как программы (или `chmod +x`), затем двойной щелчок.

## Открывать .py двойным щелчком

**Windows:** правой кнопкой по .py → «Открыть с помощью» → «Выбрать другое приложение» → «Учебник101 Python», галочка «Всегда».
**Mac:** правой кнопкой по .py → «Свойства» → «Открывать в программе» → «Учебник101 Python» → «Заменить все».
**Linux:** после установки .deb программа уже есть в списке «Открыть с помощью».

---

Здесь только готовые установщики, они собираются автоматически.
