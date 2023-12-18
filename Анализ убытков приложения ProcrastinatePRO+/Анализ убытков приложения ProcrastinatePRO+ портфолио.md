<h1>Оглавление<span class="tocSkip"></span></h1>
<div class="toc"><ul class="toc-item"><li><span><a href="#Введение" data-toc-modified-id="Введение-1"><span class="toc-item-num">1&nbsp;&nbsp;</span>Введение</a></span></li><li><span><a href="#Загрузка-и-первичный-анализ-данных" data-toc-modified-id="Загрузка-и-первичный-анализ-данных-2"><span class="toc-item-num">2&nbsp;&nbsp;</span>Загрузка и первичный анализ данных</a></span><ul class="toc-item"><li><span><a href="#Открытие-данных-и-импорт-библиотек" data-toc-modified-id="Открытие-данных-и-импорт-библиотек-2.1"><span class="toc-item-num">2.1&nbsp;&nbsp;</span>Открытие данных и импорт библиотек</a></span></li><li><span><a href="#Предобработка-данных" data-toc-modified-id="Предобработка-данных-2.2"><span class="toc-item-num">2.2&nbsp;&nbsp;</span>Предобработка данных</a></span><ul class="toc-item"><li><span><a href="#Таблица-Visits" data-toc-modified-id="Таблица-Visits-2.2.1"><span class="toc-item-num">2.2.1&nbsp;&nbsp;</span>Таблица Visits</a></span></li><li><span><a href="#Таблица-Orders" data-toc-modified-id="Таблица-Orders-2.2.2"><span class="toc-item-num">2.2.2&nbsp;&nbsp;</span>Таблица Orders</a></span></li><li><span><a href="#Таблица-Costs" data-toc-modified-id="Таблица-Costs-2.2.3"><span class="toc-item-num">2.2.3&nbsp;&nbsp;</span>Таблица Costs</a></span></li></ul></li><li><span><a href="#Промежуточный-вывод" data-toc-modified-id="Промежуточный-вывод-2.3"><span class="toc-item-num">2.3&nbsp;&nbsp;</span>Промежуточный вывод</a></span></li></ul></li><li><span><a href="#Функции-для-расчёта-и-анализа-LTV,-ROI,-удержания-и-конверсии." data-toc-modified-id="Функции-для-расчёта-и-анализа-LTV,-ROI,-удержания-и-конверсии.-3"><span class="toc-item-num">3&nbsp;&nbsp;</span>Функции для расчёта и анализа LTV, ROI, удержания и конверсии.</a></span><ul class="toc-item"><li><span><a href="#Фунция-get_profiles" data-toc-modified-id="Фунция-get_profiles-3.1"><span class="toc-item-num">3.1&nbsp;&nbsp;</span>Фунция get_profiles</a></span></li><li><span><a href="#Фунция-get_retention" data-toc-modified-id="Фунция-get_retention-3.2"><span class="toc-item-num">3.2&nbsp;&nbsp;</span>Фунция get_retention</a></span></li><li><span><a href="#Фунция-get_conversion" data-toc-modified-id="Фунция-get_conversion-3.3"><span class="toc-item-num">3.3&nbsp;&nbsp;</span>Фунция get_conversion</a></span></li><li><span><a href="#Фунция-get_ltv" data-toc-modified-id="Фунция-get_ltv-3.4"><span class="toc-item-num">3.4&nbsp;&nbsp;</span>Фунция get_ltv</a></span></li><li><span><a href="#Фунция-filter_data" data-toc-modified-id="Фунция-filter_data-3.5"><span class="toc-item-num">3.5&nbsp;&nbsp;</span>Фунция filter_data</a></span></li><li><span><a href="#Фунция-plot_retention" data-toc-modified-id="Фунция-plot_retention-3.6"><span class="toc-item-num">3.6&nbsp;&nbsp;</span>Фунция plot_retention</a></span></li><li><span><a href="#Фунция-plot_conversion" data-toc-modified-id="Фунция-plot_conversion-3.7"><span class="toc-item-num">3.7&nbsp;&nbsp;</span>Фунция plot_conversion</a></span></li><li><span><a href="#Фунция-plot_ltv_roi" data-toc-modified-id="Фунция-plot_ltv_roi-3.8"><span class="toc-item-num">3.8&nbsp;&nbsp;</span>Фунция plot_ltv_roi</a></span></li></ul></li><li><span><a href="#Исследовательский-анализ-данных" data-toc-modified-id="Исследовательский-анализ-данных-4"><span class="toc-item-num">4&nbsp;&nbsp;</span>Исследовательский анализ данных</a></span><ul class="toc-item"><li><span><a href="#Профили-пользователй-и-минимальная/максимальная-дата-привлечения" data-toc-modified-id="Профили-пользователй-и-минимальная/максимальная-дата-привлечения-4.1"><span class="toc-item-num">4.1&nbsp;&nbsp;</span>Профили пользователй и минимальная/максимальная дата привлечения</a></span></li><li><span><a href="#Количество-и-доля-пользователей-с-каждой-страны" data-toc-modified-id="Количество-и-доля-пользователей-с-каждой-страны-4.2"><span class="toc-item-num">4.2&nbsp;&nbsp;</span>Количество и доля пользователей с каждой страны</a></span></li><li><span><a href="#Количество-и-доля-пользователей-с-каждого-устройства" data-toc-modified-id="Количество-и-доля-пользователей-с-каждого-устройства-4.3"><span class="toc-item-num">4.3&nbsp;&nbsp;</span>Количество и доля пользователей с каждого устройства</a></span></li><li><span><a href="#Количество-и-доля-пользователей-с-каждого-канала" data-toc-modified-id="Количество-и-доля-пользователей-с-каждого-канала-4.4"><span class="toc-item-num">4.4&nbsp;&nbsp;</span>Количество и доля пользователей с каждого канала</a></span></li></ul></li><li><span><a href="#Маркетинг" data-toc-modified-id="Маркетинг-5"><span class="toc-item-num">5&nbsp;&nbsp;</span>Маркетинг</a></span></li><li><span><a href="#Оценить-окупаемость-рекламы" data-toc-modified-id="Оценить-окупаемость-рекламы-6"><span class="toc-item-num">6&nbsp;&nbsp;</span>Оценить окупаемость рекламы</a></span><ul class="toc-item"><li><span><a href="#Графики-LTV,-ROI-и-графики-динамики-LTV,-CAC,-ROI" data-toc-modified-id="Графики-LTV,-ROI-и-графики-динамики-LTV,-CAC,-ROI-6.1"><span class="toc-item-num">6.1&nbsp;&nbsp;</span>Графики LTV, ROI и графики динамики LTV, CAC, ROI</a></span><ul class="toc-item"><li><span><a href="#Проверка-CAC" data-toc-modified-id="Проверка-CAC-6.1.1"><span class="toc-item-num">6.1.1&nbsp;&nbsp;</span>Проверка CAC</a></span></li></ul></li><li><span><a href="#Графики-Retention-и-Conversion" data-toc-modified-id="Графики-Retention-и-Conversion-6.2"><span class="toc-item-num">6.2&nbsp;&nbsp;</span>Графики Retention и Conversion</a></span></li><li><span><a href="#Графики-LTV,-ROI-и-графики-динамики-LTV,-CAC,-ROI-с-разбивкой-по-устройствам" data-toc-modified-id="Графики-LTV,-ROI-и-графики-динамики-LTV,-CAC,-ROI-с-разбивкой-по-устройствам-6.3"><span class="toc-item-num">6.3&nbsp;&nbsp;</span>Графики LTV, ROI и графики динамики LTV, CAC, ROI с разбивкой по устройствам</a></span></li><li><span><a href="#Графики-LTV,-ROI-и-графики-динамики-LTV,-CAC,-ROI-с-разбивкой-по-странам" data-toc-modified-id="Графики-LTV,-ROI-и-графики-динамики-LTV,-CAC,-ROI-с-разбивкой-по-странам-6.4"><span class="toc-item-num">6.4&nbsp;&nbsp;</span>Графики LTV, ROI и графики динамики LTV, CAC, ROI с разбивкой по странам</a></span></li><li><span><a href="#Графики-LTV,-ROI-и-графики-динамики-LTV,-CAC,-ROI-с-разбивкой-по-каналам" data-toc-modified-id="Графики-LTV,-ROI-и-графики-динамики-LTV,-CAC,-ROI-с-разбивкой-по-каналам-6.5"><span class="toc-item-num">6.5&nbsp;&nbsp;</span>Графики LTV, ROI и графики динамики LTV, CAC, ROI с разбивкой по каналам</a></span></li><li><span><a href="#Исследование-отдельно-взятого-региона" data-toc-modified-id="Исследование-отдельно-взятого-региона-6.6"><span class="toc-item-num">6.6&nbsp;&nbsp;</span>Исследование отдельно взятого региона</a></span></li><li><span><a href="#Исследование-отдельно-взятых-девайсов" data-toc-modified-id="Исследование-отдельно-взятых-девайсов-6.7"><span class="toc-item-num">6.7&nbsp;&nbsp;</span>Исследование отдельно взятых девайсов</a></span><ul class="toc-item"><li><span><a href="#Исследования-девайсов-в-Америке" data-toc-modified-id="Исследования-девайсов-в-Америке-6.7.1"><span class="toc-item-num">6.7.1&nbsp;&nbsp;</span>Исследования девайсов в Америке</a></span></li><li><span><a href="#Исследования-девайсов-в-Европе" data-toc-modified-id="Исследования-девайсов-в-Европе-6.7.2"><span class="toc-item-num">6.7.2&nbsp;&nbsp;</span>Исследования девайсов в Европе</a></span></li></ul></li><li><span><a href="#Исследование-каналов" data-toc-modified-id="Исследование-каналов-6.8"><span class="toc-item-num">6.8&nbsp;&nbsp;</span>Исследование каналов</a></span><ul class="toc-item"><li><span><a href="#Исследования-каналов-в-Америке" data-toc-modified-id="Исследования-каналов-в-Америке-6.8.1"><span class="toc-item-num">6.8.1&nbsp;&nbsp;</span>Исследования каналов в Америке</a></span></li><li><span><a href="#Исследования-каналов-в-Европе" data-toc-modified-id="Исследования-каналов-в-Европе-6.8.2"><span class="toc-item-num">6.8.2&nbsp;&nbsp;</span>Исследования каналов в Европе</a></span></li></ul></li><li><span><a href="#Графики-LTV,-ROI-и-графики-динамики-LTV,-CAC,-ROI-американских-пользователей-с-разбивкой-по-каналам-и-по-девайсам" data-toc-modified-id="Графики-LTV,-ROI-и-графики-динамики-LTV,-CAC,-ROI-американских-пользователей-с-разбивкой-по-каналам-и-по-девайсам-6.9"><span class="toc-item-num">6.9&nbsp;&nbsp;</span>Графики LTV, ROI и графики динамики LTV, CAC, ROI американских пользователей с разбивкой по каналам и по девайсам</a></span></li><li><span><a href="#Графики-LTV,-ROI-и-графики-динамики-LTV,-CAC,-ROI-европейских-пользователей-с-разбивкой-по-каналам-и-по-девайсам" data-toc-modified-id="Графики-LTV,-ROI-и-графики-динамики-LTV,-CAC,-ROI-европейских-пользователей-с-разбивкой-по-каналам-и-по-девайсам-6.10"><span class="toc-item-num">6.10&nbsp;&nbsp;</span>Графики LTV, ROI и графики динамики LTV, CAC, ROI европейских пользователей с разбивкой по каналам и по девайсам</a></span></li><li><span><a href="#Промежуточные-выводы" data-toc-modified-id="Промежуточные-выводы-6.11"><span class="toc-item-num">6.11&nbsp;&nbsp;</span>Промежуточные выводы</a></span></li></ul></li><li><span><a href="#Выводы" data-toc-modified-id="Выводы-7"><span class="toc-item-num">7&nbsp;&nbsp;</span>Выводы</a></span></li></ul></div>

