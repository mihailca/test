# Одновременное подключение к нескольким устройствам

Когда нужно опросить много устройств, выполнение подключений поочередно будет достаточно долгим.
Конечно, это будет быстрее, чем подключение вручную, но хотелось бы получать отклик как можно быстрее.

> Все эти "долго" и "быстрее" относительные понятия, но в этом разделе мы научимся и конкретно измерять, сколько отрабатывал скрипт, чтобы сравнить, насколько быстрее будет выполняться подключение.

Для параллельного подключения к устройствам в этом разделе используется модуль concurrent.futures.


Также в разделе [Дополнительная информация](../25_additional_info/threading_multiprocessing/README.md) рассматриваются основы работы с модулями:

* threading
* multiprocessing
