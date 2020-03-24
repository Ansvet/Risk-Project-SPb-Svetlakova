# Risk-Project-SPb-Svetlakova

## (Marat) 24/03/2020 (репозиторий по состоянию на 23/03/2020)

### СAP-(ROC-) curves

Вычислительно тут все ОК.


Текущая оценка: 1 балл.

### PDs

Вычислительно все ОК. Все понятно. 

Текущая оценка: 2 балла

### Quality tests

1. Плз, укажите, каким методом вы пользуетесь для оценки CI для PDs.

2. Неправильно применен LR тест для спецификаций моделей PD. Во-первых, обратите внимание, что в формулу статистики вы подставляете log-likelihood, что противоречит используемой формуле. Во-вторых, число степеней свободы для критических значений должно быть другим. Плз, исправьте.

3. Плз, опишите тест (H0, статистику и его распределение), которым Вы пользуетесь для статистического сравнения оценок PD по разным методам в одной категории. Кстати, такого задания не было, поэтому его можно не проводить.)))

4. Не проведен proportion test для проверки гипотезы об одиноковых вероятностях дефолтов в разных категориях. Строится по исходным данным о дефолтах в разных рейтинговых категориях. Например, I2 и I3. 

Текущая оценка: 1 балл. Для получения максимально балла плз, учтите замечания.

---------------------------------

Текущий общий балл за проект: 4 балла (потенциально 6).