# Декомпозиция

- **Введение**
- **Шаг 1. Загрузка и первичный анализ данных**
    - Загрузка необходимых библиотек
    - Загрузка датасетов о визитах, заказах и рекламных расходов
    - Первичное изучение данных
    - Промежуточный вывод
    - Выполнить предобработку 
- **Шаг 2. Задать функции для расчёта и анализа LTV, ROI, удержания и конверсии**
    - Это функции для вычисления значений метрик:
        - get_profiles() — для создания профилей пользователей,
        - get_retention() — для подсчёта Retention Rate,
        - get_conversion() — для подсчёта конверсии,
        - get_ltv() — для подсчёта LTV.
    - А также функции для построения графиков:
        - filter_data() — для сглаживания данных,
        - plot_retention() — для построения графика Retention Rate,
        - plot_conversion() — для построения графика конверсии,
        - plot_ltv_roi — для визуализации LTV и ROI.
- **Шаг 3. Исследовательский анализ данных**
    - Составить профили пользователей. Определите минимальную и максимальную даты привлечения пользователей.
    - Выяснить, из каких стран пользователи приходят в приложение и на какую страну приходится больше всего платящих пользователей. Построить таблицу, отражающую количество пользователей и долю платящих из каждой страны.
    - Узнайть, какими устройствами пользуются клиенты и какие устройства предпочитают платящие пользователи. Построить таблицу, отражающую количество пользователей и долю платящих для каждого устройства.
    - Изучить рекламные источники привлечения и определите каналы, из которых пришло больше всего платящих пользователей. Построить таблицу, отражающую количество пользователей и долю платящих для каждого канала привлечения.
    - Промежуточные выводы.
- **Шаг 4. Маркетинг**
    - Посчитать общую сумму расходов на маркетинг.
    - Выяснить, как траты распределены по рекламным источникам, то есть сколько денег потратили на каждый источник.
    - Построить график с визуализацией динамики изменения расходов во времени по неделям по каждому источнику. Затем на другом графике визуализируйте динамику изменения расходов во времени по месяцам по каждому источнику.
    - Узнать, сколько в среднем стоило привлечение одного пользователя (CAC) из каждого источника.
    - Промежуточные выводы.
- **Шаг 5. Оценить окупаемость рекламы**
    - Используя графики LTV, ROI и CAC, проанализировать окупаемость рекламы. Считать, что на календаре 1 ноября 2019 года, а в бизнес-плане заложено, что пользователи должны окупаться не позднее чем через две недели после привлечения. Определеить необходимость включения в анализ органических пользователей.
    - Проанализировать окупаемость рекламы c помощью графиков LTV и ROI, а также графики динамики LTV, CAC и ROI.
    - Проверить конверсию пользователей и динамику её изменения. То же самое сделать с удержанием пользователей. Построить и изучите графики конверсии и удержания.
    - Проанализировать окупаемость рекламы с разбивкой по устройствам. Построить графики LTV и ROI, а также графики динамики LTV, CAC и ROI.
    - Проанализировать окупаемость рекламы с разбивкой по странам. Построить графики LTV и ROI, а также графики динамики LTV, CAC и ROI.
    - Проанализировать окупаемость рекламы с разбивкой по рекламным каналам. Построить графики LTV и ROI, а также графики динамики LTV, CAC и ROI.
    - Ответить на такие вопросы:
        - Окупается ли реклама, направленная на привлечение пользователей в целом?
        - Какие устройства, страны и рекламные каналы могут оказывать негативное влияние на окупаемость рекламы?
        - Чем могут быть вызваны проблемы окупаемости?
    - Промежуточный вывод (опичать возможные причины обнаруженных проблем и промежуточные рекомендации для рекламного отдела).
- **Шаг 6. Выводы**
    - Выделить причины неэффективности привлечения пользователей.
    - Рекомендации для отдела маркетинга.

# Анализ убытков приложения ProcrastinatePRO+

### Введение

У меня в распоряжении есть лог сервера с данными о посещениях приложения Procrastinate Pro+ новыми пользователями, зарегистрировавшимися в период с 2019-05-01 по 2019-10-27, выгрузка их покупок за этот период, а также статистика рекламных расходов. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Моя задача — разобраться в причинах и помочь компании выйти в плюс.Нам предстоит изучить, как люди пользуются продуктом, когда они начинают покупать, сколько денег приносит каждый клиент, когда он окупается и какие факторы отричательно влияют на привлечение пользователей.

### Загрузка и первичный анализ данных

#### Открытие данных и импорт библиотек


```python
import pandas as pd
import numpy as np
from matplotlib import pyplot as plt
from datetime import datetime, timedelta
```


```python
visits = pd.read_csv(r'C:\Users\egor1\OneDrive\Рабочий стол\All\ПРАКТИКУМ\Проекты Практикум\БАЗЫ ДАННЫХ\procrastinatiomPro+/visits_info_short.csv')
orders = pd.read_csv(r'C:\Users\egor1\OneDrive\Рабочий стол\All\ПРАКТИКУМ\Проекты Практикум\БАЗЫ ДАННЫХ\procrastinatiomPro+/orders_info_short.csv')
costs = pd.read_csv(r'C:\Users\egor1\OneDrive\Рабочий стол\All\ПРАКТИКУМ\Проекты Практикум\БАЗЫ ДАННЫХ\procrastinatiomPro+/costs_info_short.csv')
```

#### Предобработка данных

##### Таблица Visits

Проверяю на дубликаты и пропуски в таблице "visits", узнаю общую информацию о таблице (название столбцов, типы данных)


```python
print(visits.duplicated().sum())
print(visits.isna().sum())
```

    0
    User Id          0
    Region           0
    Device           0
    Channel          0
    Session Start    0
    Session End      0
    dtype: int64
    


