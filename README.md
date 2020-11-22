# Отчёт о тестировании приложения "Precision"
## Краткое описание
После тестирования Precision, обнаружилось что приложение неправильно считает сумму вещественных чисел. 

## Описание тестов
Проводилось функциональное тестирование, а именно операция сложения значения regularBonus и значения specialBonus

## Результаты
Проведен 1 тест;

Успешных тестов - 0%;

Неуспешных тестов - 100%;

[#1 Баг-репорт "Неправильное значения при сложении вещественных чисел в приложении Precision"](https://github.com/evgen-911/Precision/issues/1#issue-748236489)

## Общие рекомендации

ошибка связана с тем, как числа представлены в двоичном виде в памяти компьютера
