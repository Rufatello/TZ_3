Проект: Автоматическое определение критической позиции продуктов.
Проект предназначен для автоматического расчета поля "Критичная позиция" в файле "Задание 3", который содержит данные о продуктах, включая периоды производства и показатель ВГ.

Условия для определения критической позиции
Два периода производства: Если продукт производился в обоих периодах (период 1: "2023.01.01 - 2023.03.01", период 2: "2023.04.01 - 2023.06.01") и 
разница показателя ВГ между периодами больше 5, а показатель ВГ во 2 периоде меньше 90, то позиция критична (1).

Один период производства: Если продукт производился только в одном из периодов и показатель ВГ в этом периоде меньше 90, то позиция критична (1).

В остальных случаях позиция не критична (0).

Запуск проекта
Для запуска проекта можно использовать следующие методы:

Через исполняемый файл
Убедитесь, что файл "Задание 3" находится в той же директории, что и файл main.exe.

Запустите файл main.exe, расположенный в директории dist/main.exe.

В интегрированной среде разработки (IDE)

Откройте проект в вашей любимой IDE (например, PyCharm, Visual Studio Code и т.д.).

Убедитесь, что файл "Задание 3" находится в корне проекта.

Запустите файл main.py для запуска скрипта.
