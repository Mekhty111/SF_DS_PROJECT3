# Проект 3. Решение для соревнования [SF-DST] Booking reviews - Прогнозирование рейтинга отеля на Booking

## Оглавление  
[1. Описание проекта](#about)  
[2. Какой кейс решаем](#case)  
[3. Краткая информация о данных](#data_info)  
[4. Условия соревнования](#requirements)  
[5. Результат](#results)    
[6. Выводы](#finaly) 

<h2 id="about">Описание проекта:</h2>
Представьте, что вы работаете датасаентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов нахождения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель играет нечестно, и его стоит проверить.

Вам поставлена задача создать такую модель. Готовы приступить?



<h2 id="case">Какой кейс решаем?</h2>
✅ Мы решаем задачу регрессии, целью которой является предсказание оценки отеля на основе данных о текстовых отзывах рецензентов, оставленных в разные промежутки времени. Это позволяет анализировать клиентскую удовлетворённость, выявлять ключевые факторы, влияющие на рейтинг, и прогнозировать будущие оценки.

<h2 id="requirements">Условия соревновния:</h2>

- Данное соревнование является бессрочным и доступно для всех потоков.
- Срок выполнения соревнования устанавливается индивидуально в каждом потоке.
- Тестовая выборка представлена в LeaderBoard целиком.


  
<h2 id="metrics">Метрики качества</h2>

#### Метрика качества Результаты оцениваются по метрике MAPE 

#### Файл представления Для каждого **id** отеля в наборе тестовых данных вы должны предсказать рейтинг отеля для **reviewer_score** переменной. Файл должен содержать заголовок и иметь следующий формат: ``` reviewer_score,id 1,1 ```

<h2 id="practise">Что практикуем?</h2>
Обрабатывать датафрейм, очищать датафрейм от выбросов, применять различные методы визуализации, и анализировать полученный после предобработки датафрейм


<h2 id="data_info">Краткая информация о данных:</h2>

- :arrow_up:[Ноутбук проекта: ](PROJECT3/Project3.ipynb)
  
- :arrow_up:[Собственно сам датафрейм: ](https://drive.google.com/file/d/183i7HqZIizhg3u1ZCzYwo65TpeObBCMl/view?usp=sharing)

- :arrow_up:[Таблциа городов и координат их центра:](https://drive.google.com/file/d/183i7HqZIizhg3u1ZCzYwo65TpeObBCMl/view?usp=sharing](https://drive.google.com/file/d/19wdswoKYfq9YuC8Aj7uPMYCe3VBFGsE4/view?usp=sharing))

<h2 id="results">Результаты: </h2>  

:arrow_up:[Полученные графики анализа признаков: ](PROJECT3/Project3.ipynb#metrics)


<h2 id="finaly">Выводы: </h2>

:arrow_up:[Конец ноутбука-проекта: ](PROJECT3/Project3.ipynb)


Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️-дами
