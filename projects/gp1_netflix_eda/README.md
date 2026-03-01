# GP1 — Netflix Shows: Exploratory Data Analysis (EDA)

**Роль в проекте:** очистка данных, EDA, feature engineering, интерпретация результатов.  
**Инструменты:** Python, pandas, numpy, matplotlib, seaborn (опционально plotly).

## Что сделано
- Приведение данных к единому формату (названия колонок, очистка строковых полей).
- Обработка дубликатов:
  - удаление полных дублей,
  - разбор дублей по `(title, release_year)` и выбор строки с меньшим числом пропусков.
- Анализ пропусков и обработка:
  - `ratinglevel` и `rating` — удаление строк (малый % пропусков),
  - `user_rating_score` — заполнение медианой внутри `ratingdescription` + небольшой noise (чтобы сохранить форму распределения).
- Feature engineering метрик «успеха»:
  - `SuccessIndex`, `rating_density`, `Balance`, `RA_Index`.
- Визуализации распределений и heatmap корреляций.
- Срез по популярным шоу (top `SuccessIndex`) по декадам.

## Как запустить
1. Откройте ноутбук: `notebooks/01_netflix_eda.ipynb`
2. Положите датасет рядом с ноутбуком или укажи путь в `pd.read_excel(...)`.