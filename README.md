# Необычные шашки
## Описание
GUI-приложение для игры в шашки со специфической доской. Присутствует опция игры по сети для двух игроков. Приложение было разработано и написано в команде из трех человек, моя часть работы заключалась в написании части кода реализации сервера.
## Установка и компиляция
Для работы с приложением необходимо иметь установленную библиотеку wxWidgwets. Установить ее можно с помощью следующей команды:
```bash
libwxgtk2.8-dev libwxgtk2.8-dbg
```
Пример установки:
```bash
libwxgtk-media3.0-0v5 - wxWidgets Cross-platform C++ GUI toolkit (GTK+ media library runtime)
libwxgtk-media3.0-0v5-dbg - debugging symbols for the wxGTK media library
libwxgtk-media3.0-dev - wxWidgets Cross-platform C++ GUI toolkit (GTK+ media library development)
libwxgtk-webview3.0-0v5 - wxWidgets Cross-platform C++ GUI toolkit (webview library runtime)
libwxgtk-webview3.0-0v5-dbg - debugging symbols for the wxGTK webview library
libwxgtk-webview3.0-dev - wxWidgets Cross-platform C++ GUI toolkit (webview library development)
libwxgtk3.0-0v5 - wxWidgets Cross-platform C++ GUI toolkit (GTK+ runtime)
libwxgtk3.0-0v5-dbg - debugging symbols for the wxGTK GUI toolkit library
libwxgtk3.0-dev - wxWidgets Cross-platform C++ GUI toolkit (GTK+ development)
libwxgtk2.8-0 - wxWidgets Cross-platform C++ GUI toolkit (GTK+ runtime)
libwxgtk2.8-dev - wxWidgets Cross-platform C++ GUI toolkit (GTK+ development)
libwxgtk2.8-dbg - wxWidgets Cross-platform C++ GUI toolkit (GTK+ debug)
libwxgtk-media2.8-0 - wxWidgets Cross-platform C++ GUI toolkit (GTK+ media library runtime)
libwxgtk-media2.8-dbg - wxWidgets Cross-platform C++ GUI toolkit (GTK+ media library debug)
libwxgtk-media2.8-dev - wxWidgets Cross-platform C++ GUI toolkit (GTK+ media library development)
```
## Запуск
Для запуска игры для двух игроков потребуется три машины:
* машина-сервер;
* машина первого игрока;
* машина второго игрока;

Подключение происходит по локальной сети.

Оснавная часть пояснений содержится комментариях к ```wind.h```

### Порядок запуска

* Клиент:
```bash 
make
./comp1 wind
./wind
```

* Сервер:
```bash
./comp server
./server
```

