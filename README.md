# Общая информация

Файлы по каждой из задач лежат в отдельных папках с
названиями, соответствующими названиям задач. 

Репозиторий имеет один файл readme, содержащий все 
рекомендации по использованию.

## issue-01

Для запуска можно либо запустить файл morse.py. 
В этом случае один из тестов выдаст ошибку, 
поскольку для него не проставлен флаг 
"NORMALIZE_WHITESPACE".

Альтернативный способ запуска - через командную строку.
Для этого достаточно написать 
`python -m doctest -o NORMALIZE_WHITESPACE morse.py`. 
В этом случае все тесты пройдут.

Результаты запуска тестов для этого упражнения 
представлены в файле `issue01.txt` 

## issue-02

Это задание требует установленного pytest. Чтобы 
установить pytest, достаточно в командной строке 
написать `pip install pytest`.

Код с тестами находится в файле `test_issue02.py`. Для 
запуска достаточно просто запустить 
`pytest test_issue02.py` в терминале.

Значения и результаты тестов представлены в файле 
`issue02_results.txt`

## issue-03

Код с тестами находится в файле `issue03.py`. Для 
запуска тестов достаточно запустить эту программу.

Значения и результаты тестов представлены в файле 
`issue03_results.txt`

## issue-04

Это задание требует установленного pytest. Чтобы 
установить pytest, достаточно в командной строке 
написать `pip install pytest`.

Чтобы запустить тест, достаточно в командной строке
написать `pytest -v  issue04.py`. 

Результаты тестов доступны в файле `issue03_results.txt`
.

## issue_05

Код с тестами находится в файле `issue05.py`. Для 
запуска тестов достаточно запустить эту программу.

Значения и результаты тестов представлены в файле 
`issue05_results.txt`
 