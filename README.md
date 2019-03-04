##     
Комментарии преподавателя **в cpp файле** - для Вашего лучшего понимания проблем и ошибок!

# Прежде чем "демонстрировать" свои "крутейшие знания" с++ читать https://habrahabr.ru/post/347166/

|Прозвішча               |  экз|ДЗ1  | ДЗ2 | ДЗ3 | ДЗ4 | ДЗ5 |Диктант| ДЗ6 |КР1 | КР2| iтог |комментарии |
|:-----------------------|:---:|----:|:---:|----:|----:|----:|:-----:|----:|---:|---:|-----:|-----------:|
|Агейчик Анатолий        |  8  |     |     |     |     |     |       |     |    |    |      |            |
|Волкова Лиза            |  ?  |     |     |     |     |     |       |     |    |    |      |            |


# Обязательные требования ко всем лабам:

• Текст задания, которое выполняется надо продублировать в первых строках решения как комментарий       
также стоит реализовать вывод условия задачи как один из пунктов в меню (если создание меню есть в условии задачи)     
• в main() только объявления переменных и вызовы функций. Вся реализация функций ОТДЕЛЬНО.      
• имена переменных и функций должны соответствовать общепринятым нормам.

## Задание на 14.02 (указатели, одномерные массивы в heap )
Прочитать, скачать себе и распечатать хорошее краткое объяснение указателей с адреса http://www.math.spbu.ru/user/dlebedin/ncpp4.pdf

## Задание на 21.02 (указатели, одномерные массивы в heap )
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  3 файла с именами 0-1.cpp (тут решение 1-й задачи), 0-2.cpp (тут решение второй задачи), 0-3.cpp, 0-4.cpp)`

•	Размер массива N запрашивать у пользователя;      
•	выделение и контроль динамической памяти прямо в  main;      
•	в зависимости от задания создать одну или несколько функций для обработки массивов, которые передавать туда через указатели;     
•	организация циклов **с использованием указателей**, а не с помощью A[i];     

1. В массиве размера N, заполненного случ.числами от 0 до 10, подсчитать количество элементов, встречающихся более одного раза.     
2. В массиве размера N, заполненного случ.числами от 0 до 10, определить максимальную длину последовательности равных элементов.     
3. Массив чисел размера N проинициализировать случайными числами из промежутка от -N до N. Написать функцию циклического сдвига элементов массива вправо на k элементов.
4. Расположить в порядке возрастания элементы массива А(N), начиная с k-го элемента.

## Задание на 28.02 (функции для работы с одномерными массивами в heap )     
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  4 файла с именами 1-1.cpp (тут решение 1-й задачи), 1-2.cpp (тут решение второй задачи), 1-3.cpp)`

Разработать программу для работы с одним или несколькими одномерными массивами в heap, предусмотрев в ней:     
•	Размер массива N запрашивать у пользователя;      
•	выделение и контроль динамической памяти **в отдельной функции**, а не в main;      
•	разработать функции для инициализации, для ввода, для вывода массивов в heap;      
•	удаление динамической памяти после её использования **обязательно в отдельной функции**;      
•	организация циклов **обязательно с использованием указателей**;     
• одну или несколько функций для обработки массивов (для сортировки новый массив не создавать);   

1. Даны точки плоскости своими координатами в виде двух одномерных массивов (случайные числа). Точки плоскости рассортировать по возрастанию расстояния до прямой ax + by + c = 0.
2. Положительные элементы массива А(N) переставить в конец массива, сохраняя порядок следования. Отрицательные элементы расположить в порядке убывания. Дополнительный массив не использовать.
3. Элементы массива А(N), значения которых – простые числа, расположить в порядке возрастания, не нарушая порядка следования других элементов.


Подготовить для работы в аудитории функции для выделения памяти для **двумерного массива**, функции для инициализации, ввода, печати...      
**Прототипы функций:**     

* void give_memory(int**&, int, int)//первый способ. Подумайте, почему обязательно надо тут &
* int** give_memory(int, int)//второй способ. Подумайте, можно ли и безопасно ли тут напісать int**& give_memory     
* void init_array(int **,int,int)
* void print_array(int **,int,int)
* void free_array(int **,int)

