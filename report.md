# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

25.12.2020 - 25.12.2020 было проведено Функциональное тестирование (functional testing) приложения Credit Card Number Validator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* [Bug Report](https://github.com/NetologyQA12/CreditCardNumberValidator/issues/1)


## Описание процесса тестирования



В качестве тестовых данных использовались данные <https://www.freeformatter.com/credit-card-number-generator-validator.html>:

В строку "String number" ввожу номера карт:
* String number = "4532226695932400" Result is OK
* String number = "6763596527281639" Result is OK
* String number = "4024007133855557979" Result is FAIL
* String number = "2221000346800294" Result is OK

Тестирование производилось в следующем окружении:
* ОС Windows 10 x64
* Java Version 11.0.8
* ПО IntelliJ IDEA Community Edition 2020.2.3 x64
