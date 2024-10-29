Ссылка на презентацию - https://public.tableau.com/app/profile/.22018694/viz/CarsSales_17225850477020/sheet22?publish=yes
# Проект: Анализ рынка и определение лучших штатов для открытия автосалона компании NovaDrive Motors в США

В отдел аналитики компании NovaDrive Motors поступила задача провести анализ данных о продажах автомобилей в США, чтобы определить оптимальный штат для открытия первого автосалона компании.

**Описание компании:**
NovaDrive Motors — это ведущий европейский производитель автомобилей, специализирующийся на выпуске высококачественных седанов и кроссоверов. Благодаря современным технологиям и качеству, компания уже завоевала значительную долю на европейском рынке и пользуется высоким доверием среди клиентов.

**Причина выхода на новый рынок:**
С целью расширения бизнеса и увеличения продаж NovaDrive Motors решила выйти на рынок США. Американский рынок автомобилей является одним из крупнейших и наиболее конкурентных в мире. Вход на этот рынок предоставляет отличные возможности для роста и укрепления позиций компании на глобальном уровне.

**Цель проекта** - анализ данных о продажах автомобилей в США для определения оптимальных штатов для открытия автосалонов NovaDrive Motors. Также необходимо определить самые популярные критерия автомобиля (трансмиссия, цвет).

# Описание данных

- year - год выпуска автомобиля;
- make - название производителя;
- model - модель автомобиля;
- trim - дополнительное обозначение модели транспортного средства;
- body - тип кузова автомобиля (седан, кроссовер и пр.);
- transmission - тип трансмиссии автомобиля (автомат, ручная коробка);
- vin - идентификационный номер транспортного средства - уникальный код для каждого транспортного средства;
- state - штат, в котором зарегестрирован автомобиль;
- condition - оценка состояния автомобиля (от 1 до 5);
- odometer - пробег автомобиля;
- color - цвет автомобиля;
- interior - цвет интерьера;
- seller - компания, которая занималась продажей автомобиля;
- mmr - текущие рыночные данные о стоимости подержанных автомобилей, которые рассчитываются на основе результатов аукционов;
- sellingprice - цена продажи;
- saledate - дата продажи.


## Вывод

В ходе проведенного анализа американского рынка продаж автомобилей определили, что наиболее подходящими штатами для открытия автосолонов являются fl (Флорида), ca (Калифорния) и ga (Джорджия), так как в данных штатан наибольший спрос на автомобилия с типом кузова кроссовер и седан. Также определили самые популярные параметры автомобилей с каждым из типов кузова:

- показатели средней цены на кроссоверы в штатах: ca - 30136.43, fl - 28760.69, ga - 26564.29. Значенмя средней цены на седаны в штатах: ca - 22993.88, fl - 20770.74, ga - 17998.25;
- Основные конкуренты по штатам для кроссоверов:
    - в штате ga (Джорджия) являются Jeep и Ford;
    - в штате ca (Калифорния) являются Nissan и Subaru;
    - в штате fl (Флорида) являются Jeep и Ford.
- Основные конкуренты по штатам для седанов:
    -основными конкурентами в штате ga (Джорджия) являются Nissan и Toyota;
    - основными конкурентами в штате ca (Калифорния) являются Hyundai и Nissan;
    - основными конкурентами в штате fl (Флорида) являются Toyota и Hyundai.
    - абсолютное большинство занимают седаны с автоматической коробкой как для кроссоверов, так и для седанов;
    - в каждом штате самым распространенным цветом является белый, серый и серебристый для кроссоверов. Для седанов в штатах ga и ca самыми популярными цветами является белый, серый и серебристый. В штате fl это цвета белый, серый, серебристый;
    - самый распространенный цвет салона автомобиля - черный, серый, бежевый для обоих типов кузова.