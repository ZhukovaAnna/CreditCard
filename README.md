# Отчёт о тестировании Credit Card Number Validator. #
## Краткое описание ##
Дата начала - Дата окончания.
23.03.2020 - 23.03.2020

Было проведено дымовое тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования дефекты не выявлены. 

## Описание процесса тестирования ##

В процессе тестирования использовались следующие артефакты:

[Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

В качестве тестовых данных использовались данные [Get Credit Card Numbers](https://www.getcreditcardnumbers.com/):

 Валидные данные.
 
 Visa

4929332824231887 OK

4916285307004657 OK

4024007124090811 OK

Невалидные данные.

American Express

043833594523680 FAIL

004116196082541 FAIL

000140251831072 FAIL


Тестирование производилось в следующем окружении:

Майкрософт Windows 10 Pro x64.

Java SE 11.

Intellij IDEA Community 2019.3.4
