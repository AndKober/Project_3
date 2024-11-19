# Проект 3. EDA. Разведывательный анализ данных - отзывы об отелях на **Booking**

## Оглавление  
[1. Описание проекта](README.md#Описание-проекта)  
[2. Какой кейс решаем?](README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](README.md#Этапы-работы-над-проектом)  
[5. Результаты](README.md#Результаты)    
[6. Выводы](README.md#Выводы)    

### Описание проекта    
Учебный проект по разведывательному анализу данных реализованный в виде соревнования на Kaggle. [здесь](https://github.com/AndKober/Project_3/blob/master/project-3.ipynb)

:arrow_up:[к оглавлению](README.md#Оглавление)


### Какой кейс решаем?    
Я работаю дата-сайентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов обнаружения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель ведёт себя нечестно, и его стоит проверить.

**Метрика качества**     
- Качество кода (соблюдение стандартов оформления PEP-8, комментирование кода, README к проекту). Оформление проекта на GitHub, GitLab, Kaggle;
- Для оценки качества модели — точности прогнозов, сделанных моделью, — мы будем использовать метрику, которая называется MAPE (mean absolute percentage error), средняя абсолютная процентная ошибка.

**Что практикуем**     
- создаем свою первую модель, основанную на алгоритмах машинного обучения;
- принимаем участие в соревновании на Kaggle;
- «подготавливаем» данные, чтобы модель работала лучше.


### Краткая информация о данных
База данных содержит сведения об отзывах на отели на сайте *Booking*. В представленной ее части 515 000 отзывов.
Первоначальная версия датасета содержит 17 полей со следующей информацией:
- hotel_address — адрес отеля;
- review_date — дата, когда рецензент разместил соответствующий отзыв;
- average_score — средний балл отеля, рассчитанный на основе последнего комментария за последний год;
- hotel_name — название отеля;
- reviewer_nationality — страна рецензента;
- negative_review — отрицательный отзыв, который рецензент дал отелю;
- review_total_negative_word_counts — общее количество слов в отрицательном отзыв;
- positive_review — положительный отзыв, который рецензент дал отелю;
- review_total_positive_word_counts — общее количество слов в положительном отзыве.
- reviewer_score — оценка, которую рецензент поставил отелю на основе своего опыта;
- total_number_of_reviews_reviewer_has_given — количество отзывов, которые рецензенты дали в прошлом;
- total_number_of_reviews — общее количество действительных отзывов об отеле;
- tags — теги, которые рецензент дал отелю;
- days_since_review — количество дней между датой проверки и датой очистки;
- additional_number_of_scoring — есть также некоторые гости, которые просто поставили оценку сервису, но не оставили отзыв. Это число указывает, сколько там действительных оценок без проверки.
- lat — географическая широта отеля;
- lng — географическая долгота отеля.
  
:arrow_up:[к оглавлению](README.md#Оглавление)


### Этапы работы над проектом  
1. Знакомство с данными
2. Очистка данных
3. Исследование данных
4. Генерация признаков
5. Отбор признаков
6. Преобразование признаков
7. Вычисление метрики MAPE
  
:arrow_up:[к оглавлению](README.md#Оглавление)


### Результаты:  
В ходе проекта проведена подготовка данных для обучения алгоритма по определению рейтинга отеля исходя из отзыва о нем. Данные очищены от дубликатов и пропусков, признаки преобразованы в числовые, обучена модель и расчитана метрика MAPE, которая составила 12,23 % на обучающем наборе данных. 

:arrow_up:[к оглавлению](README.md#Оглавление)


### Выводы:  
Проект показал важность разведывательного анализа данных, очистки данных и влияние создания новых признаков на качество модели. Участие в соревновании на платформе Kaggle позволило понять возможности различных дополнительных библиотек и оценить разнообразие возможных путей решения поставленной задачи, ознакамливаясь с решениями других участников соревнования.    
  
:arrow_up:[к оглавлению](README.md#Оглавление)
