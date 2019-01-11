# gtests_example

Как настраивать На Windows 7~:
1. Переходим в папку с проектом.
2. Клонируем репозиторий googletest: `git clone https://github.com/google/googletest`
3. Устанавливаем Cygwin: https://www.cygwin.com/setup-x86_64.exe добавив пакеты make, gcc-core, gcc-g++, gdb.
4. В CLion > File > Settings > Build, Execution, Deployment > Toolchains. Затем + и выбираем Cygwin. Выбираем путь, который указывали при установке.
5. В CLion справа вверху выбираем main для запуска главной программы и tests для запуска тестов.
