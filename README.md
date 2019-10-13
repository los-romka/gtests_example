# gtests_example

Как настраивать На Windows 7~:

0. Клонируем этот репозиторий: `git clone https://github.com/los-romka/gtests_example`
1. Переходим в папку с проектом в Bash `cd gtests_example`.
2. Клонируем репозиторий googletest: `git clone https://github.com/google/googletest`
3. Устанавливаем Cygwin: https://www.cygwin.com/setup-x86_64.exe добавив пакеты make, gcc-core, gcc-g++, gdb.
4. Открываем прект `gtests_example` в CLion.
5. В CLion > File > Settings > Build, Execution, Deployment > Toolchains. Затем + и выбираем Cygwin. Выбираем путь, который указывали при установке.
6. В CLion справа вверху выбираем main для запуска главной программы и tests для запуска тестов.
7. Ещё можно нажать правой кнопкой мыши на файл tests.cpp и запустить всё тесты через IDE `Run All Tests in tests.cpp`
