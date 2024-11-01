## Mob_game_app
⚒️ `Стек: python, pandas, numpy, seaborn, matplotlib, requests, urlencode, Jupyter  Notebook`

### Реализация проекта:
1. Использовала API для загрузки данных. 
2. Провела предварительный анализ (EDA) и предобработку данных
3. Написала универсальный скрипт, позволяющий сформировать когорты по требуемым параметрам: даты начала и окончания формирования когорт, а также периоды для расчета retention
4. С помощью библиотеки seaborn визуализировала когортный анализ в виде графика

### A/B тестирование:
1. Рассчитала и проанализировала продуктовые метрики (конверсия CR, ARPPU, ARPU)
2. Проанализировала результаты А/B-теста с использованием тестов на нормальность распределений средних и стат значимость
3. Выводы:  
3.1. T-test не выявил стат. значимых различий ARPPU и ARPU между контрольной и тестовой группами.   
3.2. Хи-квадрат показал, что конверсия выше у контрольной группы, что можно признать стат. значимым различием.   
3.3. Следует проверить дизайн эксперимента и работу сплит-системы, проверить корректность предоставлений равных акций двум группам, а пока тестовой вариант не стоит выкатывать в продакшн версию.
