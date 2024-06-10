В ходе реализации проекта была создана модель, помогающая находить элементы, которые могут быть успешно исполнены спортсменом на соревновании.
Модель прогнозирует возможное выполнение тех или иных элементов программы на основе истории предыдущих выступлений и выполнения элементов на соревнованиях. 
Для реализации проекта была использована мультилейбл классификация с помощью CatBoostClassifier, одна модель для всех элементов.
Модель показала хорошие результаты, использовалась метрика F1-Score.

figure_skating_preprocessing.ipynb содержит предобработку данных

figure_skating.ipynb содержит обучение и тестирование модели CatBoostClassifier
