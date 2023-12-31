# Clustering
НИУ ВШЭ НН. Факультет ИМиКН. Методы анализа данных.  
Charge de cours:  В.А. Калягин.  

Домашнее задание 2: алгоритмы кластерного анализа  
Провести необходимые вычисления. Полученные результаты снабдить подробным комментарием. 

Цель работы: выполнить кластерный анализ данных. Провести сравнение различных алгоритмов кластеризации.  Объяснить результаты.  
Данные: в каждом варианте два набора данных X_4_i и  Y_4_i (i – номер варианта). Данные представляют собой векторы-строки в пространстве R4.   
Выполнить первичную обработку данных. Сделать первые выводы.

Подготовка данных: для каждого набора данных X_4_i и  Y_4_i  выбрать расстояние в R4 
- вычислить матрицу расстояний 
- перейти к матрице близостей (similarity matrix) и построить графовую модель данных (полный, неориентированный, простой взвешенный граф)

1. Кластеризация для числа кластеров k=2.
1.1 Найти разбиение каждого набора данных на 2 кластера с помощью следующих алгоритмов
- k-means
- EM алгоритм
- Threshold method=MST method=Single Linkage (выбрать любой из трех). Можно использовать матрицу близостей или матрицу расстояний. 
- Spectral algorithm (использовать матрицу близостей)
1.2 Сравнить попарно разбиения, полученные разными методами с помощью RAND индекса (вычислить RAND индекс для каждой пары разбиений). Дать комментарий к результату. 
1.3 Вычислить значение функции модулярности для каждого разбиения на 2 кластера из п.1.1.
1.4 Сделать общие выводы по возможности разбиения на 2 кластера каждого набора данных.

2. Кластеризация для числа кластеров k=3.
2.1 Найти разбиение каждого набора данных на 3 кластера с помощью следующих алгоритмов
- k-means
- EM алгоритм
- Threshold method=MST method=Single Linkage (выбрать любой из трех). Можно использовать матрицу близостей или матрицу расстояний. 
- Spectral algorithm (использовать матрицу близостей)
2.2 Сравнить попарно разбиения, полученные разными методами с помощью RAND индекса (вычислить RAND индекс для каждой пары разбиений). Дать комментарий к результату. 
2.3 Вычислить значение функции модулярности для каждого разбиения на 3 кластера из п.2.1.
2.4 Сделать общие выводы по возможности разбиения на 3 кластера каждого набора данных.

3. Общий случай.
- предложите (или найдите готовый) способ определения возможного числа кластеров в данных. Примените этот способ к каждому из заданных наборов данный. Сравните с вашими результатами п.1.4 и п.2.4
- Предложите (или найдите в литературе) какой-либо другой критерий качества кластеризации (отличный от модулярности). Сравните разбиения п.1.1 и п.2.1 по этому критерию. Дайте комментарий, как это согласуется с вашими выводами п.1.4 и п.2.4. 


