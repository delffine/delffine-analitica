# Учебные проекты по аналитике данных

Здесь размещены мои проекты, выполненые в рамках курса "Аналитик данных" Яндекс.Практикума




| dir    | Наименование проекта                | Описание                                                     | Стек                                                         |
| ---- | ----------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| vypusk   | [Анализ оттока килентов банка](https://github.com/delffine/practicum.yandex/tree/main/vypusk) |  Составил портрет клиентов, которые склонны уходить из банка. Для анализа взяты 8 параметров, которые я разбил на 50+ сегментов. Выделел сегменты с оттоком больше среднего. Провел статистическую проверку превышения оттока в этих сегментах относительно среднего по всей выборке. Определил сочетания сегментов, которые дают наибольший охват отточных клиентов. Предложил мероприятя для возврата клиентов в банк или удержания сомневающихся | python, pandas, numpy, scipy, matplotlib |
| sprint13   | [Аналитический отчёт в Google Таблицах](https://github.com/delffine/practicum.yandex/tree/main/sprint13) | В этом проекте я проводел расчет бизнез-показателей парикмехерской. Расчитал динамику расходов-дохов за полгода, рентабельность промо-акций, а также наибоее какие товары и услуги пользуются наибольшим спросом у клиентов | Excel |
| sprint12   | [Построение дашборда в Tableau ](https://github.com/delffine/practicum.yandex/tree/main/sprint12) | Подготовил интерактивный дашборд на основе данных о конференциях TED. 4 интерактивных слайда, 3 по заданию, послединй самостоятельно - рассмотрел динамику серий/франшиз конференций | Tableau |
| sprint11   | [Исследования рынка общепита в Москве для принятия решения оботкрытии нового заведения](https://github.com/delffine/practicum.yandex/tree/main/sprint11) | Подготовил исследование рынка общественного питания Москвы, визуализировал полученные данные. На основе данных сформировал рекомендации по выбору места для открытия новой кофейни | python, pandas, seaborn, ploty |
| sprint10   | [Анализ пользовательского поведения в мобильном приложении](https://github.com/delffine/practicum.yandex/tree/main/sprint10) | В данном проекте мной были изучены принципы событийной аналитики. Я построил воронку продаж, исследовал путь пользователей до покупки. Проанализировал результаты A/B-теста введения новых шрифтов. Сравнил 2 контрольные группы между собой, убедился в правильном разделении трафика, а затем сравнил с тестовой группой. Определил, что новый шрифт значительно не повлияет на поведение пользователей | python, pandas, seaborn, ploty, <br> проверка стат.гипотезх, продуктовые метрики |
| sprint09   | [Проверка гипотез по увеличению выручки в интернет-магазине —оценить результаты A/B теста](https://github.com/delffine/practicum.yandex/tree/main/sprint09) | В этом исследовании я проведел приоритизацию гипотез по фреймворкам ICE и RICE. Затем провел анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсийи средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности продолжения тестирования | python, pandas, seaborn, ploty, <br> A/B-тест, статистический тест, фреймворк, RICE, ICE |
| sprint08   | [Анализ сервиса вопросов и ответов по программированию](https://github.com/delffine/practicum.yandex/tree/main/sprint08) | В этом спринте я создавал сложные SQL-запросы для подсчёта требуемых значений и метрик | python, pandas, PostgreSQL, SQL |
| sprint07   | [Анализ убытков приложения ProcrastinatePRO+](https://github.com/delffine/practicum.yandex/tree/main/sprint07) | Провел анализ данных приложения ProcrastinatePRO+. Рассчитал различные юнит-метрики когортного анализа: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использовал данные в теоритической части курса функции расчёта метрик. Сделал выводы по полученным данным | python, pandas,  numpy, scipy, matplotlib, статистический тест, LTV, CAC, когортный анализ, юнит-экономик |
| sprint06   | Исследование данных об инвестиции венчурных фондов в компании-стартапы | Этот проект по SQL автоматически проверяется в тренажёре. Работал с базой данных венчурных фондов и инвестициях в компании-стартапы, которая основана на датасете Startup Investments, опубликованном на популярной платформе для соревнований по исследованию данных Kaggle. | PostgreSQL, SQL |
| sprint05   | [Изучение закономерностей, определяющих успешность игр](https://github.com/delffine/practicum.yandex/tree/main/sprint05) | В этом исследовании я выявлял параметры, определяющие успешность игры в разных регионах мира. Составлены портреты пользователей каждого региона. Проверил гипотезы о равенстве средних пользовательских рейтингов различных платформ и жанров. При анализе использовал критерий Стьюдента для независимых выборок. На основании этого подготовил отчет для планирования рекламных кампаний магазина компьютерных игр | python, pandas,  numpy, scipy, matplotlib, histogram, boxplot, статистический тест, критерий Стьюдента |
| sprint04   | [Исследование поведения пользователей сервиса аренды самокатов](https://github.com/delffine/practicum.yandex/tree/main/sprint04) | в этой работе я провел предварительный анализ использования тарифов на выборке клиентов сервиса самокатов. Проанализировал поведение клиентов при использовании услуг. Проверил статистические гипотезы на основе имеющихся данных | python, pandas,  numpy, scipy, matplotlib, histogram, boxplot, статистический тест,критерий Стьюдента|
| sprint03   | [Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости](https://github.com/delffine/practicum.yandex/tree/main/sprint03) | В этом спринте на основе данных сервиса Яндекс.Недвижимость я определил рыночную стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости отудаленности от центра. Провел предобработку данных. Добавил новые данные. Построил гистограммы, боксплоты, диаграммы рассеивания | python, pandas,  numpy, scipy, matplotlib, histogram, boxplot, scattermatrix,категоризация, scatterplot, фрод-мониторинг|
| sprint02   | [Исследование надёжности заёмщиков — анализ банковских данных](https://github.com/delffine/practicum.yandex/tree/main/sprint02) | В это исследовании на основе данных кредитного отдела банка требовалось определить влияние семейного положения иколичества детей на факт погашения кредита в срок. снчала были определены и обработаны пропуски, заменены типы данных на соответствующие хранящимся данным, удалены дубликаты, категоризованы данные. В итоге один датафрейм был декомпозирован на три | python, pandas,  numpy, scipy, matplotlib, обработка данных, дубликаты, пропуски, категоризация, декомпозиция|
| sprint01   | [Исследование данных сервиса “Яндекс.Музыка” — сравнение пользователей двух городов](https://github.com/delffine/practicum.yandex/tree/main/sprint01) | В первом проекте курса я сравнил поведение пользователей сервиса Яндекс.Музыки из Москвы и С-Петербурга | python, pandas,  numpy, scipy, matplotlib, обработка данных, дубликаты, пропуски, логическая индексация, группировка, сортировка |

Все работы делались за 2-3-4 дня, вместо отведенных 7.
Работы сдавались со второй проверки, кроме спринта , который приняли с первого раза.
Выпускной проект сделал за 2 дня, сдал с 3 итерации.


