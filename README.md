# ShelterAnimals_KaggleCompetition
## Использованные технологии и библиотеки:
Python, pandas, numpy, sklearn.pipeline, seaborn, matplotlib, sklearn.impute,  sklearn.preprocessing, sklearn.utils.validation, sklearn.model_selection, sklearn.metrics,  GradientBoostingClassifier, GridSearchCV, RandomForestClassifier, LogisticRegression, LabelEncoder.

## Описание:
Проект был реализован в рамках kaggle-соревнования по определению судьбы домашних животных, попавших в приют. 
Во время подготовки к анализу были написаны парсер-функции для преобразования определенных типов данных в необходимый формат. Далее была проведена работа с фичами в том числе с помощью средств визуализации - преобразование данных к нужным типам и feature engineering (разработка признаков) и исследовательский анализ данных (EDA). Далее было проведено обучение моделей, таких как GradientBoostingClassifier, RandomForestClassifier + GridSearchCV (для выявления лучших гиперпараметров), RandomForestClassifier + LogisticRegression на отобранных признаках. На основании лучшей модели - RandomForestClassifier была определена важность признаков. В конце был сформирован прогноз для тестового набора данных.

## Результат:
В результате проведенного анализа было выявлено, что наиболее важным признаком был час, в который животное покидало приют. Этот час передавался в неназванном столбце с среди прочих временных данных.
F1 Score составил 0,67 на тестовых данных, что являлось одним из наиболее высоких результатов среди участников.

## Ссылка на проект:
[View _Shelter Animals_Kaggle_Competition Notebook](./ShelterAnimals_KaggleCompetition_UrusovaEV.ipynb)
