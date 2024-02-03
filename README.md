# Анализ продаж чая и кофе в США
В рамках данного проекта проводится анализ продаж чая и кофе в различных магазинах США за период с 2010 по 2011 год. Целью исследования является выявление ключевых трендов и факторов, влияющих на маржинальность продажи кофе и чая. Также учитываются сезонные колебания стоимости закупок и региональные особенности потребления данных товаров.
## Описание используемого датасета
Данный датасет содержит информацию о стоимости продаж в долларах США в американских магазинах между 2010 и 2011 годами. В частности, набор данных включает:
- Площадь магазинов, штат, регион и размер;
- ID продуктов, описание, тип, категория и дата продажи;
- Бухгалтерская информация, такая как бюджетная маржа, прибыль и общие расходы.

## Гипотезы, проверяемые в ходе исследования
1. Летом возрастает стоимость крупных закупок.
2. Штат влияет на продажи, в т.ч. на дифференциацию аннуальных продаж

## Выводы:
1. Сезонность продаж:
Анализ данных показывает, что продажи кофе и чая имеют сезонную зависимость. С наступлением более холодных времен года наблюдается увеличение продаж в "холодных" штатах, в "жарких штатах" наблюдаются сезонные колебания - в основном, увеличение продаж происходит в летнее время. Данный вывод подкреплен результатами MI-анализа и построенной моделью.
2. Влияющие факторы:
Факторами, оказывающими положительное влияние на продажи, являются:
- численность населения в регионе
-  инвентарная стоимость товара
-  географическое расположение магазина (штат)
3. Взаимосвязь расходов и маркетинга:
Обнаружена сильная положительная корреляция между общими расходами на выпуск товара на рынок и размером маркетинговых затрат на продвижение чая и кофе. Это подчеркивает важность инвестиций в маркетинговые и рекламные кампании для стимулирования продаж для данного типа товара.
4. Модель прогнозирования:
Разработанная модель обладает высокой предсказательной способностью и может быть использована для оценки будущих продаж на основе текущих тенденций и идентифицированных влияющих факторов. 