```python
visits.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 309901 entries, 0 to 309900
    Data columns (total 6 columns):
     #   Column         Non-Null Count   Dtype 
    ---  ------         --------------   ----- 
     0   User Id        309901 non-null  int64 
     1   Region         309901 non-null  object
     2   Device         309901 non-null  object
     3   Channel        309901 non-null  object
     4   Session Start  309901 non-null  object
     5   Session End    309901 non-null  object
    dtypes: int64(1), object(5)
    memory usage: 14.2+ MB
    

Привожу названия столбцов к единому регстру и перевожу столбцы "session_start" и "session_end" к типу datatime


```python
visits = visits.rename(columns={'User Id':'user_id', 'Region':'region', 'Device':'device', 'Channel':'channel', 'Session Start':'session_start', 'Session End':'session_end'})
```


```python
visits['session_start'] = pd.to_datetime(visits['session_start'])
visits['session_end'] = pd.to_datetime(visits['session_end'])
```

##### Таблица Orders

Проверяю на дубликаты и пропуски в таблице "orders", узнаю общую информацию о таблице (название столбцов, типы данных)


```python
print(orders.duplicated().sum())
print(orders.isna().sum())
```

    0
    User Id     0
    Event Dt    0
    Revenue     0
    dtype: int64
    


```python
orders.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 40212 entries, 0 to 40211
    Data columns (total 3 columns):
     #   Column    Non-Null Count  Dtype  
    ---  ------    --------------  -----  
     0   User Id   40212 non-null  int64  
     1   Event Dt  40212 non-null  object 
     2   Revenue   40212 non-null  float64
    dtypes: float64(1), int64(1), object(1)
    memory usage: 942.6+ KB
    

Привожу названия столбцов к единому регстру и перевожу столбец "event_dt" к типу datatime


```python
orders = orders.rename(columns={'User Id':'user_id', 'Event Dt':'event_dt', 'Revenue':'revenue'})
```


```python
orders['event_dt'] = pd.to_datetime(orders['event_dt'])
```

##### Таблица Costs

Проверяю на дубликаты и пропуски в таблице "costs", узнаю общую информацию о таблице (название столбцов, типы данных)


```python
print(costs.duplicated().sum())
print(costs.isna().sum())
```

    0
    dt         0
    Channel    0
    costs      0
    dtype: int64
    


```python
costs.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 1800 entries, 0 to 1799
    Data columns (total 3 columns):
     #   Column   Non-Null Count  Dtype  
    ---  ------   --------------  -----  
     0   dt       1800 non-null   object 
     1   Channel  1800 non-null   object 
     2   costs    1800 non-null   float64
    dtypes: float64(1), object(2)
    memory usage: 42.3+ KB
    

Привожу названия столбцов к единому регстру и перевожу столбец "dt" к типу datatime


```python
costs = costs.rename(columns={'Channel':'channel'})
costs['dt'] = pd.to_datetime(costs['dt']).dt.date
```


```python
visits.region = visits.region.str.lower()
visits.device = visits.device.str.lower()
visits.channel = visits.channel.str.lower()
costs.channel = costs.channel.str.lower()
```

#### Промежуточный вывод

В ходе предобработки данных были выполнены следующие действия и сделаны выводы:
- Датасет Visits:
  - Был проверн на наличие пропусков (пропусков не выявлено)
  - Был проверн на наличие явных дубликатов (явных дубликатов не выявлено)
  - Названия столбцов были приведены к нижнему регистру
  - Столбцы "session_start" и "session_end" были приведены в тип данных datetime
- Датасет Orders
  - Был проверн на наличие пропусков (пропусков не выявлено)
  - Был проверн на наличие явных дубликатов (явных дубликатов не выявлено)
  - Названия столбцов были приведены к нижнему регистру
  - Столбец "event_dt" был приведен в тип данных datetime
- Датасет Costs
  - Был проверн на наличие пропусков (пропусков не выявлено)
  - Был проверн на наличие явных дубликатов (явных дубликатов не выявлено)
  - Названия столбцов были приведены к нижнему регистру
  - Столбец "dt" был приведен в тип данных datetime

### Функции для расчёта и анализа LTV, ROI, удержания и конверсии.

Это функции для вычисления значений метрик:

- `get_profiles()` — для создания профилей пользователей,
- `get_retention()` — для подсчёта Retention Rate,
- `get_conversion()` — для подсчёта конверсии,
- `get_ltv()` — для подсчёта LTV.

А также функции для построения графиков:

- `filter_data()` — для сглаживания данных,
- `plot_retention()` — для построения графика Retention Rate,
- `plot_conversion()` — для построения графика конверсии,
- `plot_ltv_roi` — для визуализации LTV и ROI.

#### Фунция get_profiles


```python
def get_profiles(sessions, orders, ad_costs):

    # находим параметры первых посещений
    profiles = (
        sessions.sort_values(by=['user_id', 'session_start'])
        .groupby('user_id')
        .agg(
            {
                'session_start': 'first',
                'channel': 'first',
                'device': 'first',
                'region': 'first',
            }
        )
        .rename(columns={'session_start': 'first_ts'})
        .reset_index()
    )

    # для когортного анализа определяем дату первого посещения
    # и первый день месяца, в который это посещение произошло
    profiles['dt'] = profiles['first_ts'].dt.date
    profiles['month'] = profiles['first_ts'].astype('datetime64[M]')

    # добавляем признак платящих пользователей
    profiles['payer'] = profiles['user_id'].isin(orders['user_id'].unique())


    # считаем количество уникальных пользователей
    # с одинаковыми источником и датой привлечения
    new_users = (
        profiles.groupby(['dt', 'channel'])
        .agg({'user_id': 'nunique'})
        .rename(columns={'user_id': 'unique_users'})
        .reset_index()
    )

    # объединяем траты на рекламу и число привлечённых пользователей
    ad_costs = ad_costs.merge(new_users, on=['dt', 'channel'], how='left')

    # делим рекламные расходы на число привлечённых пользователей
    ad_costs['acquisition_cost'] = ad_costs['costs'] / ad_costs['unique_users']

    # добавляем стоимость привлечения в профили
    profiles = profiles.merge(
        ad_costs[['dt', 'channel', 'acquisition_cost']],
        on=['dt', 'channel'],
        how='left',
    )

    # стоимость привлечения органических пользователей равна нулю
    profiles['acquisition_cost'] = profiles['acquisition_cost'].fillna(0)

    return profiles
```

#### Фунция get_retention


```python
def get_retention(
    profiles,
    sessions,
    observation_date,
    horizon_days,
    dimensions=[],
    ignore_horizon=False,
):

    # добавляем столбец payer в передаваемый dimensions список
    dimensions = ['payer'] + dimensions

    # исключаем пользователей, не «доживших» до горизонта анализа
    last_suitable_acquisition_date = observation_date
    if not ignore_horizon:
        last_suitable_acquisition_date = observation_date - timedelta(
            days=horizon_days - 1
        )
    result_raw = profiles.query('dt <= @last_suitable_acquisition_date')

    # собираем «сырые» данные для расчёта удержания
    result_raw = result_raw.merge(
        sessions[['user_id', 'session_start']], on='user_id', how='left'
    )
    result_raw['lifetime'] = (
        result_raw['session_start'] - result_raw['first_ts']
    ).dt.days

    # функция для группировки таблицы по желаемым признакам
    def group_by_dimensions(df, dims, horizon_days):
        result = df.pivot_table(
            index=dims, columns='lifetime', values='user_id', aggfunc='nunique'
        )
        cohort_sizes = (
            df.groupby(dims)
            .agg({'user_id': 'nunique'})
            .rename(columns={'user_id': 'cohort_size'})
        )
        result = cohort_sizes.merge(result, on=dims, how='left').fillna(0)
        result = result.div(result['cohort_size'], axis=0)
        result = result[['cohort_size'] + list(range(horizon_days))]
        result['cohort_size'] = cohort_sizes
        return result

    # получаем таблицу удержания
    result_grouped = group_by_dimensions(result_raw, dimensions, horizon_days)

    # получаем таблицу динамики удержания
    result_in_time = group_by_dimensions(
        result_raw, dimensions + ['dt'], horizon_days
    )

    # возвращаем обе таблицы и сырые данные
    return result_raw, result_grouped, result_in_time 
```

#### Фунция get_conversion


```python
def get_conversion(
    profiles,
    purchases,
    observation_date,
    horizon_days,
    dimensions=[],
    ignore_horizon=False,
):

    # исключаем пользователей, не «доживших» до горизонта анализа
    last_suitable_acquisition_date = observation_date
    if not ignore_horizon:
        last_suitable_acquisition_date = observation_date - timedelta(
            days=horizon_days - 1
        )
    result_raw = profiles.query('dt <= @last_suitable_acquisition_date')

    # определяем дату и время первой покупки для каждого пользователя
    first_purchases = (
        purchases.sort_values(by=['user_id', 'event_dt'])
        .groupby('user_id')
        .agg({'event_dt': 'first'})
        .reset_index()
    )

    # добавляем данные о покупках в профили
    result_raw = result_raw.merge(
        first_purchases[['user_id', 'event_dt']], on='user_id', how='left'
    )

    # рассчитываем лайфтайм для каждой покупки
    result_raw['lifetime'] = (
        result_raw['event_dt'] - result_raw['first_ts']
    ).dt.days

    # группируем по cohort, если в dimensions ничего нет
    if len(dimensions) == 0:
        result_raw['cohort'] = 'All users' 
        dimensions = dimensions + ['cohort']

    # функция для группировки таблицы по желаемым признакам
    def group_by_dimensions(df, dims, horizon_days):
        result = df.pivot_table(
            index=dims, columns='lifetime', values='user_id', aggfunc='nunique'
        )
        result = result.fillna(0).cumsum(axis = 1)
        cohort_sizes = (
            df.groupby(dims)
            .agg({'user_id': 'nunique'})
            .rename(columns={'user_id': 'cohort_size'})
        )
        result = cohort_sizes.merge(result, on=dims, how='left').fillna(0)
        # делим каждую «ячейку» в строке на размер когорты
        # и получаем conversion rate
        result = result.div(result['cohort_size'], axis=0)
        result = result[['cohort_size'] + list(range(horizon_days))]
        result['cohort_size'] = cohort_sizes
        return result

    # получаем таблицу конверсии
    result_grouped = group_by_dimensions(result_raw, dimensions, horizon_days)

    # для таблицы динамики конверсии убираем 'cohort' из dimensions
    if 'cohort' in dimensions: 
        dimensions = []

    # получаем таблицу динамики конверсии
    result_in_time = group_by_dimensions(
        result_raw, dimensions + ['dt'], horizon_days
    )

    # возвращаем обе таблицы и сырые данные
    return result_raw, result_grouped, result_in_time 
