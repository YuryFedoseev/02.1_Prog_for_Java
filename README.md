# 2.1_Prog_for_Java

# Отчёт о тестировании Money Transfer- Пополнение счета

## Проверка корректности пополнения счета клиентов с крупными суммами

<16.06.2021> - <16.06.2021> было проведено исследовательское тестирование приложения Money Transfer.

### На тестирование затрачено: <0,2 часа>

В результате тестирования выявлены следующие дефекты:
[Дефект типа данных](https://github.com/YuryFedoseev/02.1_Prog_for_Java/issues/1)

Описание процесса тестирования:

В процессе тестирования использовались следующие артефакты*:
1. [Чек лист](https://github.com/YuryFedoseev/02.1_Prog_for_Java/blob/master/Чек%20лист.txt)



В качестве тестовых данных использовались данные :

1. Из ошибки с продуктива  - -  int balanse= 2_000_000_000;int perevod= 500_000_000;
1. Переменные, сумма которых попадает под значение int  - - int balanse= 200_000_000;int perevod= 500_000_000;
1. Измененные типы переменных с int на long - -         long balanse= 2_000_000_000; long perevod= 500_000_000;

Тестирование производилось в следующем окружении:

1. <windows 10> - 64x
2. 11.01.10 - версия Java
3. код с типами переменных, см репозиторий
