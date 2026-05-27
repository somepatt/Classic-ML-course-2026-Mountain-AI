<h1 align="center">🏔️ Classic ML Course 2026 — Mountain AI</h1>

<p align="center">
  <b>Практический курс по классическому машинному обучению за 12 уроков</b>
</p>

<p align="center">
  От анализа данных и baseline-моделей до бустинга, пайплайнов и финального ML-проекта.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/scikit--learn-ML-orange?style=for-the-badge&logo=scikit-learn" />
  <img src="https://img.shields.io/badge/pandas-Data%20Analysis-purple?style=for-the-badge&logo=pandas" />
  <img src="https://img.shields.io/badge/12-Lessons-success?style=for-the-badge" />
</p>

---

## О курсе

**Classic ML Course 2026 — Mountain AI** — это практический курс по классическому машинному обучению.

Главная идея курса — научиться не просто запускать модели, а проходить полный ML-пайплайн:

```text
data → analysis → preprocessing → model → validation → interpretation → final project
```

Курс рассчитан на студентов и начинающих ML-инженеров, которые уже знают основы Python и хотят научиться решать реальные ML-задачи с помощью классических алгоритмов.

---

## Что будет в курсе

В курсе мы разберём:

- как устроен ML-проект;
- как анализировать и чистить данные;
- как выбирать правильные метрики;
- как обучать baseline-модели;
- как работают линейные модели;
- как устроены деревья решений;
- зачем нужны ансамбли;
- как использовать Random Forest и Gradient Boosting;
- как строить preprocessing pipeline;
- как избегать data leakage;
- как делать финальный ML-проект.

---

## Для кого этот курс

Курс подойдёт, если ты:

- знаешь базовый Python;
- хочешь войти в machine learning;
- хочешь понять классические ML-алгоритмы;
- хочешь сделать первый ML-проект в портфолио;
- готовишься к стажировке или junior ML-позиции;
- хочешь системно разобраться в scikit-learn.

---

## Необходимые знания

Желательно знать:

- базовый Python;
- списки, словари, функции;
- основы NumPy;
- базовый pandas;
- школьную математику;
- базовую линейную алгебру будет плюсом.

Сложная математика не требуется. Все формулы будут объясняться через интуицию и практические примеры.

---

## Технологии

Основные инструменты курса:

| Инструмент | Для чего используется |
|---|---|
| Python | основной язык курса |
| NumPy | работа с массивами и вычислениями |
| pandas | анализ и обработка данных |
| matplotlib | визуализация |
| scikit-learn | классические ML-модели |
| CatBoost / XGBoost / LightGBM | градиентный бустинг |
| Jupyter Notebook | эксперименты и проекты |

---

## Результат после курса

После прохождения курса студент сможет:

- взять датасет и понять, что в нём происходит;
- подготовить данные для модели;
- выбрать метрику под задачу;
- обучить несколько ML-моделей;
- сравнить модели честно;
- подобрать гиперпараметры;
- собрать sklearn pipeline;
- объяснить результат модели;
- оформить полноценный ML-проект.

---

## Timeline курса

| Неделя | Тема | Главный результат |
|---:|---|---|
| 1 | ML Pipeline | Понимание структуры ML-проекта |
| 2 | EDA и обработка данных | Умение анализировать датасет |
| 3 | Метрики и валидация | Умение правильно измерять качество |
| 4 | Linear Regression | Первая полноценная regression-модель |
| 5 | Logistic Regression | Первая полноценная classification-модель |
| 6 | KNN, Naive Bayes, Baselines | Простые модели и baseline-мышление |
| 7 | Decision Trees | Интерпретируемые tree-based модели |
| 8 | Random Forest | Bagging и ансамбли |
| 9 | Gradient Boosting | Сильные модели для табличных данных |
| 10 | Feature Engineering | Улучшение качества через признаки |
| 11 | Unsupervised Learning | PCA, clustering, anomaly detection |
| 12 | Final Project | Готовый ML-проект в портфолио |

---

## Roadmap

```text
Python basics
    ↓
NumPy / pandas
    ↓
EDA and data cleaning
    ↓
Metrics and validation
    ↓
Linear models
    ↓
KNN and Naive Bayes
    ↓
Decision trees
    ↓
Random Forest
    ↓
Gradient Boosting
    ↓
Feature Engineering
    ↓
Pipelines
    ↓
Unsupervised Learning
    ↓
Final ML Project
```

---

# Программа курса

## Урок 1. Introduction to Machine Learning and ML Pipeline

**Главная идея:** машинное обучение — это не только модель, а полный процесс работы с данными.

### Темы

- Что такое machine learning
- Supervised learning
- Unsupervised learning
- Regression vs classification
- Train / validation / test split
- Overfitting и underfitting
- Общий ML pipeline

### Практика