```

#### Фунция get_ltv


```python
def get_ltv(
    profiles,
    purchases,
    observation_date,
    horizon_days,
    dimensions=[],
    ignore_horizon=False,
):

    # исключаем пользователей, не «доживших» до горизонта анализа
    last_suitable_acquisition_date = observation_date
    if not ignore_horizon:
        last_suitable_acquisition_date = observation_date - timedelta(
            days=horizon_days - 1
        )
    result_raw = profiles.query('dt <= @last_suitable_acquisition_date')
    # добавляем данные о покупках в профили
    result_raw = result_raw.merge(
        purchases[['user_id', 'event_dt', 'revenue']], on='user_id', how='left'
    )
    # рассчитываем лайфтайм пользователя для каждой покупки
    result_raw['lifetime'] = (
        result_raw['event_dt'] - result_raw['first_ts']
    ).dt.days
    # группируем по cohort, если в dimensions ничего нет
    if len(dimensions) == 0:
        result_raw['cohort'] = 'All users'
        dimensions = dimensions + ['cohort']

    # функция группировки по желаемым признакам
    def group_by_dimensions(df, dims, horizon_days):
        # строим «треугольную» таблицу выручки
        result = df.pivot_table(
            index=dims, columns='lifetime', values='revenue', aggfunc='sum'
        )
        # находим сумму выручки с накоплением
        result = result.fillna(0).cumsum(axis=1)
        # вычисляем размеры когорт
        cohort_sizes = (
            df.groupby(dims)
            .agg({'user_id': 'nunique'})
            .rename(columns={'user_id': 'cohort_size'})
        )
        # объединяем размеры когорт и таблицу выручки
        result = cohort_sizes.merge(result, on=dims, how='left').fillna(0)
        # считаем LTV: делим каждую «ячейку» в строке на размер когорты
        result = result.div(result['cohort_size'], axis=0)
        # исключаем все лайфтаймы, превышающие горизонт анализа
        result = result[['cohort_size'] + list(range(horizon_days))]
        # восстанавливаем размеры когорт
        result['cohort_size'] = cohort_sizes

        # собираем датафрейм с данными пользователей и значениями CAC, 
        # добавляя параметры из dimensions
        cac = df[['user_id', 'acquisition_cost'] + dims].drop_duplicates()

        # считаем средний CAC по параметрам из dimensions
        cac = (
            cac.groupby(dims)
            .agg({'acquisition_cost': 'mean'})
            .rename(columns={'acquisition_cost': 'cac'})
        )

        # считаем ROI: делим LTV на CAC
        roi = result.div(cac['cac'], axis=0)

        # удаляем строки с бесконечным ROI
        roi = roi[~roi['cohort_size'].isin([np.inf])]

        # восстанавливаем размеры когорт в таблице ROI
        roi['cohort_size'] = cohort_sizes

        # добавляем CAC в таблицу ROI
        roi['cac'] = cac['cac']

        # в финальной таблице оставляем размеры когорт, CAC
        # и ROI в лайфтаймы, не превышающие горизонт анализа
        roi = roi[['cohort_size', 'cac'] + list(range(horizon_days))]

        # возвращаем таблицы LTV и ROI
        return result, roi

    # получаем таблицы LTV и ROI
    result_grouped, roi_grouped = group_by_dimensions(
        result_raw, dimensions, horizon_days
    )

    # для таблиц динамики убираем 'cohort' из dimensions
    if 'cohort' in dimensions:
        dimensions = []

    # получаем таблицы динамики LTV и ROI
    result_in_time, roi_in_time = group_by_dimensions(
        result_raw, dimensions + ['dt'], horizon_days
    )

    return (
        result_raw,  # сырые данные
        result_grouped,  # таблица LTV
        result_in_time,  # таблица динамики LTV
        roi_grouped,  # таблица ROI
        roi_in_time,  # таблица динамики ROI
    )
```

#### Фунция filter_data


```python

def filter_data(df, window):
    # для каждого столбца применяем скользящее среднее
    for column in df.columns.values:
        df[column] = df[column].rolling(window).mean() 
    return df 
```

#### Фунция plot_retention


```python
def plot_retention(retention, retention_history, horizon, window=7):

    # задаём размер сетки для графиков
    plt.figure(figsize=(15, 10))

    # исключаем размеры когорт и удержание первого дня
    retention = retention.drop(columns=['cohort_size', 0])
    # в таблице динамики оставляем только нужный лайфтайм
    retention_history = retention_history.drop(columns=['cohort_size'])[
        [horizon - 1]
    ]

    # если в индексах таблицы удержания только payer,
    # добавляем второй признак — cohort
    if retention.index.nlevels == 1:
        retention['cohort'] = 'All users'
        retention = retention.reset_index().set_index(['cohort', 'payer'])

    # в таблице графиков — два столбца и две строки, четыре ячейки
    # в первой строим кривые удержания платящих пользователей
    ax1 = plt.subplot(1, 2, 1)
    retention.T.plot(
        grid=True, ax=ax1
    )
    plt.legend()
    plt.xlabel('Лайфтайм')
    plt.title('Удержание платящих пользователей')
```

#### Фунция plot_conversion


```python
def plot_conversion(conversion, conversion_history, horizon, window=7):

    # задаём размер сетки для графиков
    plt.figure(figsize=(15, 5))

    # исключаем размеры когорт
    conversion = conversion.drop(columns=['cohort_size'])
    # в таблице динамики оставляем только нужный лайфтайм
    conversion_history = conversion_history.drop(columns=['cohort_size'])[
        [horizon - 1]
    ]

    # первый график — кривые конверсии
    ax1 = plt.subplot(1, 2, 1)
    conversion.T.plot(grid=True, ax=ax1)
    plt.legend()
    plt.xlabel('Лайфтайм')
    plt.title('Конверсия пользователей')

    # второй график — динамика конверсии
    ax2 = plt.subplot(1, 2, 2, sharey=ax1)
    columns = [
        # столбцами сводной таблицы станут все столбцы индекса, кроме даты
        name for name in conversion_history.index.names if name not in ['dt']
    ]
    filtered_data = conversion_history.pivot_table(
        index='dt', columns=columns, values=horizon - 1, aggfunc='mean'
    )
    filter_data(filtered_data, window).plot(grid=True, ax=ax2)
    plt.xlabel('Дата привлечения')
    plt.title('Динамика конверсии пользователей на {}-й день'.format(horizon))

    plt.tight_layout()
    plt.show() 
