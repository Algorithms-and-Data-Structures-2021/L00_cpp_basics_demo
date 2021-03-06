# Основы C++ (Часть 0)

![Build status](https://github.com/Algorithms-and-Data-Structures-2021/L00_cpp_basics_demo/actions/workflows/cmake.yml/badge.svg)

Материалы занятия доступны по [ссылке](https://www.notion.so/L00-Introduction-to-C-689f613bb4d94b24b2f64bc3f1cf7c9d).

Рассмотрены следующие темы:
1. Что такое C++?
2. Препроцессинг, компиляция, компановка.
3. Структура программы: функция `main`.
4. Подключение заголовочных файлов (библиотек), директива `#nclude`.
5. Базовые (примитивные) типы данных и операции над ними. Оператор `sizeof`.
6. Операторы: арифметические, логические, отношения, тернарный.
7. Приведение типов в C++ и оператор `static_cast`.
8. Операторы ветвления `if-else`, `switch-case`.
9. Циклы `for`, `while`, `do-while`. Оператор `break` и `continue`.
10. Функции. Объявление и определение функций. Возвращаемый тип `void`. Оператор возврата `return`.

## Как запустить проект?

Самый простой способ запуска проекта - это использование онлайн IDE.

**Внимание!** Необходимо авторизоваться в Repl.it со своего GitHub аккаунта. 

[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://repl.it/github/Algorithms-and-Data-Structures-2021/L00_cpp_basics_demo)


Если Вы хотите внести изменения в проект и сохранить их у себя в репозитории, то Вам необходимо выполнить `Fork` проекта.
Подробные инструкции можно прочесть по [ссылке](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo).

1. Клонируете проект к себе на компьютер.
в терминале (консоли):
```shell
git clone https://github.com/Algorithms-and-Data-Structures-2021/L00_cpp_basics_demo.git
```
или через среду разработки, клиента Git (например, [Git for Windows](https://git-scm.com/download/win) или [GitHub Desktop](https://desktop.github.com/)).

2. Импортируете/открываете проект в среде разработки (как CMake проект, см. [здесь](https://www.jetbrains.com/help/clion/quick-cmake-tutorial.html)).

3. Запуск программы осуществляется в среде разработки.

Ручная сборка проекта в терминале:
```shell
mkdir build
cd build
cmake ..
cmake --build .
cd Debug
<program_name>.exe
```
