3 варианта расчета:
1.	Ver1.ipynb

1 категориальный признак – Group age

RealEstateLoansOrLines (закодированное кол-во кредитов) - тк показатель количественный, попробуем его перевести в числовой вид 

NumberOfTimes90DaysLate, NumberOfTime60-89DaysPastDueNotWorse –убиваем, тк корреляция большая

2.	Ver2.ipynb

2 категориальных признака – Group age, RealEstateLoansOrLines 

NumberOfTimes90DaysLate, NumberOfTime60-89DaysPastDueNotWorse –убиваем, тк корреляция большая

3.	Ver3.ipynb

Age – убиваем, будем опираться на Group age 

1 категориальный признак – Group age

RealEstateLoansOrLines (закодированное кол-во кредитов) - тк показатель количественный, попробуем его перевести в числовой вид 

NumberOfTimes90DaysLate, NumberOfTime60-89DaysPastDueNotWorse –убиваем, тк корреляция большая



Сравнение показателей разных моделей и разных подходов к обработке признаков.


 	Логистическая регрессия	- Градиентный бустинг	- Категориальные признаки
  
1й вариант

precision	0.7321	- 0.4341	- 0.4371

recall	0.0160	- 0.2725	- 0.2400

auc-roc	0.6623	- 0.8352	- 0.8284

2й вариант

precision	- 0.7169	- 0.4360	- 0.4331

recall	0.0149	- 0.2752	- 0.2466

auc-roc	0.6543	- 0.8344	- 0.8286

3й вариант

precision	0.5957	- 0.4223	- 0.4354

recall	0.0112	- 0.2636	- 0.2419

auc-roc	0.6349	- 0.8336	- 0.8293