```

#### Фунция plot_ltv_roi


```python
def plot_ltv_roi(ltv, ltv_history, roi, roi_history, horizon, window=7):

    # задаём сетку отрисовки графиков
    plt.figure(figsize=(20, 10))

    # из таблицы ltv исключаем размеры когорт
    ltv = ltv.drop(columns=['cohort_size'])
    # в таблице динамики ltv оставляем только нужный лайфтайм
    ltv_history = ltv_history.drop(columns=['cohort_size'])[[horizon - 1]]

    # стоимость привлечения запишем в отдельный фрейм
    cac_history = roi_history[['cac']]

    # из таблицы roi исключаем размеры когорт и cac
    roi = roi.drop(columns=['cohort_size', 'cac'])
    # в таблице динамики roi оставляем только нужный лайфтайм
    roi_history = roi_history.drop(columns=['cohort_size', 'cac'])[
        [horizon - 1]
    ]

    # первый график — кривые ltv
    ax1 = plt.subplot(2, 3, 1)
    ltv.T.plot(grid=True, ax=ax1)
    plt.legend()
    plt.xlabel('Лайфтайм')
    plt.title('LTV')

    # второй график — динамика ltv
    ax2 = plt.subplot(2, 3, 2, sharey=ax1)
    # столбцами сводной таблицы станут все столбцы индекса, кроме даты
    columns = [name for name in ltv_history.index.names if name not in ['dt']]
    filtered_data = ltv_history.pivot_table(
        index='dt', columns=columns, values=horizon - 1, aggfunc='mean'
    )
    filter_data(filtered_data, window).plot(grid=True, ax=ax2)
    plt.xlabel('Дата привлечения')
    plt.title('Динамика LTV пользователей на {}-й день'.format(horizon))

    # третий график — динамика cac
    ax3 = plt.subplot(2, 3, 3, sharey=ax1)
    # столбцами сводной таблицы станут все столбцы индекса, кроме даты
    columns = [name for name in cac_history.index.names if name not in ['dt']]
    filtered_data = cac_history.pivot_table(
        index='dt', columns=columns, values='cac', aggfunc='mean'
    )
    filter_data(filtered_data, window).plot(grid=True, ax=ax3)
    plt.xlabel('Дата привлечения')
    plt.title('Динамика стоимости привлечения пользователей')

    # четвёртый график — кривые roi
    ax4 = plt.subplot(2, 3, 4)
    roi.T.plot(grid=True, ax=ax4)
    plt.axhline(y=1, color='red', linestyle='--', label='Уровень окупаемости')
    plt.legend()
    plt.xlabel('Лайфтайм')
    plt.title('ROI')

    # пятый график — динамика roi
    ax5 = plt.subplot(2, 3, 5, sharey=ax4)
    # столбцами сводной таблицы станут все столбцы индекса, кроме даты
    columns = [name for name in roi_history.index.names if name not in ['dt']]
    filtered_data = roi_history.pivot_table(
        index='dt', columns=columns, values=horizon - 1, aggfunc='mean'
    )
    filter_data(filtered_data, window).plot(grid=True, ax=ax5)
    plt.axhline(y=1, color='red', linestyle='--', label='Уровень окупаемости')
    plt.xlabel('Дата привлечения')
    plt.title('Динамика ROI пользователей на {}-й день'.format(horizon))

    plt.tight_layout()
    plt.show() 
```

### Исследовательский анализ данных

#### Профили пользователй и минимальная/максимальная дата привлечения

Построим профили пользователй и узнаем максималную и минимальную дату привлечения пользователей.


```python
profiles = get_profiles(visits, orders, costs)
min_dt = profiles['first_ts'].min()
max_dt = profiles['first_ts'].max()
print(max_dt - min_dt)
print(f'Минимальная дата привлечения пользователя : {min_dt} \nМаксимальная дата привлечения пользователя: {max_dt}')
```

    179 days 23:58:23
    Минимальная дата привлечения пользователя : 2019-05-01 00:00:41 
    Максимальная дата привлечения пользователя: 2019-10-27 23:59:04
    


```python
profiles
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>user_id</th>
      <th>first_ts</th>
      <th>channel</th>
      <th>device</th>
      <th>region</th>
      <th>dt</th>
      <th>month</th>
      <th>payer</th>
      <th>acquisition_cost</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>599326</td>
      <td>2019-05-07 20:58:57</td>
      <td>faceboom</td>
      <td>mac</td>
      <td>united states</td>
      <td>2019-05-07</td>
      <td>2019-05-01</td>
      <td>True</td>
      <td>1.088172</td>
    </tr>
    <tr>
      <th>1</th>
      <td>4919697</td>
      <td>2019-07-09 12:46:07</td>
      <td>faceboom</td>
      <td>iphone</td>
      <td>united states</td>
      <td>2019-07-09</td>
      <td>2019-07-01</td>
      <td>False</td>
      <td>1.107237</td>
    </tr>
    <tr>
      <th>2</th>
      <td>6085896</td>
      <td>2019-10-01 09:58:33</td>
      <td>organic</td>
      <td>iphone</td>
      <td>france</td>
      <td>2019-10-01</td>
      <td>2019-10-01</td>
      <td>False</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>22593348</td>
      <td>2019-08-22 21:35:48</td>
      <td>adnonsense</td>
      <td>pc</td>
      <td>germany</td>
      <td>2019-08-22</td>
      <td>2019-08-01</td>
      <td>False</td>
      <td>0.988235</td>
    </tr>
    <tr>
      <th>4</th>
      <td>31989216</td>
      <td>2019-10-02 00:07:44</td>
      <td>yrabbit</td>
      <td>iphone</td>
      <td>united states</td>
      <td>2019-10-02</td>
      <td>2019-10-01</td>
      <td>False</td>
      <td>0.230769</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>150003</th>
      <td>999956196527</td>
      <td>2019-09-28 08:33:02</td>
      <td>tiptop</td>
      <td>iphone</td>
      <td>united states</td>
      <td>2019-09-28</td>
      <td>2019-09-01</td>
      <td>False</td>
      <td>3.500000</td>
    </tr>
    <tr>
      <th>150004</th>
      <td>999975439887</td>
      <td>2019-10-21 00:35:17</td>
      <td>organic</td>
      <td>pc</td>
      <td>uk</td>
      <td>2019-10-21</td>
      <td>2019-10-01</td>
      <td>False</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>150005</th>
      <td>999976332130</td>
      <td>2019-07-23 02:57:06</td>
      <td>tiptop</td>
      <td>iphone</td>
      <td>united states</td>
      <td>2019-07-23</td>
      <td>2019-07-01</td>
      <td>False</td>
      <td>2.600000</td>
    </tr>
    <tr>
      <th>150006</th>
      <td>999979924135</td>
      <td>2019-09-28 21:28:09</td>
      <td>mediatornado</td>
      <td>pc</td>
      <td>united states</td>
      <td>2019-09-28</td>
      <td>2019-09-01</td>
      <td>False</td>
      <td>0.205714</td>
    </tr>
    <tr>
      <th>150007</th>
      <td>999999563947</td>
      <td>2019-10-18 19:57:25</td>
      <td>organic</td>
      <td>iphone</td>
      <td>united states</td>
      <td>2019-10-18</td>
      <td>2019-10-01</td>
      <td>False</td>
      <td>0.000000</td>
    </tr>
  </tbody>
</table>
<p>150008 rows × 9 columns</p>
</div>



#### Количество и доля пользователей с каждой страны


```python
profiles['payer'] = profiles['user_id'].isin(orders['user_id'].unique())
region_payer = profiles.groupby('region').agg({'payer':'sum', 'user_id':'nunique'}).sort_values(by='payer', ascending=False)
region_payer['payer, %'] = round((region_payer['payer'] / region_payer['user_id']) * 100, 1)
region_payer = region_payer.rename(columns={'user_id':'all'})
region_payer
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>payer</th>
      <th>all</th>
      <th>payer, %</th>
    </tr>
    <tr>
      <th>region</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>united states</th>
      <td>6902</td>
      <td>100002</td>
      <td>6.9</td>
    </tr>
    <tr>
      <th>uk</th>
      <td>700</td>
      <td>17575</td>
      <td>4.0</td>
    </tr>
    <tr>
      <th>france</th>
      <td>663</td>
      <td>17450</td>
      <td>3.8</td>
    </tr>
    <tr>
      <th>germany</th>
      <td>616</td>
      <td>14981</td>
      <td>4.1</td>
    </tr>
  </tbody>
</table>
</div>




```python
visits['region'].unique()
```




    array(['united states', 'uk', 'france', 'germany'], dtype=object)




```python
region_payer['all'].plot(kind='pie', title='Количество пользователей в каждой стране', figsize=[15, 15], ax=plt.subplot(1, 2, 1))
region_payer['payer'].plot(kind='pie', title='Количество платящих пользователей в каждой стране', figsize=[15, 15], ax=plt.subplot(1, 2, 2))
plt.show;
```


    
![png](output_59_0.png)
    


По данным графикам можно сделать вывод, что подавляющее количество всех пользователей из США, как и платящих пользователей. Так же самая высокая доля платящих пользователей тоже в США - около 7-ми процентов. В Европе же (Франция, Гремания, Великобритания) приблизительно одни и те же значения по количество всех пользователей, платящих пользователей и их доли.

#### Количество и доля пользователей с каждого устройства


```python
device_payer = profiles.groupby('device').agg({'payer':'sum', 'user_id':'nunique'}).sort_values(by='payer', ascending=False)
device_payer['payer, %'] = round((device_payer['payer'] / device_payer['user_id']) * 100, 1)
device_payer = device_payer.rename(columns={'user_id':'all'})
device_payer
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>payer</th>
      <th>all</th>
      <th>payer, %</th>
    </tr>
    <tr>
      <th>device</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>iphone</th>
      <td>3382</td>
      <td>54479</td>
      <td>6.2</td>
    </tr>
    <tr>
      <th>android</th>
      <td>2050</td>
      <td>35032</td>
      <td>5.9</td>
    </tr>
    <tr>
      <th>mac</th>
      <td>1912</td>
      <td>30042</td>
      <td>6.4</td>
    </tr>
    <tr>
      <th>pc</th>
      <td>1537</td>
      <td>30455</td>
      <td>5.0</td>
    </tr>
  </tbody>
</table>
</div>




```python
device_payer['all'].plot(kind='pie', title='Количество пользователей по устройствам', figsize=[15, 15], ax=plt.subplot(1, 2, 1))
device_payer['payer'].plot(kind='pie', title='Количество платящих пользователей по устройства', figsize=[15, 15], ax=plt.subplot(1, 2, 2))
plt.show;
```


    
![png](output_63_0.png)
    


