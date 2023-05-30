3 варианта расчета:
1.	CS_ver_of_MY_new.ipynb
1 категориальный признак – Group age
RealEstateLoansOrLines (закодированное кол-во кредитов) - тк показатель количественный, попробуем его перевести в числовой вид 
NumberOfTimes90DaysLate, NumberOfTime60-89DaysPastDueNotWorse –убиваем, тк корреляция большая
2.	CS_ver_of_MY_new2.ipynb
2 категориальных признака – Group age, RealEstateLoansOrLines 
NumberOfTimes90DaysLate, NumberOfTime60-89DaysPastDueNotWorse –убиваем, тк корреляция большая
3.	CS_ver_of_MY_new3.ipynb
Age – убиваем, будем опираться на Group age 
1 категориальный признак – Group age
RealEstateLoansOrLines (закодированное кол-во кредитов) - тк показатель количественный, попробуем его перевести в числовой вид 
NumberOfTimes90DaysLate, NumberOfTime60-89DaysPastDueNotWorse –убиваем, тк корреляция большая

 	Логистическая регрессия	Градиентный бустинг	Категориальные признаки
1й вариант
precision	0.732142857	0.434103685	0.437142857
recall	0.016078431	0.27254902	0.24
auc-roc	0.662305154	0.835204034	0.828452948
2й вариант
precision	0.716981132	0.434079602	0.433195592
recall	0.014901961	0.27372549	0.246666667
auc-roc	0.654377151	0.834285709	0.828618163
3й вариант
precision	0.5	0.402285027	0.417525773
recall	0.008016032	0.268136273	0.259719439
auc-roc	0.683277965	0.837627471	0.832946037

