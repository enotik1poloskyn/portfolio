## Нужно спрогнозировать уйдет ли клиент от оператора или нет.

<b>Стек:</b>
 - pandas
 - matplotlib
 - numpy
 -  Для обучения.
   -- sklearn
   -- lightgbm
   -- Catboost


Таблица <b>contract</b>

- customerID - id пользователя
- BeginDate - дата начала действия
- EndDate - дата окончания действия
- Type - Тип оплаты (раз в год или помесячно)
- PaperlessBilling - безбумажный расчетный лист
- PaymentMethod - тип платежа
- MonthlyCharges - расход за месяц
- TotalCharges - общие расходы

Таблица <b>personal</b>

- customerID - id пользователя
- gender - пол
- SeniorCitizen - пожилой гражданин
- Partner - партнер
- Dependents - иждивенцы

Таблица <b>internet</b>

- customerID - id пользователя
- InternetService - тип подключения
- OnlineSecurity - блокировка небезопасных сайтов
- OnlineBackup - Облачное хранилище файлов для резервного копирования данных
- DeviceProtection - антивирус
- TechSupport - Выделенная линия технической поддержки
- StreamingTV - Стриминговое телевидение
- StreamingMovies - каталог фильмов

Таблица <b>phone</b>

- customerID - id пользователя
- MultipleLines - Подключение телефонного аппарата к нескольким линиям одновременно
