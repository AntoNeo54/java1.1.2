# Отчёт о тестировании установки IntelliJ IDEA и работы приложения Credit Card Number Validator

## Краткое описание

31/10/2020 - 31/10/2020 было проведено тестирование установки IntelliJ IDEA и функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* Валидация банковских карт не проходит при количестве символов в номере не равным 16 [1#issue-733760229](https://github.com/AntoNeo54/java1.1.2/issues/1#issue-733760229)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Руководство по установке IntelliJ IDEA [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* Функциональность валидации номера банковской карты [Программный код](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/README.md#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0-1)

В качестве тестовых данных использовались данные сгенерированные [Credit Card Generator](https://cardgenerator.io):

Номера кредитных карт разных платёжных систем:

* 4769008194770232 - VISA
* 5298472761011247 - MasterCard
* 6011634767694409 - Discover Card
* 3559986248531930 - JCB Card
* 379440031696348 - American Express Card
* 38612028205746 - Diners Club Credit Card

ожидаемый результат Result is OK


Тестирование производилось в следующем окружении:
* Операционная система Windows 10 Pro версия 1909 x64
* Java
openjdk version "11.0.7" 2020-04-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.7+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.7+10, mixed mode)
* IntelliJ IDEA 2020.2 (Community Edition)
Runtime version: 11.0.7+10-b944.20 amd64