- Загрузка датасета
- Train/test split
- Обучение первой простой модели
- Подсчёт первой метрики

### Результат урока

Студент понимает, как выглядит типичный ML-проект от данных до оценки качества.

---

## Урок 2. Data Analysis, EDA, Missing Values and Outliers

**Главная идея:** качество модели сильно зависит от качества данных.

### Темы

- Типы признаков
- Числовые признаки
- Категориальные признаки
- Пропуски
- Дубликаты
- Выбросы
- Корреляции
- Target leakage
- Базовая визуализация

### Практика

- Анализ датасета через pandas
- Поиск пропусков
- Анализ распределений
- Построение графиков
- Простая очистка данных

### Результат урока

Студент умеет открыть датасет, изучить его и подготовить к первой модели.

---

## Урок 3. Metrics and Validation

**Главная идея:** нельзя улучшать модель, если неправильно измеряешь качество.

### Темы

Regression metrics:

- MAE
- MSE
- RMSE
- R²

Classification metrics:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrix

Validation:

- Train/test split
- Cross-validation
- Stratified split
- Imbalanced datasets

### Практика

- Сравнение разных метрик
- Пример, где accuracy обманывает
- Cross-validation
- Анализ confusion matrix

### Результат урока

Студент умеет выбирать метрику под задачу и корректно валидировать модель.

---

## Урок 4. Linear Regression and Regularization

**Главная идея:** линейные модели — база классического машинного обучения.

### Темы

- Linear Regression
- MSE loss
- Интуиция градиентного спуска
- Ridge Regression
- Lasso Regression
- ElasticNet
- Bias-variance tradeoff

### Ключевые формулы

```text
y_hat = w^T x + b
```

```text
MSE = 1/n * sum((y_i - y_hat_i)^2)
```

### Практика

- LinearRegression
- Ridge
- Lasso
- Сравнение коэффициентов
- Влияние регуляризации

### Результат урока

Студент понимает, как работает линейная регрессия и зачем нужна регуляризация.

---

## Урок 5. Logistic Regression and Classification

**Главная идея:** логистическая регрессия — простой и сильный baseline для классификации.

### Темы

- Binary classification
- Sigmoid
- Probability prediction
- Log loss
- Decision threshold
- Precision-recall tradeoff
- Multiclass classification

### Ключевая формула

```text
p(y = 1 | x) = sigmoid(w^T x + b)
```

### Практика

- LogisticRegression
- Confusion matrix
- Изменение threshold
- Precision и recall
- ROC-AUC

### Результат урока

Студент умеет решать задачу классификации и анализировать ошибки модели.

---

## Урок 6. KNN, Naive Bayes and Baseline Models

**Главная идея:** перед сложными моделями нужно уметь строить простые baseline.

### Темы

- K-nearest neighbors
- Расстояния между объектами
- Feature scaling
- Curse of dimensionality
- Naive Bayes
- Dummy classifiers
- Baseline thinking

### Практика

- KNN classifier
- Подбор числа соседей
- Влияние StandardScaler
- Сравнение KNN и Logistic Regression
- Простые baseline-модели

### Результат урока

Студент понимает, зачем нужны baseline-модели и почему scaling важен для distance-based методов.

---

## Урок 7. Decision Trees

**Главная идея:** деревья решений интерпретируемы и лежат в основе многих сильных моделей.

### Темы

- Decision tree structure
- Splitting criteria
- Gini impurity
- Entropy
- Information gain
- Max depth
- Min samples leaf
- Overfitting in trees

### Ключевые формулы

```text
Gini = 1 - sum(p_k^2)
```

```text
Entropy = -sum(p_k * log(p_k))
```

### Практика

- DecisionTreeClassifier
- Визуализация дерева
- Переобучение глубоких деревьев
- Подбор max_depth
- Интерпретация дерева

### Результат урока

Студент понимает, как дерево принимает решения и почему его нужно ограничивать.

---

## Урок 8. Random Forest and Ensemble Learning

**Главная идея:** ансамбли объединяют много моделей и дают более стабильный результат.

### Темы

- Ensemble learning
- Bagging
- Bootstrap
- Random Forest
- Feature randomness
- Variance reduction
- Feature importance
- Out-of-bag score

### Практика

- Decision Tree vs Random Forest
- RandomForestClassifier
- Feature importance
- Подбор числа деревьев
- Подбор max_depth

### Результат урока

Студент понимает, почему Random Forest обычно стабильнее одного дерева.

---

## Урок 9. Gradient Boosting, XGBoost, LightGBM and CatBoost

**Главная идея:** градиентный бустинг — один из самых сильных методов классического ML для табличных данных.

### Темы

- Boosting idea
- Bagging vs Boosting
- Sequential error correction
- Learning rate
- Number of estimators
- Tree depth
- Overfitting in boosting
- CatBoost for categorical features

### Ключевая формула