## Задание на 7.03
1) Готовимся программировать динамические структуры данных (стек, дек, очередь). Читаем теорию http://learnc.info/adt/

2) Выбираем одну задачу по работе с массивами **в heap** из списка и реализуем её.      
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  1 файл с именами 2-1.cpp `      
**Попроще**       
• ( ________) В массиве А(N,М) найти номер строки, среднее арифметическое положительных элементов которой является наименьшим и поменять её с первой строкой.    
• (Rapinchuk) В массиве А(N,N) найти первую строку, не содержащую отрицательных элементов, и поменять её с последней строкой.       
• (________) В массиве А(N,М) найти строку, для которой количество перемен знаков максимально и поменять её с первой строкой.        
• (________) В массиве А(N,N) найти максимальные элементы нижнего и верхнего треугольников относительно главной диагонали и поменять местами строки в которых они находятся.       
•	(Malchikova) В массиве А(N,М) поменять местами строки, содержащие максимальный и минимальный элементы.        
•	(Шпаковский) В массиве А(N,М) часть строк состоит из нулей. удалить нулевые строки.       
•	(________) В массиве А(N,М) сменить знаки минимальных элементов и удалить строку с минимальным произведением элементов.       
•	(Гапанович) В массиве А(N,М) расположить строки в порядке возрастания их максимальных элементов.        
•	(________) В массиве А(N,М) расположить строки в порядке возрастания количества минимальных элементов в каждой строке.    
•	(________) В массиве А(N,M) переставить строки в порядке возрастания элементов последнего столбца.     
•	(________) В массиве А(N,M) переставить строки так, чтобы строка с максимальной суммой элементов стала первой строкой, а остальные строки расположить в порядке возрастания элементов первого столбца.     

**Посложнее немножко**       
• (________) В массиве А(N,M) расположить строки, стоящие после строки с первым максимальным элементом матрицы, в порядке возрастания количества чётных элементов в строке.      
• (Жилко) В массиве А(N,M) переставить столбцы так, чтобы столбец с максимальной суммой элементов стал первым, а остальные столбцы расположить в порядке возрастания элементов первой строки.        
• (Куделич)	В массиве А(N,M) расположить столбцы по возрастанию количества чётных элементов в столбце.        
• (Тухолко)	В массиве А(N,M) расположить столбцы по возрастанию значений минимальных элементов столбцов.        
• (Ковалевский) В массиве А(N,M) элементы столбцов, не содержащих нулевых элементов, расположить в порядке убывания, а сами столбцы расположить в порядке возрастания элементов первой строки.        
• (________)	В массиве А(N,M) расположить элементы каждого столбца в порядке возрастания модулей их отрицательных элементов, а сами столбцы расположить в порядке убывания  сумм их элементов.        
• (________)	В массиве А(N,M) расположить положительные элементы каждого столбца в порядке возрастания, а сами столбцы расположить в порядке убывания их первых максимальных элементов.        
• (________)	В массиве А(N,M) расположить в порядке возрастания элементы столбцов, максимальный элемент которых не превосходит заданную величину р, а сами столбцы расположить в порядке возрастания количества нечётных элементов в столбце.        
• (________)	В массиве А(N,M) расположить в порядке возрастания элементы столбцов, максимальный элемент которых не превосходит заданную величину р, а сами столбцы расположить в порядке возрастания количества перемен знаков в каждом столбце.        
• (Kisliakou)	В массиве А(N,M) расположить столбцы в порядке  возрастания количества нулевых элементов в каждом столбце.       
• (Збойчик)	В массиве А(N,М) удалить столбцы, все элементы которых являются простыми числами.       
• (Ageichik)	В массиве А(N,М) столбец с минимальным количеством нечетных элементов поменять местами с последним столбцом.       
• (Денис)	В каждом столбце массива А(N,М) после первого отрицательного элемента вставить максимальную цепочку из положительных элементов данного столбца. Расположить столбцы в порядке возрастания по количеству вставленных элементов. 

