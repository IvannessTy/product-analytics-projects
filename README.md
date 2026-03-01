# Product Analytics Projects

## Проекты

### 1) GP1 — Netflix Shows: EDA + Feature Engineering  
- Очистка данных, исследовательский анализ, метрики “успешности” контента.  
- Файл: `notebooks/01_netflix_eda.ipynb`  
- Подробнее: `projects/gp1_netflix_eda/README.md`

### 2) GP2 — MOEX: Scraping & API Market Overview  
- Сбор котировок через MOEX ISS API + web-scraping, недельные доходности, риск/доходность метрики, корреляции.  
- Файл: `notebooks/02_moex_scraping_api_market_overview.ipynb`  
- Подробнее: `projects/gp2_moex_scraping/README.md`

### 3) GP3 — A/B Test: Landing Page  
- Подготовка данных A/B-теста, EDA, z-test для долей, bootstrap CI, вывод для продуктового решения.  
- Файл: `notebooks/03_ab_test_landing_page.ipynb`  
- Подробнее: `projects/gp3_ab_testing/README.md`

## Структура портфолио
```
│   README.md
│   requirements.txt
│
├───notebooks
│       01_netflix_eda.ipynb
│       02_moex_scraping_api_market_overview.ipynb
│       03_ab_test_landing_page.ipynb
│
└───projects
    ├───gp1_netflix_eda
    │       README.md
    │
    ├───gp2_moex_scraping
    │       README.md
    │
    └───gp3_ab_testing
            README.md

```

## Как запустить локально
1. Установить необходимые зависимости
```bash
pip install -r requirements.txt
```
2. Открыть нужный notebook для просмотра