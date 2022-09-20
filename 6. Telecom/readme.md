# Классификаиция клиентов телеком компании

## Описание проекта

Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».
В вашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы (из проекта курса «Статистический анализ данных»). Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Предобработка данных не понадобится — вы её уже сделали.  
Постройте модель с максимально большим значением accuracy. Чтобы сдать проект успешно, нужно довести долю правильных ответов по крайней мере до 0.75. Проверьте *accuracy* на тестовой выборке самостоятельно.


## План проекта

1. Импорт данных и изучение датасета   
2. Разделение исходных данных на обучающую, валидационную и тестовую выборки.  
3. Исследование качества разных моделей, с изменением гиперпараметров  
    3.1 Дерево решений  
    3.2 Cлучайный лес  
    3.3 Логистическая регрессия  
4. Проверка качества модели на тестовой выборке.  
5. Дополнительное задание: проверка модели на вменяемость.  
6. Выводы

## Итоги работы

В данном исследовании были рассмотрены модели 3 машинного обучения - *DecisionTreeClassifier*, *RandomForestClassifier* и *LogisticRegression*. Наибольшую точность показала модель *RandomForestClassifier*. 

## Cтэк

Python  
Pandas  
Matplotlib  
Scikit-learn  

