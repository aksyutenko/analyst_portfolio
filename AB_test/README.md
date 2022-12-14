# Анализ результатов А/В тестирования для определения влияния нового шрифта на продажи

[Ссылка на тетрадь](https://github.com/aksyutenko/data_analyst_portfolio/blob/main/AB_test/AB_test.ipynb)

**Цель исследования**

Изучить поведение пользователей сайта продуктов питания и выполнить анализ результатов А/В тестирования введения нового шрифта в интерфейс.

**Задачи исследования**

- Подготовить данные и провести исследовательский анализ
- Проверить результаты А/В тестирования

**Использованные библиотеки**
- pandas
- math
- scipy
- plotly
- matplotlib

**Результат исследования**

- Проведен обзор данных, переименованы колонки, удалены дубликаты, изменен формат данных;
- В ходе первичного анализа данные очищены от событий попавших в выборку до начала эксперимента;
- При анализе воронки удалось выяснить что большинство пользователей покидает сайт еще до перехода к каталогу покупок;
- Проведен анализ отличий между тремя группами А/В тестирования, двумя контрольными и экспериментальной:
  - Между контрольными группами отличий не найдено, что говорит о верности методики формирования групп;
  - Между двумя контрольными и экспериментальной группами также не найдено отличий.
- Таким образом, можно утверждать что предлагаемые изменения не окажут значительного влияние на конверсию.
