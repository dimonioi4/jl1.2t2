# Отчёт о тестировании приложения "Precision"
## Краткое описание

22.01.2021 - 22.01.2021 было проведено функциональное тестирование, тестирование граничных типов приложения Money Transfer.

[Код программы Precision](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-2---precision)

На тестирование затрачено: 1 час.

## Описание тестов

Проводился позитивный тест функциональности приложения Precision


Результаты

     0% успешных/100% неуспешных тестов
    
[Баг 1 Неточность выведения результата итогового бонуса](https://github.com/dimonioi4/jl1.2t2/issues/1#issue-791855155) 

# Общие рекомендации

В работе с примитивными переменными типа double необходимо помнить, что в десятичной системе нельзя точно представить результат деления 1/3, так и в двоичной системе невозможно точно представить 1/10. Если вам нужно исключить ошибки округления, следует использовать класс BigDecimal.  
