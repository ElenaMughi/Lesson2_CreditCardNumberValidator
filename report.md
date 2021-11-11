# Отчёт о тестировании Lesson2_CreditCardNumberValidator

## Краткое описание
 
На тестирование затрачено: 9 часов

В результате тестирования выявлены следующие дефекты:
* [Не верифицирует карты из более 16 символов #1](<https://github.com/ElenaMughi/Lesson2_CreditCardNumberValidator/issues/1#issue-1048816542>)
* [Нет верификации карт МИР #2](<https://github.com/ElenaMughi/Lesson2_CreditCardNumberValidator/issues/2#issue-1048914863>)
* [Нет верификации карт China unionPay #3](<https://github.com/ElenaMughi/Lesson2_CreditCardNumberValidator/issues/3#issue-1048919902>)
* [Нет верификации карт с количеством знаков меньше 16-ти #4](<https://github.com/ElenaMughi/Lesson2_CreditCardNumberValidator/issues/4#issue-1048942042>)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [сайт-генератор кредитных карт 1](https://www.freeformatter.com/credit-card-number-generator-validator.html)
* [сайт-генератор кредитных карт 2](https://ccard-generator.com/)

В качестве тестовых данных использовались данные:
* номера кредитных карт VISA, MASTER CARD, American Express по ссылке выше c сайта 1
* номера остальных карт сгенерированы с помощью сайта 2

Тестирование производилось в следующем окружении:
* Windows 10 Home (rus) 64b
* Java Ver 11.02.12+4-b1504.40 amd64
