# Кластеризация пользователей мобильного приложения "Ненужные вещи"

## Задачи
- Загрузить данные и получить первичное представление о структуре и наполнении;
- Исследовать и обработать дубликаты;
- Исследовать и заменить пропущенные значения;
- В тех случаях, где необходимо, привести данные к соответствующим типам;
- Если необходимо, то изменить и привести названия столбцов к нижнему регистру;
- Объединить события show_contacts и contacts_show;
- Объединить события search_1 - search_7;
- Выделить из столбца с датой необходимые временные промежутки;
- Определить, сколько всего пользователей воспользовались приложением;
- Определить, сколько пользователей приносят нам наши источники;
- Построить график распределения событий по дням за исследуемый период;
- Построить график распредления событий по дням с разбивкой по источникам;
- Посчитать конверсию пользователей в целевое событие - просмотр контактов;
- Определить время начала и конца события для каждого пользователя в приложении;
- Сформировать таблицу с признаками, необходимыми для кластеризации;
- Произвести рассчет показателей: продолжительность каждого сеанса пользователя, количество совершения пользователем целевого действия, определить количество просмотров рекомендованных объявлений и добавлений объявления в избранное, посчитать общее время использования приложения для каждого пользователя;
- Построить графики распределения признаков и написать вывод;
- Построить матрицу корреляции признаков и написать вывод;
- На основании получившихся признаков разобить пользователей на группы при помощи ML;
- Построить графики распределения признаков для кластеров и описать получившиеся кластеры;
- Проверить гипотезу: Конверсия в просмотр контактов между пользователями, установившими приложение по ссылке из yandex и пользователями, установившими приложение по ссылке из google, различается;
- Проверить гипотезу: Конверсия в добавление объявления в избранное между пользователями, установшими приложение по ссылке из yandex, отличается от конверсии пользователей, установивших приложение по ссылке из google.
- Написать общий вывод и подготовить рекомендации для маркетологов по увеличению показателя вовлеченности пользователей в приложение;
- Подготовить презентацию с результатами исследования;
- Подготовить дашборд в Tableau.

## Результаты исследования
Необходимо развивать маркетинговые активности не только в Яндекс, но в Google и в других источниках. Нужно усовершенствовать алгоритм подбора рекомендованных объявлений. Для увеличения количества покупок можно ввести систему доставки, чтобы пользователи могли совершать покупки на всей территории страны.

## Использованные библиотеки
- *pandas*
- *datetime*
- *numpy*
- *math*
- *scipy*
- *matplotlib*
- *seaborn*
- *warnings*
- *calendar*
- *sklearn.model_selection*
- *sklearn.linear_model*
- *sklearn.ensemble*
- *sklearn.metrics*
- *sklearn.metrics*
- *sklearn.preprocessing*
- *scipy.cluster.hierarchy*
- *sklearn.cluster*

## Статус проекта
Завершен.
