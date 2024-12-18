# 3DViewer v2.0

## Основная информация о программе

Данная программа предоставляет возможность просмотра 3D модели в каркасном виде. 
Данные модели хранятся в файле формата .obj. 

## Описание программы

- Программа разработана на языке C++ стандарта C++17.
- Сборка программы настроена с помощью Makefile со стандартным набором целей для GNU-программ: all, install, uninstall, clean, dvi, dist, tests. 
- Программа разработана в соответствии с принципами объектно-ориентированного программирования.
- Обеспечено полное покрытие unit-тестами модулей, связанных с загрузкой моделей и аффинными преобразованиями.
- Программа предоставляет возможность:
    - Загружать каркасную модель из файла формата obj (поддержка только списка вершин и поверхностей);
    - Перемещать модель на заданное расстояние относительно осей X, Y, Z;
    - Поворачивать модель на заданный угол относительно своих осей X, Y, Z;
    - Масштабировать модель на заданное значение.
- В программе реализован графический пользовательский интерфейс, на базе Qt.

**Графический пользовательский интерфейс содержит:**

    - Кнопку для выбора файла с моделью и поле для вывода его названия;
    - Зону визуализации каркасной модели;
    - Ползунок для перемещения модели;
    - Ползунок для поворота модели;
    - Ползунок для масштабирования модели; 
    - Информацию о загруженной модели — название файла, кол-во вершин и ребер.

- Программа реализована с использованием паттерна MVC
- Использованы три различных паттерна проектирования (стратегия, мост, посредник).
