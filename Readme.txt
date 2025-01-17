Проект: Обучение с учителем: качество модели

Описание проекта:
Интернет-магазин «В один клик» заметил снижение активности покупателей. Для увеличения покупательской активности постоянных клиентов компания решила использовать персонализированные предложения. 

Постановка задачи:
Разработать модель, предсказывающую вероятность снижения покупательской активности клиентов в следующие три месяца.

Используемые модели и методы:
1. Сбор данных: 
   - Признаки коммуникации с клиентом.
   - Продуктовое поведение покупателя.
   - Покупательское поведение клиента.
   - Поведение покупателя на сайте.
2. Обработка данных:
   - Сбор и предобработка данных из четырех таблиц: market_file.csv, market_money.csv, market_time.csv, money.csv.
   - Объединение таблиц и корреляционный анализ признаков.
3. Моделирование:
   - Обучение моделей KNeighborsClassifier, DecisionTreeClassifier, LogisticRegression, SVC.
   - Подбор гиперпараметров с использованием GridSearchCV.
4. Оценка моделей:
   - Выбор лучшей модели на основе ROC-AUC и F1-score.
   - Анализ ошибок модели и построение precision-recall кривой.
5. Сегментация клиентов:
   - Выделение сегментов клиентов на основе результатов моделирования и данных о прибыли.

Результаты:
1. Лучшая модель: Логистическая регрессия показала наилучшие результаты по метрикам ROC-AUC (0.91) и F1-score (0.9).
2. Сегментация покупателей:
   - Very High: Наиболее активные и прибыльные покупатели с высокой вероятностью снижения активности.
   - High: Активные покупатели с меньшей вероятностью снижения активности.
   - Medium: Покупатели с умеренной активностью и потенциалом для повышения.
   - Low: Редкие покупатели с низкой прибыльностью и высокой вероятностью снижения активности.

Дополнительные предложения:
1. Программа лояльности: Вознаграждать клиентов за активность.
2. VIP-статус: Предоставлять дополнительные преимущества для ценных клиентов.
3. Обратная связь: Регулярно запрашивать обратную связь для улучшения качества обслуживания.

Вывод:
Проект успешно разработал модель для предсказания снижения покупательской активности, что позволяет интернет-магазину «В один клик» создавать персонализированные предложения и повышать лояльность клиентов.
