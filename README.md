# Практическая работа №2 — Разведочный анализ данных (EDA)

**Студент:** Ашымбеков Акыл  
**Дисциплина:** Машинное обучение  
**Датасет:** Titanic

## Что сделано

- `df.info()`, пропуски, описательная статистика
- Гистограммы и boxplot
- Анализ категориальных признаков
- Корреляционная матрица и pairplot
- Поиск выбросов (IQR)
- Итоговый отчёт о проблемах данных

## Основные результаты

- В Fare 116 потенциальных выбросов (выше 65,6)
- Pclass и Fare: корреляция −0,55
- Дисбаланс классов: 61,6% / 38,4%

## Структура проекта

```text
Titanic_Practice_2/
├── data/
│   └── titanic.csv
├── notebooks/
│   └── practice_2.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Как запустить

1. Создать и активировать виртуальное окружение:

```bash
python3 -m venv venv
source venv/bin/activate
```

2. Установить библиотеки:

```bash
pip install -r requirements.txt
```

3. Открыть `notebooks/practice_2.ipynb` в VS Code или Jupyter и выполнить **Restart & Run All**.

## Технологии

Python, pandas, NumPy, matplotlib, seaborn, scikit-learn, Jupyter Notebook.
