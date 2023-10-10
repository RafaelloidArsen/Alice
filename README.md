# Alice
Бинарная классификация (модель logreg)
Данные: https://www.kaggle.com/competitions/catch-me-if-you-can-intruder-detection-through-webpage-session-tracking2/data
В обучающей выборке содержатся следующие признаки: 
- site1 – индекс первого посещенного сайта в сессии
- time1 – время посещения первого сайта в сессии
...
- site10 – индекс 10-го посещенного сайта в сессии
- time10 – время посещения 10-го сайта в сессии
- target – целевая переменная, 1 для сессий Элис, 0 для сессий других пользователей
Сессии пользователей выделены таким образом, что они не могут быть длиннее получаса или 10 сайтов.
То есть сессия считается оконченной либо когда пользователь посетил 10 сайтов подряд либо когда сессия заняла по времени более 30 минут.
