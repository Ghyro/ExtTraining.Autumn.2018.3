## ExtTraining.Autumn.2018.3

*- Форкнуть данный репозиторий.*

   ![](https://github.com/AnzhelikaKravchuk/ExtTraining.Autumn.2018.3/blob/master/Pictures/1.png)
        
*- Склонировать **свою ветку** к себе на десктоп.*

   ![](https://github.com/AnzhelikaKravchuk/ExtTraining.Autumn.2018.3/blob/master/Pictures/2.png)
        
*- Выполнить указанные ниже задачи, заролнив необходимыми функциональностью и изменениями только те проекты No#.Solution и No#.Solution.Console (No#.Solution.Tests), которые указаны в задниях.*

*- Синхронизировать локальные изменения с содержимым своего репозитория на gitub-e.*

*- Сделать pull request к данному репозиторию.*

   ![](https://github.com/AnzhelikaKravchuk/ExtTraining.Autumn.2018.3/blob/master/Pictures/3.png)

## Постановка заданий

1. Дана система типов (проект No1) для верификации пароля согласно некоторым фиксированным правилам и его сохранения, в случае валидности, в хранилище. Какие  проблемы возникнут при использовании данного кода, если множество клиентов класса PasswordCheckerService захотят его использовать для различных комбинаций условий валидации (существующих и новых), используя при этом различные хранилища? Выполнить рефакторинг данного кода, устранив обнаруженную проблему (решение поместить в проект No1.Solution). Проверить работу новой системы типов с помощью модульных тестов, тесты поместить в проект No1.Tests. 
2. Разработана система типов (проект No2), моделирующая работу фондовой биржы. Изменить код, используя механизм событий (решение поместить в проект No2.Solution), проверить работу новой системы типов в консоли (проект No2.Solution.Console). 
3. Разработана система типов (проект No3) для расчета различных вариантов среднего арифметического значения для набора вещественных чисел. Выполнить изменения кода с учетом возможности изменения/дополнения алгоритма подсчета среднего значения (решение поместить в проект No3.Solution), проверить работу новой системы типов для тестов из проекта No3.Solution.Tests (unit-тесты изменить для работы с новой 
системой типов). Предложить, *различные варианты* (как минимум два) решения данной задачи.
4. Разработана система типов (проект No4) для генерации файлов с рандомным содержимым. Изменить систему типов (решение поместить в проект No4.Solution), выделив необходимые/(ую) абстракции/(ю). Проверить работу новой системы типов в консоли (проект No4.Solution.Console).
5. Разработана система типов (проект No5) для описания документа - класс Document, состоящего из различного вида частей документа DocumentPart - BoldText, Hyperlink, PlainText (3 типа представлено только для краткости примера), части документа могут быть получены как часть публичного API класса Document (если есть такая необходимость). Какие проблемы возникнут при использовании данного кода, если часто будет возникать необходимость добавления конвертирования документа в новый формат (например, обычный текст, html, LaTeX и т.д.)? Пересмотреть реализацию типов, устранив обнаруженную проблему (решение поместить в проект No5.Solution), проверить работу новой системы типов в консоли (проект No5.Solution.Console).
6. Реализовать (решение поместить в проект No6.Solution) обобщенный генератор n-первых членов последовательности, заданной рекуррентной формулой для элементов типа T по правилу

        x(1) = a, x(2) = b, x(n + 1) = f(x(n), x(n - 1)), n = 2, 3, ...
    
Проверить работу построенного генератора (проект No6.Solution.Tests) на примере следующих последовательностей.

        1) x(1) = 1, x(2) = 1, x(n + 1) = x(n) +  x(n - 1), n = 2, 3, ... T - целочисленный тип;
        2) x(1) = 1, x(2) = 2, x(n + 1) = 6 * x(n) - 8 * x(n - 1), n = 2, 3, ... T - целочисленный тип;
        3) x(1) = 1, x(2) = 2, x(n + 1) = x(n) +  x(n - 1) / x(n), n = 2, 3, ... T - вещественный тип.
