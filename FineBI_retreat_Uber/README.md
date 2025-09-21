# Проект работы в рамках ретрита FineBI: [Второе дыхание](https://bi.glowbyteconsulting.com/second-breath-day-1)

## Вводные данные.
В рамках данного [проекта](https://bi.glowbyteconsulting.com/second-breath-day-1) была проделана работа над [датасетом](https://www.kaggle.com/datasets/bhanupratapbiswas/uber-data-analysis/data):
**Uber Data Analysis🚗 🚕**

Выбор данного датасета был обоснован следующим:
  * возможностью применения описательной и диагностической аналитики не только в разрезе категориальных, качественных данных, но и анализа их динамики;
  * возможностью самостоятельного анализа данных, не взирая на примеры с данного ретрита.

## Результаты работы
В рамках данного проекта подготовлены:
  * Дашборт на основании выбранного [датасета](https://www.kaggle.com/datasets/bhanupratapbiswas/uber-data-analysis/data).
  * Процесс предобработки датасета для загрузки в FineBI с помощью Python: [ссылка](https://github.com/NovikovaMary/Pet_projects/blob/main/FineBI_retreat_Uber/preprocessing_Uber.ipynb).
  * Предобработанный [датасет](https://github.com/NovikovaMary/Pet_projects/blob/main/FineBI_retreat_Uber/UberDataset_new.xlsx)
  * Аналитическая записка: [ссылка на telegrapf](https://telegra.ph/Analitika-dannyh-Uber-2016-2017-gg-insajty-i-rekomendacii-09-18), согласно заданиям [ретрита](https://bi.glowbyteconsulting.com/second-breath-day-1)

## Общий вид дашборда.

![Вкладка 1. Основные показатели](https://i.postimg.cc/28MCpvQn/1.jpg)
*Вкладка 1. Основные показатели*

![Вкладка 2. Таблица. Для детального анализа.](https://i.postimg.cc/k4JmNyCP/2.jpg)
*Вкладка 2. Таблица. Для детального анализа.*

## Выводы по проделанной работе.
В данной работе была проведена [предобработка](https://github.com/NovikovaMary/Pet_projects/blob/main/FineBI_retreat_Uber/preprocessing_Uber.ipynb) исходного датасета языком Python.
В процессе разработки дашборта в FineBI:
* были созданы новые столбцы: День недели, Время поездки, Час заказа, Год-месяц заказа, в датасет для дальнейшего создания визуализации.
* были добавлены индиакторы: Кол-во заказов, Протяженность всего, Эффективность поездки, Скользящая средняя.
* добавлены визуальные компоненты: линейные, столбчатые диаграммы, пайчарт, Color Table.
* установлены Linkage, set Jump.
* установлены фильтры в Frozen Bar.

В результате проделанной работы были получены следующие выводы: [ссылка на telegrapf](https://telegra.ph/Analitika-dannyh-Uber-2016-2017-gg-insajty-i-rekomendacii-09-18), согласно заданиям ретрита.

В целом было много интересных функций и методов, возможных к применению в FineBI. Очень удобным показалось наличие готовых стилей дашбордов, что может быть удобным для создания быстрой отчетности.