Всего у нас четыре платформы, которыми пользуются пользователи: IPhone, Android, PC, Mac. Подавляющее большинство всех пользователей и платящих пользуется IPhone. Но Доля пользователей Mac (6,4%) больше доли IPhone(6,2%), а замыкает этот список PC, его доля составляет всего 5%

#### Количество и доля пользователей с каждого канала


```python
channel_payer = profiles.groupby('channel').agg({'payer':'sum', 'user_id':'nunique'}).sort_values(by='payer', ascending=False)
channel_payer['payer, %'] = round((channel_payer['payer'] / channel_payer['user_id']) * 100, 1)
channel_payer = channel_payer.rename(columns={'user_id':'all'})
channel_payer

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>payer</th>
      <th>all</th>
      <th>payer, %</th>
    </tr>
    <tr>
      <th>channel</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>faceboom</th>
      <td>3557</td>
      <td>29144</td>
      <td>12.2</td>
    </tr>
    <tr>
      <th>tiptop</th>
      <td>1878</td>
      <td>19561</td>
      <td>9.6</td>
    </tr>
    <tr>
      <th>organic</th>
      <td>1160</td>
      <td>56439</td>
      <td>2.1</td>
    </tr>
    <tr>
      <th>wahoonetbanner</th>
      <td>453</td>
      <td>8553</td>
      <td>5.3</td>
    </tr>
    <tr>
      <th>adnonsense</th>
      <td>440</td>
      <td>3880</td>
      <td>11.3</td>
    </tr>
    <tr>
      <th>rocketsuperads</th>
      <td>352</td>
      <td>4448</td>
      <td>7.9</td>
    </tr>
    <tr>
      <th>leapbob</th>
      <td>262</td>
      <td>8553</td>
      <td>3.1</td>
    </tr>
    <tr>
      <th>opplecreativemedia</th>
      <td>233</td>
      <td>8605</td>
      <td>2.7</td>
    </tr>
    <tr>
      <th>lambdamediaads</th>
      <td>225</td>
      <td>2149</td>
      <td>10.5</td>
    </tr>
    <tr>
      <th>yrabbit</th>
      <td>165</td>
      <td>4312</td>
      <td>3.8</td>
    </tr>
    <tr>
      <th>mediatornado</th>
      <td>156</td>
      <td>4364</td>
      <td>3.6</td>
    </tr>
  </tbody>
</table>
</div>




```python
channel_payer['all'].plot(kind='pie', title='Количество пользователей по каналам', figsize=[15, 15], ax=plt.subplot(1, 2, 1))
channel_payer['payer'].plot(kind='pie', title='Количество платящих пользователей по каналам', figsize=[15, 15], ax=plt.subplot(1, 2, 2))
plt.show;
```


    
![png](output_67_0.png)
    


Из графиков и таблицы видно, что больше всего пользователей приходит органически, и только после этого идут два крупных канала TipTop и FaceBoom. Меньше всего польщователей приходит с канала lambdaMediaAds. А вот с платящами пользователями все немного иначе. Больше всего платящих пользователей приходит с канала FaceBoom, после него идет TipToр, потом органически, и только потом идут все остальные каналы. Если говорить про доли пользователей, то самый высокий показатель у канала FaceBoom 12,2%, затем у AdNonSense 11,3%, потом идет lambdaMediaAds c 10,5%, а затем уже TipTop 9б,6%. Худшй показатель у органических пользователей и у канала OppleCreativeMedia 2,7%.

### Маркетинг


```python
costs['costs'].sum()
```




    105497.30000000002



Суммарный расход на маркетинг составил 105497


```python
profiles.groupby('channel')['acquisition_cost'].sum().sort_values(ascending=False)
```




    channel
    tiptop                54751.30
    faceboom              32445.60
    wahoonetbanner         5151.00
    adnonsense             3911.25
    opplecreativemedia     2151.25
    rocketsuperads         1833.00
    leapbob                1797.60
    lambdamediaads         1557.60
    mediatornado            954.48
    yrabbit                 944.22
    organic                   0.00
    Name: acquisition_cost, dtype: float64



Самым дорогим канналом привлечения пользователей стал tiptop, от него недалеко ушел также faceboom


```python
costs['month'] = pd.to_datetime(costs['dt']).dt.month
costs['week']= pd.to_datetime(costs['dt']).dt.isocalendar().week
costs
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>dt</th>
      <th>channel</th>
      <th>costs</th>
      <th>month</th>
      <th>week</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2019-05-01</td>
      <td>faceboom</td>
      <td>113.3</td>
      <td>5</td>
      <td>18</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2019-05-02</td>
      <td>faceboom</td>
      <td>78.1</td>
      <td>5</td>
      <td>18</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2019-05-03</td>
      <td>faceboom</td>
      <td>85.8</td>
      <td>5</td>
      <td>18</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2019-05-04</td>
      <td>faceboom</td>
      <td>136.4</td>
      <td>5</td>
      <td>18</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2019-05-05</td>
      <td>faceboom</td>
      <td>122.1</td>
      <td>5</td>
      <td>18</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>1795</th>
      <td>2019-10-23</td>
      <td>lambdamediaads</td>
      <td>4.0</td>
      <td>10</td>
      <td>43</td>
    </tr>
    <tr>
      <th>1796</th>
      <td>2019-10-24</td>
      <td>lambdamediaads</td>
      <td>6.4</td>
      <td>10</td>
      <td>43</td>
    </tr>
    <tr>
      <th>1797</th>
      <td>2019-10-25</td>
      <td>lambdamediaads</td>
      <td>8.8</td>
      <td>10</td>
      <td>43</td>
    </tr>
    <tr>
      <th>1798</th>
      <td>2019-10-26</td>
      <td>lambdamediaads</td>
      <td>8.8</td>
      <td>10</td>
      <td>43</td>
    </tr>
    <tr>
      <th>1799</th>
      <td>2019-10-27</td>
      <td>lambdamediaads</td>
      <td>12.0</td>
      <td>10</td>
      <td>43</td>
    </tr>
  </tbody>
</table>
<p>1800 rows × 5 columns</p>
</div>




```python
month_table = costs.pivot_table(index='month', columns='channel', values='costs', aggfunc='sum')
week_table = costs.pivot_table(index='week', columns='channel', values='costs', aggfunc='sum')
month_table.plot(legend=True, figsize=[20, 8], ax=plt.subplot(1, 2, 1), \
                 title='Динамики изменения расходов по месяцам по каждому источнику')
plt.ylabel('Расходы')
plt.xlabel('Месяц')
week_table.plot(legend=True, figsize=[20, 8], ax=plt.subplot(1, 2, 2), \
                title='Динамики изменения расходов по неделям по каждому источнику')
plt.ylabel('Расходы')
plt.xlabel('Неделя')
plt.show();
```


    
![png](output_75_0.png)
    


На графиках мы наблюдаем как по месячно и по недельно растут затраты по двум источникам: tiptop и faceboom. В то время как динамика расходов на остальные источники достаточно стабильна и близится к нулю


```python
mean_cost_channel = profiles.groupby('channel')['acquisition_cost'].mean()
mean_cost_channel.sort_values(ascending=False)
```




    channel
    tiptop                2.799003
    faceboom              1.113286
    adnonsense            1.008054
    lambdamediaads        0.724802
    wahoonetbanner        0.602245
    rocketsuperads        0.412095
    opplecreativemedia    0.250000
    yrabbit               0.218975
    mediatornado          0.218717
    leapbob               0.210172
    organic               0.000000
    Name: acquisition_cost, dtype: float64




```python
mean_cost_channel.plot(kind='pie', title='Средняя стоимость привлечения пользователей по каналам', figsize=(15, 15))
```




    <AxesSubplot:title={'center':'Средняя стоимость привлечения пользователей по каналам'}, ylabel='acquisition_cost'>




    
![png](output_78_1.png)
    


На графике и таблице мы видим, что самые дорогие, в прямом смысле слова, пользователи у нас приходят с каналов tiptop, faceboom и adnonsense

### Оценить окупаемость рекламы


```python
observation_date = datetime(2019, 11, 1).date()
analysis_horizon = 14
ad_profiles = profiles.query('channel != "organic"')
```

#### Графики LTV, ROI и графики динамики LTV, CAC, ROI


```python
ltv_raw, ltv_grouped, ltv_history, roi_grouped, roi_history = get_ltv(
    ad_profiles, orders, observation_date, analysis_horizon
)
# строим графики
plot_ltv_roi(ltv_grouped, ltv_history, roi_grouped, roi_history, analysis_horizon) 
```


    
![png](output_83_0.png)
    


Выводы по графикам:
- Реклама не окупается, по графику ROI видно что прибыль составляет чуть больше 80-и процентов
- CAC не стабилен, ниже я проверил правильно ли я его построил, оказалось да. Думаю это связано с тем, что была не одна рекламная компания а несколько. Из-за этого такой нестабильный график.
- График LTV стабилен и постоянно растет

##### Проверка CAC


