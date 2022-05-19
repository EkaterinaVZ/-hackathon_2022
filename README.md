Межгалактический Хакатон 2022image
Задача Хакатона - разработать модель, которая будет обнаруживать цифровые и физические атаки на оборудование промышленного предприятия

Кибератака - это любой наступательный маневр, нацеленный на компьютерные информационные системы, компьютерные сети, инфраструктуру или персональные компьютерные устройства

Описание кейса:
Применить машинное обучение для решения задачи информационной безопасности: обнаружение атак на киберфизические системы. Это системы для решения критически важных задач, которые состоят из физических компонентов и цифровых алгоритмов.

...................................................................................................................................

Описание датасета
Набор данных, на которых происходит обучение и тестирование модели включает в себя как состояние оборудования и характеристики очищаемой воды, так и сетевой трафик. Атаки в обучающем наборе данных размечены вручную. С помощью размеченных данных вам нужно научиться определять атаки для тестового набора данных.

Описание модели
Классификацию производили с использованием следующих моделей машинного обучения

KNeighborsClassifier()
DecisionTreeClassifier()
RandomForestClassifier()
MLPClassifier(max_iter=500)
GaussianNB()
LinearDiscriminantAnalysis()
LinearDiscriminantAnalysis(solver='svd')
QuadraticDiscriminantAnalysis()
SVC()
LogisticRegression()
Настройка гиперпараметров проводились с помощью GridSearchCV. В целях продолжения эксперимента планируется применить случайный поиск/подбор CV гиперпараметров и с помощью optuna
ВСЕ МОДЕЛИ РАБОТАЮТ В СРЕДНЕМ С ТОЧНОСТЬЮ НЕ МЕНЕЕ 92
Сделаем воду чистой и улучшим экологию!
