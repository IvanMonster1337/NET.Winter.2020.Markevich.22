# Day 22
* Create table of records type of T
  * Для набора элементов типа T  (IEnumeable<T>), где состояние объектов типа T описывается набором публичных свойств, имеющих только тип даты, числовой, строковый и символьный,  реализовать возможность записи  в табличном виде  в текстовый поток.

  * Количество столбцов в таблице определяется количеством публичных свойств каждой записи. Ширина каждого столбца определяется максимальным количеством символов,  необходимым для записи в поток отдельного свойства. При этом, числа  и даты должны быть выровнены по правому краю, строки и символы - по левому.

  * Проверить работу разработанной функциональности на примере класса FileCabinetRecord (Ссылки на внешний сайт.), используя вывод в текстовый файл и консоль.
* Streams.Task1
  * Разработать класс, предоставляющий следующие функциональные возможности:
    * функцию побайтового копирования содержимого одного тестового файла в другой с использованием класса FileStream в качестве потока с резервным хранилищем; функция должна возвращать количество записанных байт;
    * функцию побайтового копирования содержимого одного тестового файла в другой с использованием класса MemoryStream в качестве потока с резервным хранилищем; функция должна возвращать количество записанных байт; содержимое потока MemoryStream наполняется массивом байт, полученных на основе текстовой информации из файла-источника с помощью класса StreamReader;
    * функцию копирования содержимого одного тестового файла в другой, используя возможности буферизации класса FileStream, функция должна возвращать количество записанных байт;
    * функцию копирования содержимого одного тестового файла в другой, используя возможности класса-декоратора потоков BufferedStream, функция должна возвращать количество записанных байт;
    * функцию копирования содержимого одного тестового файла в другой с использованием класса MemoryStream в качестве потока с резервным хранилищем; функция должна возвращать количество записанных байт;
    * функцию построчного копирования содержимого одного тестового файла в другой, функция должна возвращать количество записанных строк;
    * функцию сравнения содержимого исходного и полученного файлов.
  * Протестировать работу методов класса для текстового  файла SourceText.txt, информацию о местонахождении файлов получать из конфигурационного json-файла.
  * Полученные результаты проанализировать.
  * Для выполнения задания использовать следующий проект Streams.
* Streams. Task 2
  * Реализовать функциональность, обозначенную в методах класса StreamTask проекта Streams.2.zip.
  * Проверить работу реализованной функциональности для предлагаемых в проекте тестов.