```python
roi_grouped
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>cohort_size</th>
      <th>cac</th>
      <th>0.0</th>
      <th>1.0</th>
      <th>2.0</th>
      <th>3.0</th>
      <th>4.0</th>
      <th>5.0</th>
      <th>6.0</th>
      <th>7.0</th>
      <th>8.0</th>
      <th>9.0</th>
      <th>10.0</th>
      <th>11.0</th>
      <th>12.0</th>
      <th>13.0</th>
    </tr>
    <tr>
      <th>cohort</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>All users</th>
      <td>88644</td>
      <td>1.117794</td>
      <td>0.309163</td>
      <td>0.389834</td>
      <td>0.451341</td>
      <td>0.501962</td>
      <td>0.547002</td>
      <td>0.58541</td>
      <td>0.620991</td>
      <td>0.652873</td>
      <td>0.684043</td>
      <td>0.712711</td>
      <td>0.739091</td>
      <td>0.762278</td>
      <td>0.785579</td>
      <td>0.806974</td>
    </tr>
  </tbody>
</table>
</div>



Для проверки CAC найдем максимальную дату привлечения


```python
max_acquisition_date = roi_history.reset_index()['dt'].max()
print(max_acquisition_date) 
```

    2019-10-19
    

Максимальная дата привлечения 19 октября 2019 года. Сложим расходы за все дни до максимальной даты привлечения включительно из таблицы с данными о рекламных тратах и сравним результат с произведением CAC и размера когорты из таблицы ROI. Если результаты будут равны, то мы правильно построили график CAC


```python

print(
   'Общие расходы на привлечение из таблицы ROI: {:.2f}'.format(
       roi_grouped.loc['All users', 'cac'] * roi_grouped.loc['All users', 'cohort_size']
   )
)

