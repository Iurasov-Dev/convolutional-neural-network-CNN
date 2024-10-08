# convolutional-neural-network-CNN

Задание
Основные цели этого задания:

Научиться строить архитектуру модели сверточной нейронной сети

Научиться распознавать факты переобучения и недообучения модели

Научить бороться с переобучением и недообучением модели путем варьирования ее гиперпараметров

Научиться применять методы регуляризации для контроля переобучения

# Задача:

Построить модель полносвязной и сверточной нейронной сети, которая будет отличать маффин от чихуахуа. Необходимо достичь точности (Accuracy) на тестовом датасете  > 85 % с использованием любой архитектуры нейронной сети

Ссылка на датасет: Muffin vs chihuahua

План решения:

Загрузите данные так, как это было показано в видеоуроках или любым другим известным вам способом.

Проведите разбиение на тренировочные и тестовые данные.

Реализуйте функцию, в которой вы будете определять архитектуру полносвязной модели нейронной сети без использования слоев свёртки. Функция должна возвращать скомпилированную модель и иметь названия fcc_nn(fully-connected_neural_network). Обучите модель нейронной сети, измеряя точность на каждой эпохе с помощью тестовой выборки. 

Постройте график зависимости ошибки и точности полносвязной нейронной сети в зависимости от эпох.

Реализуйте функцию, в которой вы будете определять архитектуру полносвязной модели нейронной сети, с использованием слоев свёртки, регуляризации, препроцессинга изображений(Rescaling). Функция должна возвращать скомпилированную модель и иметь названия conv_nn(convolutional_neural_network). Обучите модель нейронной сети, измеряя точность на каждой эпохе с помощью тестовой выборки. 

Постройте график зависимости ошибки и точности свёрточной нейронной сети в зависимости от эпох.

Напишите вывод о том, при какой архитектуре нейронной сети качество получилось лучше и почему. Также укажите в выводе, какие методы препроцессинга, регуляризации или гиперпараметры дали наибольший прирост к точности.

Надеюсь, теперь вы с легкостью будете отличать маффин от чихуахуа!
