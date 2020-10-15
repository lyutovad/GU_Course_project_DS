## Курсовой проект факультета "ИИ" (GeekBrains) по предмету "Библиотеки Python для Data Science: продолжение"

### Цель проекта - построить модель прогноза невыполнения долговых обязательств по текущему кредиту на основании имеющихся данных о клиентах банка. 

[Данные](https://github.com/lyutovad/GU_Course_project_DS/tree/main/Data)
-----
course_project_train.csv - обучающий датасет

course_project_test.csv - тестовый датасет


#### Целевая метрика

F1( 𝛽  = 1) > 0.5 при Precision > 0.5 и Recall > 0.5

Метрика оценивается по качеству прогноза для главного класса (1 - просрочка по кредиту)

### Описание датасета

- Home Ownership - домовладение
- Annual Income - годовой доход
- Years in current job - количество лет на текущем месте работы
- Tax Liens - налоговые льготы
- Number of Open Accounts - количество открытых счетов
- Years of Credit History - количество лет кредитной истории
- Maximum Open Credit - наибольший открытый кредит
- Number of Credit Problems - количество проблем с кредитом
- Months since last delinquent - количество месяцев с последней просрочки платежа
- Bankruptcies - банкротства
- Purpose - цель кредита
- Term - срок кредита
- Current Loan Amount - текущая сумма кредита
- Current Credit Balance - текущий кредитный баланс
- Monthly Debt - ежемесячный долг
- Credit Score - оценка благонадежности клиента (скоринговый балл, полученный из другого источника)
- Credit Default - факт невыполнения кредитных обязательств (0 - погашен вовремя, 1 - просрочка)


## Для достижения поставленной цели необходимо решить следующие задачи

1. Предобработка данных:
- обработка категориальных переменных;
- обработка пропущенных значений;
- обработка выбросов

2. Построение новых признаков

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
