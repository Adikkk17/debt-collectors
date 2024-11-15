Документация коду для расчёта и прогнозирования ВВП на душу населения
Цель
Код выполняет следующие задачи:

Обрабатывает данные численности населения и ВВП из Excel-файлов.
Вычисляет ВВП на душу населения (отношение ВВП к численности населения за каждый год).
Строит прогноз ВВП на душу населения на 10 лет вперёд с использованием библиотеки Prophet.
Визуализирует прогноз и сохраняет результаты в Excel.
Используемые библиотеки
pandas: Для обработки табличных данных (чтение, очистка, обработка, анализ).
numpy: Для выполнения численных операций.
matplotlib: Для визуализации данных и прогноза.
Prophet: Для прогнозирования временных рядов.
Структура кода
Загрузка данных

Численность населения из файла "Численность населения-3.xlsx".
ВВП из листа "Инпут" файла "1. ВВП методом производства (4).xlsx".
Очистка данных

Удаление некорректных и пропущенных значений.
Преобразование года из строкового формата (например, "2010 год") в числовой.
Группировка данных по годам.
Расчёт ВВП на душу населения

Объединение данных численности населения и ВВП по годам.
Вычисление показателя:
ВВП на душу населения
=
ВВП
Численность населения
ВВП на душу населения= 
Численность населения
ВВП
​
 
Прогнозирование

Обучение модели Prophet на рассчитанных данных ВВП на душу населения.
Прогнозирование на 10 лет вперёд.
Визуализация и сохранение данных

Построение графиков прогноза и компонентов.
