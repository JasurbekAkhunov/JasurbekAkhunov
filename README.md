<h1 align="center">Жасурбек Ахунов</h1>
<p align="center">
  <b>Data Scientist</b> · Python · ML · SQL · PySpark · PyTorch<br/>
  <sub>Специалист по Data Science (расширенный курс), Яндекс Практикум</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/CatBoost-FFCC00?style=flat"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/>
</p>

---

Решаю задачи анализа данных и машинного обучения: от предобработки и исследовательского анализа до обучения моделей и перевода метрик в деньги заказчика. Работаю с табличными данными, SQL-витринами, распределёнными вычислениями и нейросетями.

**Открыт к предложениям:** удалённая работа, полная и частичная занятость, проектная работа. Английский — **C1**.

---

## Стек

| Направление | Инструменты |
|---|---|
| **Языки** | Python, SQL (PostgreSQL) |
| **Анализ данных** | pandas, NumPy, Matplotlib, Seaborn, SciPy |
| **Машинное обучение** | scikit-learn, CatBoost, imbalanced-learn, Optuna |
| **Глубокое обучение** | PyTorch |
| **Большие данные** | Apache Spark (PySpark, Spark SQL, MLlib), Hadoop / HDFS |
| **Инструменты** | Git, GitHub, Jupyter, SQLAlchemy |

## Что умею

- **Аналитика:** предобработка и очистка данных, EDA, поиск и обоснование аномалий, продуктовые метрики (конверсия, воронки, ARPU/ARPPU, LTV, ROI, Retention и Churn), когортный анализ.
- **Статистика:** проверка гипотез и A/B-тесты (расчёт длительности заранее, ошибки I и II рода, корректная интерпретация p-value), доверительные интервалы, bootstrap для оценки рисков.
- **Машинное обучение:** полный цикл — подготовка признаков без утечек, работа с дисбалансом классов, подбор гиперпараметров (GridSearchCV / Optuna), выбор метрики под бизнес-задачу, интерпретация моделей (feature importance, permutation importance, SHAP).
- **SQL:** сложные выборки, оконные функции, CTE, когортные витрины, выгрузка результатов в pandas через SQLAlchemy.
- **Big Data:** обработка данных и обучение моделей на PySpark.

## Проекты

### Машинное обучение

| Проект | Задача | Стек |
|---|---|---|
| [**hr-analytics-ml**](https://github.com/JasurbekAkhunov/hr-analytics-ml) | Две модели для HR: прогноз удовлетворённости (SMAPE ≤ 15%) и вероятности увольнения (ROC-AUC ≥ 0.91). Прогноз первой модели использован как признак во второй | sklearn, Ridge, DecisionTree, RandomForest, пайплайны |
| [**customer-activity-prediction**](https://github.com/JasurbekAkhunov/customer-activity-prediction) | Предсказание снижения покупательской активности клиентов интернет-магазина, сегментация покупателей под персональные предложения | sklearn, бинарная классификация |
| [**well-location-ml**](https://github.com/JasurbekAkhunov/well-location-ml) | Выбор региона для нефтедобычи: bootstrap 1000 итераций, доверительный интервал прибыли, отбор региона с риском убытка < 2.5% | LinearRegression, bootstrap |
| [**california-housing-spark**](https://github.com/JasurbekAkhunov/california-housing-spark) | Прогноз стоимости жилья на распределённых данных, сравнение моделей на всех признаках и только на числовых (RMSE 67 713 против 68 813) | PySpark, Spark MLlib |
| [**cow-selection-ml**](https://github.com/JasurbekAkhunov/cow-selection-ml) | Отбор коров для покупки: регрессия удоя + классификация вкуса молока, ручное устранение нелинейности признаков | sklearn, LinearRegression, LogisticRegression |

### Аналитика и статистика

| Проект | Задача |
|---|---|
| [**real-estate-analysis**](https://github.com/JasurbekAkhunov/real-estate-analysis) | Объявления о продаже квартир в Санкт-Петербурге: факторы цены, скорость продажи, зависимость от удалённости от центра |
| [**gofast-analysis**](https://github.com/JasurbekAkhunov/gofast-analysis) | Сервис аренды самокатов: расчёт выручки по тарифам и проверка статистических гипотез о пользователях с подпиской и без |
| [**credit-risk-analysis**](https://github.com/JasurbekAkhunov/credit-risk-analysis) | Надёжность заёмщиков: влияние семейного положения, детей, дохода и цели кредита на возврат в срок |
| [**russian-cinema-analysis**](https://github.com/JasurbekAkhunov/russian-cinema-analysis) | Российский кинопрокат: тренды, господдержка, сборы |

### SQL

| Проект | Задача |
|---|---|
| [**sql-venture-investments**](https://github.com/JasurbekAkhunov/sql-venture-investments) | Венчурный рынок и M&A-сделки: агрегации, JOIN, CTE, оконные функции, сводные аналитические таблицы. С ER-диаграммой базы |
| [**DVD-rental-DateBase**](https://github.com/JasurbekAkhunov/DVD-rental-DateBase) | Запросы к базе проката DVD |

### Продукт

| Проект | Задача | Стек |
|---|---|---|
| [**fintrack-ai**](https://github.com/JasurbekAkhunov/fintrack-ai) | Трекер личных финансов с интеграцией LLM — доведён до работающего приложения | React, Vite, Firebase, Groq |

### Тестовые задания

| Проект | Задача |
|---|---|
| [**effective-mobile-junior-da-test**](https://github.com/JasurbekAkhunov/effective-mobile-junior-da-test) | Тестовое на Junior Data Analyst: теория вероятностей, алгоритмические задачи на Python, SQL с оконными функциями, статистика и вопросы по ML |

---

## Связь

<p>
  <a href="mailto:nasajasa5070@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/jasurbek-akhunov-945a69372"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
</p>
