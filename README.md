**В репозитории представлен пример вызова кода C++ из кода Python с применением CPython и PyBind.**

**IDE:** Visual Studio (2022). 

**Инструкция:**

Клонируйте. Откройте CppEmbeddingInPython.sln в Visual Studio. Удалите текущее локальное окружение env и поставьте новое, установив зависимости из requirements.txt. 

**Рабочая версия Python:** 3.10 x64.

**Requirements:**

pybind11==2.10.4

**Ветки:**

Console - Режим 0: сравнение скорости выполнение Native Python, CPython и PyBind. Режим 1: демонстрация передачи сообщения между компонентами в консоли.

DearPyGUI -  демонстрация передачи сообщения между компонентами в GUI от DearPyGUI (Node Editor).
