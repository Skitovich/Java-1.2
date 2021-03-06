# Отчёт о тестировании  Credit Card Number Validator

## Приложение для проверки валидации кредитных карт.

14.08.2020 - 17.08.2020 было проведено функциональное тестирование приложения  Credit Card Number Validator

На тестирование затрачено: 7 часов.

В результате тестирования выявлены следующие дефекты:
* https://github.com/Skitovich/Java-1.2/issues/1
* https://github.com/Skitovich/Java-1.2/issues/2
* https://github.com/Skitovich/Java-1.2/issues/3
* https://github.com/Skitovich/Java-1.2/issues/4

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Тест-план](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/report.md)


В качестве тестовых использовался   [сайт](https://www.freeformatter.com/credit-card-number-generator-validator.html), [сайт](https://wtools.io/ru/credit-card-generator) и [сайт](https://bcoll.ru/19000-lyuboj-nomer-karty/):

Валидные номера:
* 4916585017020145
* 4916098671211439975
* 4024007144777936522
* 4556294458320985981
* 311041184212468043
* 76009244561
* 4222222222222
* 371515887874970
* 349751932759531
* 344237555479701
* 346348544672179
* 30198039417288
* 30179304008598
* 30055056078007



Невалидные номера:
* 4916585017020144
* абвгд
* " "
* 0
* abcde
* ^&@#$!~
* 0000'0000@0000$0000
* 9999999999999999999
* 888888888888888888
* 77777777777777777
* 6666666666666666
* 555555555555555
* 44444444444444
* 3333333333333
* 222222222222
* 11111111111
* 9898989898
* 212112121
* 34343434
* 4545454
* 566565
* 45454
* 8989
* 789
* 89
* 9

Тестирование производилось в следующем окружении:
* Windows 10. 64 - разрядная
* Java 14



