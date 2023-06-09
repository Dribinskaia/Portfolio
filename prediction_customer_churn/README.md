# Прогнозирование оттока клиентов
__Задача:__\
Построить модель, которая будет предсказывать, уйдет клиент банка или нет.

__Данные:__\
В наличии исторические данные о поведении клиентов и расторжении договоров с банком.

__Выводы:__\
Поскольку в данных присутствовал дисбаланс классов, в ходе исследования строились модели с разными способами борьбы с дисбалансом: как с помощью апсэмплинга, так и с помощью параметра class_weight='balanced'. Кроме того, оценивалось качество моделей, не учитывающих дисбаланс классов.\
В результате в качестве модели, рекомендованной для внедрения, отобрана модель случайный лес с числом деревьев 30 и глубиной 9, с балансировкой классов.

__Используемые библиотеки:__\
*pandas, matplotlib, scikit-learn*
