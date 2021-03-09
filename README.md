# **Отчёт о тестировании приложения Money Transfer**

## **Краткое описание**
09 марта 2021 было проведено функциональное тестирование приложения Money Transfer при помощи положительного метода на основе [Задачи 1] (https://github.com/netology-code/javaqa-homeworks/tree/master/programming#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-1---money-transfer) из Домашнего задания к занятию "1.2. Программирование на Java: переменные, операторы, работа с отладчиком".

## **На тестирование затрачено**: 15 минут

## **В результате тестирования выявлены следующие дефекты**:

* [При зачислении 500_000_000 на депозит с суммой 2_000_000_000 в приложении Money Transfer баланс счёта клиента становится отрицательным.](https://github.com/maxim-valov/MoneyTransfer/issues/11)


## **Описание процесса тестирования**

**В процессе тестирования использовались следующие артефакты**:

Тестированииe проводилось на осове требований к [Задаче 1](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-1---money-transfer) из Домашнего задания к занатию «1.2. Программирование на Java: переменные, операторы, работа с отладчиком»


**В качестве тестовых данных использовались данные**:

* [JAVA Код для Money Transfer](https://github.com/maxim-valov/MoneyTransfer/blob/master/codeMoneyTransfer.md)  c ожидаемым результатом: При зачислении на депозит с суммой 2_000_000_000 дополнительных 500_000_000 баланс счёта становится равен 2_500_000_000.


**Тестирование производилось в следующем окружении**:

* Windows 10x
* OpenJDK 11.0.10+9
* IntelliJ IDEA