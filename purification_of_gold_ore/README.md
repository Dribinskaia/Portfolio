# Прогноз концентрации золота в процессе его очистки
__Задача:__
Создание модели для промышленной компании, которая будет предсказывать коэффициент восстановления золота из золотосодержащей руды

__Данные:__
Использованы данные с различными параметрами золотосодержащей руды на разных стадиях производственного процесса по очистке.

__Выводы:__
В ходе анализа данных было выявлено, что некоторые замеряемые в ходе производственного процесса параметры коррелируют друг с другом, что потребовало удаления части параметров из обучающей выборки во избежание утечки данных. Среди обученных моделей наилучший результат показала модель Дерева решений, рекомендованная для внедрения. 

__Используемые библиотеки:__
*python, pandas, matplotlib, numpy, scikit-learn*
