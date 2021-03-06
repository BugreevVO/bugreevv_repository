# Сеть фитнес-центров

### [Проект с полноценной визуализацией и навигацией](https://nbviewer.org/github/BugreevVO/bugreevv_repository/blob/main/09_Анализ_и_план_действий_по_удержанию_клиентов_фитнес-центра/bugreev_analysis_and_action_plan_for_customer_retention_of_the_fitness_center.ipynb)

## Данные

Сеть фитнес-центров разрабатывает стратегию взаимодействия с клиентами на основе аналитических данных.

Распространённая проблема фитнес-клубов и других сервисов — отток клиентов.

Чтобы бороться с оттоком, отдел по работе с клиентами фитнес-центра перевёл в электронный вид множество клиентских анкет. 

План исследования:
1. Загрузим данные;
2. Проведем исследовательский анализ данных (EDA);
3. Построим модель прогнозирования оттока клиентов;
4. Сделаем кластеризацию клиентов;
5. Сформулируем выводы и сделаем базовые рекомендации по работе с клиентами.

Сеть фитнес-клубов предоставила сведения в csv-файлах. Заказчик подготовил данные, которые содержат данные на месяц до оттока и факт оттока на определённый месяц.

## Задача

Провести анализ и подготовить план действий по удержанию клиентов. А именно:
- научиться прогнозировать вероятность оттока (на уровне следующего месяца) для каждого клиента;
- сформировать типичные портреты клиентов: выделить несколько наиболее ярких групп и охарактеризовать их основные свойства;
- проанализировать основные признаки, наиболее сильно влияющие на отток;
- сформулировать основные выводы и разработать рекомендации по повышению качества работы с клиентами:
 - 1) выделить целевые группы клиентов;
 - 2) предложить меры по снижению оттока;
 - 3) определить другие особенности взаимодействия с клиентами.
 
## Используемые библиотеки

- *pandas*
- *seaborn*
- *pyplot*
- *warnings*
- *sklearn*
- *scipy*