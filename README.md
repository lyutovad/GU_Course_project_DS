## Курсовой проект факультета "ИИ" (GeekBrains) по предмету "Библиотеки Python для Data Science: продолжение"

### Цель проекта - построить модель прогноза невыполнения долговых обязательств по текущему кредиту на основании имеющихся данных о клиентах банка. 

[Данные](https://github.com/lyutovad/GU_Course_project_DS/tree/main/Data)
-----
course_project_train.csv - обучающий датасет

course_project_test.csv - тестовый датасет


#### Целевая метрика

F1( 𝛽  = 1) > 0.5 при Precision > 0.5 и Recall > 0.5

Метрика оценивается по качеству прогноза для главного класса (1 - просрочка по кредиту)

### Для достижения поставленной цели необходимо решить следующие задачи

1. [Предобработка данных](https://github.com/lyutovad/GU_Course_project_DS/tree/main/Data%20preprocessing):
- обработка категориальных переменных;
- обработка пропущенных значений;
- обработка выбросов

2. [Построение новых признаков](https://github.com/lyutovad/GU_Course_project_DS/tree/main/Feature%20engineering)

3. Анализ данных и проверка статистических гипотез:
- анализ целевой переменной;
- анализ признакового пространства;
- выделение целевой переменной и групп признаков;
- отбор признаков для построения модели

4. Построение модели:
- нормализация данных;
- разбиение данных на тестовую и валидационную части;
- балансировка целевой переменной;
- построение и оценка базовых моделей;
- выбор наилучшей модели;
- настройка гиперпараметров;
- построение финальной модели

5. Оценка и интерпритация модели:
- оценка важности параметров;
- оценка модели

6. Предсказание на тестовом датасете