```text
F_m(x) = F_{m-1}(x) + eta * h_m(x)
```

### Практика

- GradientBoostingClassifier / Regressor
- CatBoost или XGBoost
- Сравнение с Random Forest
- Подбор гиперпараметров
- Таблица качества моделей

### Результат урока

Студент умеет использовать бустинг и понимает главные гиперпараметры.

---

## Урок 10. Feature Engineering and Preprocessing Pipelines

**Главная идея:** хорошие признаки часто дают больший прирост качества, чем смена модели.

### Темы

- One-hot encoding
- Ordinal encoding
- Target encoding
- Feature scaling
- Log-transform
- Binning
- Interaction features
- Datetime features
- Pipeline
- ColumnTransformer
- Data leakage prevention

### Практика

- Полный sklearn Pipeline
- Обработка числовых признаков
- Обработка категориальных признаков
- ColumnTransformer
- Обучение модели внутри pipeline

### Результат урока

Студент умеет собирать аккуратный preprocessing pipeline без data leakage.

---

## Урок 11. Unsupervised Learning: PCA, Clustering and Anomaly Detection

**Главная идея:** не все ML-задачи имеют разметку.

### Темы

- Dimensionality reduction
- PCA
- Explained variance
- KMeans
- DBSCAN
- Hierarchical clustering
- Silhouette score
- Anomaly detection

### Практика

- PCA для визуализации
- KMeans clustering
- Выбор числа кластеров
- Silhouette score
- Поиск аномалий

### Результат урока

Студент понимает базовые методы unsupervised learning и где их применять.

---

## Урок 12. Final ML Project

**Главная идея:** собрать все темы курса в один законченный проект.

### Что должен сделать студент

- Выбрать или получить датасет
- Сформулировать ML-задачу
- Сделать EDA
- Подготовить признаки
- Обучить baseline
- Обучить несколько моделей
- Сравнить метрики
- Выбрать лучшую модель
- Объяснить результат
- Оформить notebook и короткую презентацию

### Финальный результат

- Clean Jupyter Notebook
- Таблица сравнения моделей
- Визуализации
- Выводы
- Финальная презентация

---

# Финальный проект

## Требования к проекту

Хороший финальный проект должен содержать:

- problem statement;
- dataset description;
- exploratory data analysis;
- preprocessing;
- baseline model;
- at least three different ML models;
- validation strategy;
- metric comparison;
- interpretation of results;
- final conclusion.

## Пример структуры проекта

```text
final_project/
├── data/
├── notebooks/
├── src/
├── report.md
└── presentation.pdf
```

---

# Формат занятий

Рекомендуемая структура каждого урока:

| Блок | Время |
|---|---:|
| Теория и формулы | 30-60 минут |
| Семинар | 15-20 минут(если останется время) |

---

# Домашние задания

Лучший формат домашних заданий — сквозной проект, который постепенно улучшается каждую неделю.

Пример развития проекта:

| Урок | Домашнее задание |
|---:|---|
| 1 | Выбрать датасет и поставить задачу |
| 2 | Сделать EDA и очистку данных |
| 3 | Выбрать метрики и стратегию валидации |
| 4 | Обучить линейную модель |
| 5 | Обучить классификационную модель |
| 6 | Построить baseline |
| 7 | Обучить Decision Tree |
| 8 | Обучить Random Forest |
| 9 | Обучить Gradient Boosting |
| 10 | Собрать Pipeline |
| 11 | Добавить PCA / clustering analysis |
| 12 | Оформить финальный проект |

---

# Философия курса

> Сначала пойми данные, потом выбирай модель.

Курс строится вокруг практического подхода:

- не просто запоминать алгоритмы;
- понимать, когда и зачем их использовать;
- честно сравнивать модели;
- правильно валидировать результат;
- уметь объяснить свои решения.

---

# Будущая структура репозитория

Пока вся информация находится в одном `README.md`.

Позже репозиторий можно расширить так:

```text
Classic-ML-course-2026-Mountain-AI/
├── README.md
├── lessons/
│   ├── lesson-01-ml-pipeline/
│   ├── lesson-02-eda/
│   ├── lesson-03-metrics-validation/
│   ├── lesson-04-linear-regression/
│   ├── lesson-05-logistic-regression/
│   ├── lesson-06-knn-naive-bayes/
│   ├── lesson-07-decision-trees/
│   ├── lesson-08-random-forest/
│   ├── lesson-09-gradient-boosting/
│   ├── lesson-10-feature-engineering/
│   ├── lesson-11-unsupervised-learning/
│   └── lesson-12-final-project/
├── homework/
├── notebooks/
├── projects/
├── datasets/
└── assets/
```

---

# Author

Created by [@somepatt](https://github.com/somepatt).

---

<p align="center">
  <b>Classic ML is the foundation. Deep Learning comes after.</b>
</p>
