# Проект "Анализ сети фитнес-центров"
## Данные
* `пол`
* `живет ли рядом`
* `сотрудник ли компании-партнера`
* `пользовался ли промо`
* `оставил ли телефон`
* `возраст`
* `месяцы с последнего обращения`
* `срок абонемента в месяцах`
* `месяцев до конца абонемента`
* `посещал ли групповые занятия`
* `частота посещений в неделю за все время`
* `частота посещений в неделю за последний месяц`
* `выручка за доп. услуги за все время`
* `факт оттока`
## Описание проекта
Cеть фитнес-центров хочет снизить уровень оттока клиентов
## Цель проекта 
Провести анализ и подготовить план действий по удержанию клиентов, а именно: 
* научиться прогнозировать вероятность оттока на следующий месяц для каждого клиента
* сформировать портреты клиентов
* выделить признаки, наиболее сильно влияющие на отток
* сформулировать основные выводы и разработать рекомендации по повышению качества работы с клиентами
## Используемые библиотеки
* pandas
* matplotlib.pyplot
* seaborn
* sklearn.model_selection.train_test_split
* sklearn.linear_model.LogisticRegression
* sklearn.ensemble.RandomForestClassifier
* sklearn.metrics.accuracy_score
* sklearn.metrics.precision_score
* sklearn.metrics.recall_score
* sklearn.metrics.f1_score
* sklearn.preprocessing.StandardScaler
* scipy.cluster.hierarchy.dendrogram, linkage
* scipy.cluster.hierarchy.linkage
* sklearn.cluster.KMeans
* warnings
