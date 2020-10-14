## Курсовой проект факультета "ИИ" (GeekBrains) по предмету "Библиотеки Python для Data Science: продолжение"

### Цель проекта - построить модель прогноза невыполнения долговых обязательств по текущему кредиту на основании имеющихся данных о клиентах банка. 

[Данные](https://github.com/lyutovad/GU_Course_project_DS/tree/main/Data)
-----
course_project_train.csv - обучающий датасет

course_project_test.csv - тестовый датасет


Целевая метрика

F1( 𝛽  = 1) > 0.5 при Precision > 0.5 и Recall > 0.5
Метрика оценивается по качеству прогноза для главного класса (1 - просрочка по кредиту)

### Для достижения поставленной цели необходимо решить следующие задачи

1. [Предобработка данных](http://):
- обработка категориальных переменных;
- обработка пропущенных значений;
- обработка выбросов

2. Построение новых признаков

3. Анализ данных и проверка статистических гипотез:
- анализ целевой переменной;
- анализ признакового пространства;
- выделение целевой переменной и групп признаков;
- отбор признаков для моделирования

4. Построение модели:
- нормализация данных;
- балансировка целевой переменной;
- разбиение данных на тестовую и валидационную части;
- построение и оценка базовых моделей;
- выбор наилучшей модели;
- настройка гиперпараметров

5. Оценка и интерпритация модели:
- построение финальной модели;
- оценка модели
