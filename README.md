# Клиент под контролем  
### Прогноз оттока клиентов телеком-компании (Выпускной проект Яндекс.Практикум)

![Python](https://img.shields.io/badge/Python-3.9.5-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-Gradient_Boosting-yellowgreen?style=for-the-badge)
![Accuracy](https://img.shields.io/badge/Accuracy-~93%25-brightgreen?style=for-the-badge)

Проект решает задачу бинарной классификации: **прогноз оттока клиентов** оператора связи «ТелеДом».  
Модель на основе **CatBoostClassifier** показывает **точность ~93%** на тестовых данных.

Цель проекта — построить модель, которая поможет маркетологам своевременно выявлять клиентов, склонных к уходу, и предлагать им персональные условия.

### 🚀 Основные результаты
- Лучшая модель: **CatBoostClassifier**
- Метрика на тесте: **Accuracy ≈ 0.93**, **ROC-AUC ≈ 0.91**
- Важнейшие признаки: длительность договора, общие расходы клиента, тип подписки.

### 📊 Превью результатов

<img src="screenshots/confusion_matrix.png" alt="Цены по удалённости от центра" width="500">

<img src="screenshots/feature_importance.png" alt="Цены по удалённости от центра" width="500">

### 🛠 Технологический стек
- **Python 3.9.5**
- **Библиотеки**: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, catboost
- **Jupyter Notebook**

### 📓 Ноутбук проекта
Полный анализ с исследовательским анализом данных (EDA), предобработкой, обучением моделей и выводами:

[Открыть ноутбук с интерактивными графиками (nbviewer)](https://nbviewer.org/github/Dayana373/Portfolio_Yandex/blob/4518223c1509ffa941e87acc8017c1c75f7f97b1/final_project.ipynb)

[Открыть ноутбук напрямую на GitHub](https://github.com/Dayana373/Portfolio_Yandex/blob/main/final_project.ipynb) (Единственный нюанс — графики Plotly в GitHub не отображаются)

### 📁 Данные
Данные предоставлены Яндекс.Практикумом:

[Скачать датасет](https://disk.yandex.ru/d/8hb_9fAZatuyMw)

### 👩‍💻 Автор
Диана Сергеева  
Data Scientist | Выпускница Яндекс.Практикум  
GitHub: [@Dayana373](https://github.com/Dayana373)


