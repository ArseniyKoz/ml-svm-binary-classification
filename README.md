# SVM для бинарной классификации

Pet-проект с обучением SVM, подбором гиперпараметров и сравнением метрик качества.

## Что сделано

- Подготовка признаков и разделение train/test.
- Обучение SVC с вероятностным выводом.
- GridSearchCV по гиперпараметрам с оценкой ROC-AUC.

## Стек

- Python
- NumPy
- Pandas
- scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Как запустить

`ash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook practice_5.ipynb
```

## Результаты

Получена рабочая SVM-модель с кросс-валидационным подбором параметров.

## Чему научился

- Строить устойчивый baseline через CV и поиск параметров.
- Контролировать обобщающую способность SVM.

## Ограничения и что улучшить

- Добавить сравнение с Logistic Regression и Gradient Boosting.

## Автор

Арсений Козлов - [github.com/ArseniyKoz](https://github.com/ArseniyKoz)

