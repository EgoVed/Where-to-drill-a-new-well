# Where-to-drill-a-new-well
Где бурить новую скважину?

http://mopo.lukoil.ru/i/upload_img/media/8/3/15383-image_url-cfcaf6fcd2f62cd05566a33f9615e9de.JPG

### Описание проекта

Допустим, мы работаете в добывающей компании. Нужно решить, где бурить новую скважину.
Предоставлены пробы нефти в трёх регионах: в каждом — 100 000 месторождений, где измерили качество нефти и объём её 
запасов. Надо построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализировать возможную прибыль и риски техникой Bootstrap.

### Шаги для выбора локации:

В избранном регионе ищут месторождения, для каждого определяют значения признаков;
Строят модель и оценивают объём запасов;
Выбирают месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
Прибыль равна суммарной прибыли отобранных месторождений.

### Условия задачи:
Для обучения модели подходит только линейная регрессия.
При разведке региона проводится исследование 500 точек.
Бюджет на разработку месторождений — 10 млрд рублей, стоимость бурения одной скважины — 50 млн рублей.
Один баррель сырья приносит 4500 рублей прибыли.
Не рассматривать регионы, в которых риск убытков выше 2.5%. Из оставшихся выбирается регион с наибольшей средней прибылью.