print(
   'Общие расходы на привлечение из таблицы costs: {:.2f}'.format(
       costs.query('dt <= @max_acquisition_date')['costs'].sum()
   )
) 
```

    Общие расходы на привлечение из таблицы ROI: 99085.74
    Общие расходы на привлечение из таблицы costs: 99085.74
    

Результаты совпали, следовательно мы правильно построили график САС 

#### Графики Retention и Conversion


```python
retention_raw, retention, retention_history  = get_retention(profiles, visits, observation_date, analysis_horizon)
plot_retention(retention, retention_history, analysis_horizon)
```


    
![png](output_93_0.png)
    


Выводы по графику:
- График выглядит нормально, удержание платящих пользователей намного выше неплатящих


```python
conversion_raw, conversion, conversion_history = get_conversion(profiles, orders, observation_date, analysis_horizon)
plot_conversion(conversion, conversion_history, analysis_horizon)
```


    
![png](output_95_0.png)
    


Выводы по графикам:
- График конверсии пользователей также выглядит нормально
- График динамики конверсии пользователей на 14-й день в первые дни привлечения выглядит не лучшим образом, поскольку слишком низкая. Но уже в последующее время конверсия возрастет и показатели стали намного лучше, чем в первые дни.

#### Графики LTV, ROI и графики динамики LTV, CAC, ROI с разбивкой по устройствам


```python
ltv_raw, ltv_grouped, ltv_history, roi_grouped, roi_history = get_ltv(
    ad_profiles, orders, observation_date, analysis_horizon, dimensions=['device']
)
# строим графики
plot_ltv_roi(ltv_grouped, ltv_history, roi_grouped, roi_history, analysis_horizon) 
```


    
![png](output_98_0.png)
    


Выводы по графикам:
- Реклама не окупается, по графику ROI видно что окупается только реклама на PC, процент окупаемости android 90%, а mac и iphone окупаются всего лишь на 70%
- CAC также не стабилен. При низкой окпаемсти mac и iphone их динамика стоимости привлечения клинетов обходится дороже всего, после них идет android и затем pc
- График LTV стабилен и постоянно растет худший показатель по этому графику у PC
- По этим графикам я могу сделать вывод, что пользователи iphone и mac самые невыгодные из представленных

#### Графики LTV, ROI и графики динамики LTV, CAC, ROI с разбивкой по странам


```python
ltv_raw, ltv_grouped, ltv_history, roi_grouped, roi_history = get_ltv(
    ad_profiles, orders, observation_date, analysis_horizon, dimensions=['region']
)
# строим графики
plot_ltv_roi(ltv_grouped, ltv_history, roi_grouped, roi_history, analysis_horizon) 
```


    
![png](output_101_0.png)
    


Выводы по графикам:
- Реклама окупается в европейских государствах, а в США нет. По графику ROI видно что прибыль составляет около 150-и процентов в европейских странах. В США прибыль в районе 70-80%.
- CAC не стабилен, есть резкое падение CAC в европейских странах в июне 2019 года, возможно это было связано с политикой ил чем-то подобным. После этого скачка динамика CАС стабильна. В США в тот же промежуток времени резкий скачок вверх, и показатели продолжают расти. 
- График LTV стабилен и постоянно растет. LTV США составляет около 1,00. А в Европейских государствах в районе 0,7.
- Показатель динамики ROI на 14 день у европейских стран приблизительно похож, а вот в США идет сильно ниже и несет убытки.
- По этим графикам можно сделать вывод, что показатели европейских стран сильно отличаются от показателй США. Реклама в США приносит убыток.

#### Графики LTV, ROI и графики динамики LTV, CAC, ROI с разбивкой по каналам


```python
ltv_raw, ltv_grouped, ltv_history, roi_grouped, roi_history = get_ltv(
    ad_profiles, orders, observation_date, analysis_horizon, dimensions=['channel']
)
# строим графики
plot_ltv_roi(ltv_grouped, ltv_history, roi_grouped, roi_history, analysis_horizon) 
```


    
![png](output_104_0.png)
    


Выводы по графикам:
- Реклама не окупается по трем каналам (tiptop, adnonsense, faceboom), остальные каналы окупаются, opplecreativemedia и wahoonetbanner на 150%, остаьные на 200-300%
- CAC не стабилен по каналу tiptop, у него скачки почти каждый мсяц и цена только увеличивается. Остальные каналы почти стабильны и цена их даже падает как к примеру у канала leapbob.
- График LTV стабилен и постоянно растет, но прирост почти у всех каналов слишком маленький, нормальный прирост только у каналов lambdamediaads и tiptop

#### Исследование отдельно взятого региона


```python
retention_raw, retention, retention_history  = get_retention(profiles, visits, observation_date, analysis_horizon, dimensions=['region'])
plot_retention(retention, retention_history, analysis_horizon)
```


    
![png](output_107_0.png)
    



```python
conversion_raw, conversion, conversion_history = get_conversion(profiles, orders, observation_date, analysis_horizon, dimensions=['region'])
plot_conversion(conversion, conversion_history, analysis_horizon)
```


    
![png](output_108_0.png)
    


Выводы по графикам:
- Конверсия пользователей из европейских стран все также стабильна, но показатели конверсии в США радуют, они сильно выше европейских.
- А вот главная проблема пользователей из Америки это удержание. Коэффициент удержания платящих пользователей из Америки сильно ниже Европейских. Поэтому ROI и был занижен.

#### Исследование отдельно взятых девайсов


```python
retention_raw, retention, retention_history  = get_retention(profiles, visits, observation_date, analysis_horizon, dimensions=['device'])
plot_retention(retention, retention_history, analysis_horizon)
```


    
![png](output_111_0.png)
    



```python
conversion_raw, conversion, conversion_history = get_conversion(profiles, orders, observation_date, analysis_horizon, dimensions=['device'])
plot_conversion(conversion, conversion_history, analysis_horizon)
```


    
![png](output_112_0.png)
    


Выводы по графикам:
- На графике удержания все стабильно, пользователи всех девайсов плюс минус равны.
- На графике конверсии выделяется только PC с показателем конверсии ниже остальных, но сами графики выглядят нормально.

##### Исследования девайсов в Америке


```python
profiles_usa = profiles.query('region == "united states"')
visits_usa = visits.query('region == "united states"')
profiles_usa = profiles_usa.query('payer == True')
retention_raw, retention_usa, retention_history  = get_retention(profiles_usa, visits_usa, observation_date, analysis_horizon, dimensions=['device'])
plot_retention(retention_usa, retention_history, analysis_horizon)
```


    
![png](output_115_0.png)
    



```python
conversion_raw, conversion, conversion_history = get_conversion(profiles_usa, orders, observation_date, analysis_horizon, dimensions=['device'])
plot_conversion(conversion, conversion_history, analysis_horizon)
```


    
![png](output_116_0.png)
    


Выделив отдельно регион Америки и разделив пользователей по девайсам каких-то критических значений я не увидел, все графики выглдят нормально и явных отклонений нет.

##### Исследования девайсов в Европе


```python
profiles_eu = profiles.query('region != "united states"')
visits_eu = visits.query('region != "united states"')
retention_raw, retention_eu, retention_history  = get_retention(profiles_eu, visits_eu, observation_date, analysis_horizon, dimensions=['device'])
retention_eu = retention_eu.query('payer == True')
plot_retention(retention_eu, retention_history, analysis_horizon)
```


    
![png](output_119_0.png)
    



```python
conversion_raw, conversion, conversion_history = get_conversion(profiles_eu, orders, observation_date, analysis_horizon, dimensions=['device'])
plot_conversion(conversion, conversion_history, analysis_horizon)
```


    
![png](output_120_0.png)
    


Выделив отдельно регионы Европы и разделив пользователей по девайсам каких-то критических значений я не увидел, все графики выглдят нормально и явных отклонений нет.

####  Исследование каналов


```python
retention_raw, retention, retention_history  = get_retention(profiles, visits, observation_date, analysis_horizon, dimensions=['channel'])
retention = retention.query('payer == True')
plot_retention(retention, retention_history, analysis_horizon)
```


    
![png](output_123_0.png)
    



```python
conversion_raw, conversion, conversion_history = get_conversion(profiles, orders, observation_date, analysis_horizon, dimensions=['channel'])
plot_conversion(conversion, conversion_history, analysis_horizon)
```


    
![png](output_124_0.png)
    


Выводы по графикам:
- На графике удержания выделяются два канала faceboom и adnonsense их удержание сильно меньше остальных каналов и стремится к нулю
- На графике конверсии выделяется половина всех каналов. Конверия слишком низкая и график выглядит несовсем правильно

##### Исследования каналов в Америке


```python
profiles_usa = profiles.query('region == "united states"')
visits_usa = visits.query('region == "united states"')
retention_raw, retention_usa, retention_history  = get_retention(profiles_usa, visits_usa, observation_date, analysis_horizon, dimensions=['channel'])
retention_usa = retention_usa.query('payer == True')
plot_retention(retention_usa, retention_history, analysis_horizon)
```


    
![png](output_127_0.png)
    



```python
conversion_raw, conversion, conversion_history = get_conversion(profiles_usa, orders, observation_date, analysis_horizon, dimensions=['channel'])
plot_conversion(conversion, conversion_history, analysis_horizon)
```


    
![png](output_128_0.png)
    


Выделив отдельно регион Америки и разделив пользователей по каналам сразу выявились проблемы. Во-первых не все представленные каналы распространяются на американских пользователей. Во-вторых, удержание американских пользователей по каналу faceboom критически мало, оно сильно выбивается из всех остальных, при этом у этого канала самая высокая конверсия среди платящих американских пользователей. Еще хотелось бы выделить конверсию каналов yrabbit и mediatornado, которые практически не растут.

##### Исследования каналов в Европе


```python
profiles_eu = profiles.query('region != "united states"')
visits_eu = visits.query('region != "united states"')
retention_raw, retention_eu, retention_history  = get_retention(profiles_eu, visits_eu, observation_date, analysis_horizon, dimensions=['channel'])
retention_eu = retention_eu.query('payer == True')
plot_retention(retention_eu, retention_history, analysis_horizon)
```


    
![png](output_131_0.png)
    



```python
conversion_raw, conversion, conversion_history = get_conversion(profiles_eu, orders, observation_date, analysis_horizon, dimensions=['channel'])
plot_conversion(conversion, conversion_history, analysis_horizon)
```


    
![png](output_132_0.png)
    


Выделив отдельно регионы Европы и разделив пользователей по каналам сразу выявились проблемы. Вопервых не все представленные каналы распространяются на европейских пользователей. Во-вторых, удержание американских пользователей по каналу adnonsense критически мало, оно сильно выбивается из всех остальных, при этом у этого канала самая высокая конверсия среди платящих европейских пользователей. Еще хотелось бы выделить конверсию каналов opplecreativemedia, leapbob и wahoonetbanner, которые практически не растут.

#### Графики LTV, ROI и графики динамики LTV, CAC, ROI американских пользователей с разбивкой по каналам и по девайсам


```python
ad_profiles_usa = ad_profiles.query('region == "united states"')
```


```python
ltv_raw, ltv_grouped, ltv_history, roi_grouped, roi_history = get_ltv(
    ad_profiles_usa, orders, observation_date, analysis_horizon, dimensions=['channel']
)
# строим графики
plot_ltv_roi(ltv_grouped, ltv_history, roi_grouped, roi_history, analysis_horizon) 
```


    
![png](output_136_0.png)
    



```python
ltv_raw, ltv_grouped, ltv_history, roi_grouped, roi_history = get_ltv(
    ad_profiles_usa, orders, observation_date, analysis_horizon, dimensions=['device']
)
# строим графики
plot_ltv_roi(ltv_grouped, ltv_history, roi_grouped, roi_history, analysis_horizon) 
```


    
![png](output_137_0.png)
    


Так в графиках немного меньше шума, но выводы те же:
CAC TipTop растет скачками от месяца к месяцу, в то время как для остальных платформ стабилен и даже немного снижаетсяреклама в TipTop и FaceBoom не окупается вообще, а в остальных каналах - уже к 2-3 днюLTV стабилен везде.
Девайсы же стабильны и полноценно окупаются

#### Графики LTV, ROI и графики динамики LTV, CAC, ROI европейских пользователей с разбивкой по каналам и по девайсам


```python
ad_profiles_eu = ad_profiles.query('region != "united states"')
```


```python
ltv_raw, ltv_grouped, ltv_history, roi_grouped, roi_history = get_ltv(
    ad_profiles_eu, orders, observation_date, analysis_horizon, dimensions=['channel']
)
# строим графики
plot_ltv_roi(ltv_grouped, ltv_history, roi_grouped, roi_history, analysis_horizon) 
```


    
![png](output_141_0.png)
    



```python
ltv_raw, ltv_grouped, ltv_history, roi_grouped, roi_history = get_ltv(
    ad_profiles_eu, orders, observation_date, analysis_horizon, dimensions=['device']
)
# строим графики
plot_ltv_roi(ltv_grouped, ltv_history, roi_grouped, roi_history, analysis_horizon) 
```


    
![png](output_142_0.png)
    


В Европе не окупается только AdNonSense, но CAC стабильный для всех каналов. И для всех девайсов тоже все хорошо, вся реклама окупается

#### Промежуточные выводы

- Сложно сказать опредленно окупается ли реклама в целом, по сколько на графиках ROI видно, что окупаются только пользователи на PC, из Европейских стран и только 7 из десяти каналов. Но судя по начальным графикам, по всем пользователем, можно сказать, что рекламная компания не окупается.
- Как я написал ранее на окупаемсоти рекламы негативно сказываются пользователи всех устройств кроме PC, пользователи из США (хоть у них и высокая конверсия в сравнении с остальными, у них очень низкий коффициент удержания, как мы выяснили в ходе исследования), и пользователи пришедшие по каналам tiptop, adnonsense, faceboom.
- Больше всего негатвно влияют на окупаемость пользователи из США из-за никзкого коэффициента удержания. Скорее всего это вызвано тем, что рекламная компания хорошо настроена на европейских пользователей, но она не подходит для американских. Также есть убытки из-за пользователей mac, android и iphone. Скорее всего это вызвано тем, что реклама настроена под PC  и удовлетворяет пользователей. В то время как она не настроена для мобильных устройств и пользователей mac.

### Выводы

- причин неэффективности привлечения клиентов есть несколько:
    - неориентированность на американский рынок. Как я утверждал ранее, в ходе исследования было выяснено, что коэффициент удержания американских пользователей ниже, в сравнении с европейскими. Это скорее всего происходит из-за неправильно настроенной рекламы для опредленного региона. 
    - Также есть просадка пользователей мобильных и apple-овских устройств. Тут необходимо понимать, что американские пользователи чаще используют отечесвенные (американские) девайсы, то есть mac и iphone. Из-за этого идет просадка в американском сегменте, не только из-за неправильно настроенной рекламы в связи с регионом, но и также, скорее всего, из-за неадаптированной рекламы на мобильных устройствах, так как android тоже проседает.
    - И еще одна причина это колоссальная цена пользователей, а в следствии колоссальные затраты на некоторые каналы, такие как tiptop, faceboom и adnonsense. И также в ходе исследования была выявлена низкая конверсия у половины всех используемых каналов.
- Рекомендаций будет также три как и причины
    1. Адаптировать рекламу под американских пользователей, учитывая их предпочтения.
    2. Адаптировать рекламу для мобильных утсройств, чтобы это было удобно и практично.
    3. Возможно отказать от некоторых источников и сократить затраты на их использование.
    4. На площадку TipTop была потрачена почти половина бюджета приложения, однако при высоком удержании конверсия средняя и окупаемость очень низкая. В среднем каждый покупатель обошелся более чем в 29. Скорее всего, это очень дорогой канал для рекламы и необходимо либо отказаться от его использования, либо как-то поменять цену.
    5. Второй не окупающийся в США канал рекламы - FaceBoom, у которого низкая конверсия и низкое удержание пользователей. Аналогичная ситуация с площадкой AdNonSense в Европе. Скорее всего, с этих каналов приходит не целевая аудитория и следуюет просто отказаться от этих каналов.
    6. Рекламные бюджеты следует попробовать перераспределить в пользу каналов, окупаемость которых выше: например, lambdaMediaAds	в Европе и RocketSuperAds в США. Оба имеют высокий процент покупателей и низкую стоимость их привлечения.
