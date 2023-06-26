# Портфолио: аналитик данных

## Обо мне 

Привет! Меня зовут Ольга, я начинающий аналитик данных. 

В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>

## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``, ``Python``. 
- Языки программирования и библиотеки: ``Python (Jupyter Notebook)``, ``Pandas``, ``Math`` , ``Datetime``, ``Numpy``, ``Scipy.stats``. 
- СУБД: ``PostgreSQL``.
- Средства визуализации данных: ``PowerBi``, ``Matplotlib``, ``Seaborn``


## Проекты
<p> Проект 1: Анализ работы онлайн кинотеатра. Калькулятор юнит-экономики кинотеатра в Excel</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25%-ную маржинальность</li>
  <li>Собрать визуализации основных бизнес-показателей</li>
  <li>Поисследовать данные о пользователях и их поведении</li>
  <li>Прогноз выручки на год</li>
</ol>

<p>Как решала: Провела аналитику по каждому пункту. Визуализацию собрала в презентацию плюс добавила выводы.<p>
<p>Калькулятор учитывает возможность манипуляций с ценой подписки, решение по скидкам, расходам на привлечение, план по привлечению новых пользователей.<p>

> <a href="Проект №1 Excel">Ссылка на проект</a>


<p>Выводы:<p>
<ol>
  <li>Итог №1. Визуализировала поведение пользователей.</li>
  <li>Итог №2. 50% просмотров дают 73 фильма из 5142, что может говорить о возможных проблемах с библиотекой и, как следствие, потери интереса к сервису </li>
  <li>Итог №3. В Июне и Июле затраты на маркетинг были менее эффективны, т.к. привели меньшее количество подписчиков.</li>
  <li>Итог №4. Текущая юнит-экономика не удовлетворительна. Маржа отрицательная -минус 80%. В построенном калькуляторе предложен вариант выхода на стабильную маржинальность в 25%.</li>
</ol>

<br> 

<p> Проект 2: Анализ транзакций по Торговым точкам в Excel </p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Визуализировать динамику транзакций по ТТ. Ответить на вопрос, для какой торговой точки доля по кол-ву транзакций с течением 2020 года снижалась. Указать месяцы наибольшего роста и падения.</li>
  <li>Сделать калькулятор, который будет показывать кол-во транзакций до заданной даты по указанной торговой точке.</li>
  <li>Построить прогноз продаж на основе имеющихся данных</li>
</ol>

<p>Как решала: Построила сводную таблицу по продажам. С помощью гистограмы с накоплениями визуализировала долю каждой ТТ в продажах по месяцам. Прогноз на следующий год построила на основе имеющейся статистики за 2 года с учетом коэффициента сезонности <p>

> <a href=Проект №2 Excel>Ссылка на проект</a>

<p>Выводы:<p>
<ol>
  <li>Итог №1. ТТ Колибри показывает падение по доли в общем количестве транзакций. Наибольший рост транзакций был в декабре, Наибольшее падение в июне.</li>
  <li>Итог №2. Калькулятор создала. Работает при введении даты(из списка) и ТТ по названию. Адрес выпадает по названию. </li>
  <li>Итог №3. Прогнос построила с учетом коэффициента сезонности, что составило +7% к текущим данным. </li>
</ol>

<br> 

<p> Проект 3: Аналитика продаж по ТТ. Сегментация покупок. Прогноз продаж.в Excel<p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Собрать информацию из разных источников. Построить динамику продаж по ТТ по дням. Для каждой ТТ рассчитать долевое участие в общих продажах в руб. Рассчитать по каждой ТТ долю покупок выше 3000руб. Визуализировать результат.</li>
  <li>Построить калькулятор, где при выборе пользователем ТТ(из списка) и даты, будет выводится сумма оплат, количество оплат и среднюю оплату по данной торговой точке за весь период вплоть до указанной даты</li>
  <li>Прогноз по объема оплат на след месяц</li>
</ol>
  
<p>Как решала: Для сбора информации использовала функции ВПР, из поля с датой платежа вытащила месяц, неделю, день. С помьщью сводных постоила оплаты по дням - как линейный график, доли покупок свыше 3000руб и доли ТТ в общем объеме продаж по месацам - нормированная гистограмма с накоплениями. Для калькулятора использовала выпадающие списки и сумм/счетесли. Для прогноза продаж на след месяц провела исследование зависимости результатов продаж от дня недели, дня месяца, проверила наличие единого поведения между ТТ. Поскольку паттернов не выявлено был составлен линейный прогноз продаж с учетом тренда на основе статистики понедельной.<\p>
<p>

> <a href="https://drive.google.com/drive/folders/1wdD-mfSeIsHWgrMLJz8Tv_ClAuP_EAOQ?usp=sharing">Ссылка на проект</a>

<br> 


<p>Проект 4: Построение баланса по студентам онлайн школы за 2016. в SQL <p> 
<p>Что нужно было сделать: <p>
<ol>
 <li>Есть 4 БД: студенты, учителя, уроки, платежи.</li>
 <li>Смоделировать изменение балансов студентов - количество уроков, которое есть у каждого студента.</li>
 <li>Сколько всего уроков было на балансе всех учеников за каждый календарный день</li>
 <li>Как это количество менялось под влиянием транзакций (оплат, начислений, корректирующих списаний) и уроков (списаний с баланса по мере прохождения уроков)</li>
 <li>В результате должен получиться запрос, который собирает данные о балансах студентов за каждый прожитый ими день.</li>
</ol>
  
<p>Как решала: Создала таблицу с начисленными/списанными уроками (по платежам) по каждому студенту с момента старта его учебы (с даты первой оплаты - подзапросом). Создала таблицу по успешным урокам по датам по каждому студенту. Объединила начисленные уроки с фактическими, через оконные функции посчитала накопительный итог по оплаченным и фактическим урокам - получила сводный баланс по датам по студентам. Затем создала запрос на расчет баланса по дням суммарно по всем студентам.<p>

> <a href="https://drive.google.com/drive/folders/1QOk5AAh6x7jK_yHgfKI2sUFYR7AWUi5u">Ссылка на проект</a>

<p>Итоги:<p>
<ol>
  <li>Итог №1. Есть проблемы в файле оплат. Есть 12% студентов, что обучаются более 2-х месяцев, а оплат не было</li>
  <li>Итог №2. Есть проблемы с файлом уроков. Есть 1% студентов, которые спустя 60 дней после оплаты не получили ни одного урока </li>
  <li>Итог №3. Возможно есть проблема с назначением User-ID, ранней цифре User_id соответствует более поздний первый платеж. Требует уточнения.</li>
</ol>

<br> 

<p>Проект 5: Когорный анализ по студентам онлайн школы в SQL </p> 
<p>Что нужно было сделать:<p>
<ol>
  <li>Составить запрос, как для каждой когорты - как ежемесячно меняется доля учеников, пропустивших хотя бы одну неделю за все время от общего кол-ва активных учеников в конкретном месяце.</li>
</ol>

<p>Как решала: Когорты назначила от первого месяца обучения студента. Определила через окнонную функцию кол-во недель от предыдущего занятия. Выделила в отдельные таблицы всех учеников и учеников-прогульщиков. Объединила запросы в один и рассчитала долю прогульщков<p>

> <a href="https://github.com/Skyproportfolio/data-analytics/tree/main/Проект%20№5">Ссылка на проект</a>

<br> 

<p>Проект 6: Анализ платежей в банке в разрезе по категориям, признакам в SQL </p> 
<p>Что нужно было сделать:<p>
<ol>
  <li>Есть 3 таблицы с данными: Информация о клиентах, информация обо всех клиентских платежах, расшифровка идентификаторов городов и наименования федеральных округов, в которых расположены клиентские города</li>
  <li>Для федерального округа "Поволжье" выведите динамику суммарных платежей по дням.</li>
  <li>Для каждого города найдите долю мужчин (% мужчин среди всех клиентов в данном городе). Ограничьтесь только клиентами, которым от 20 до 40 лет. В выводе используйте названия городов, а не идентификаторы.</li>
  <li>Определите средний возраст по тем клиентам, которые ни разу ничего не заплатили.</li>
  <li>Для каждого федерального округа выделите первые три платежа.</li>
  <li>Ограничьтесь клиентами из федеральных округов "Южный" и "Северный". Для каждого города рассчитайте, сколько в среднем времени проходит между платежами одного клиента.</li>
 </ol>

<p>Как решала: Используя join подтянула необходимую информацию, далее используя агрегирующие функции получила запрашиваемые метрики, с помощью where отбирала нужные регионы, города<p>

> <a href="https://github.com/Skyproportfolio/data-analytics/tree/main/Проект%20№6">Ссылка на проект</a>

<br> 

<p>Проект 7: Анализ и визуализация результатов АВ-теста в ритейлере “SkyLenta” в Python</p> 
<p>Что нужно было сделать:<p>
<ol>
  <li>Проверить данные на предмет аномалий</li>
  <li>Исследовать результаты проведенного АВ теста. Оценить эффективность теста</li>
  <li>Визуализировать результат теста в т.ч по городам</li>
  <li>Выдать рекомендации по результатам исследования</li>
</ol>

<p>Как решала: Проверила данные на предмет полноты информации. Исключила ТТ, где группы разделены не верно либо нет результатов. Получила результат эксперимента по среднему платежу и конверсии. Подтвердила статистическую значимость результата с помощью t-test и хи-квадрата, проверила распределение с помощью манн-уитни. Проверила результаты теста по каждому городу и подвела суммарные результаты исхода эксперимента. Составлен калькулятор в Excel для расчета выгод/рисков при продолжении эксперимента.<p>

> <a href="https://github.com/Skyproportfolio/data-analytics/tree/main/Проект%20№7">Ссылка на проект</a>

<p>Выводы:<p>
<ol>
  <li>Итог №1. Статистическая значимость роста среднего платежа и роста конверсии подтверждена </li>
  <li>Итог №2. Исходы эксперимента противоричивы по городам, рекомендуем продолжить эксперимент, скорректировав группы по удаленным ТТ.</li>
  <li>Итог №3. Составлен калькулятор для расчета выгод/рисков при продолжении эксперимента. Вводный параметр кол-во месяцев доп.наблюдений.</li>
</ol>

<br> 

<p>Проект 8: Анализ результатов АВ теста в агрегаторе такси</p> 
<p>Что нужно было сделать:<p>
<ol>
  <li>Проверить результат АВ теста в целом и по каждому городу отдельно.Создать список городов, где исход теста положительный и стат.значимый </li>
  <li>Проверить результат АВ теста в час пик в сравнении с остальными часами.</li>
  <li>Сделать выводы и дать рекомендации.</li>
</ol>

<p>Как решала: Получила результат АВ теста как в целом по всем городам так и по каждому городу отдельно. С помощью цикла и функций T-test, хи-квадрат и манн-уитни проверила распределения и статистическую занчимость роста конверсии в заказы в целом и по каждому городу. Города с подтвержденной статистической значимостью роста в конверсии занесла в список. Проверила результат эксперимента в разрезе час-пика/остальных часов и подтвердила значимость. <p>

> <a href="https://github.com/Skyproportfolio/data-analytics/tree/main/Проект%20№8">Ссылка на проект</a>

<p>Выводы:<p>
<ol>
  <li>Итог №1. Общий результат теста показывает положительное влияние на рост конверсии. Статистическая разница роста конверсии подтверждена.</li>
  <li>Итог №2. Положительная динамика по конверсии статистически подтверждена только в 3 городах</li>
  <li>Итог №3. Положительная динамика по конверсии статистически подтверждена как на пиковых, так и на НЕ пиковых заказах.</li>
  <li>Итог №4. Как промежуточный результат, ТЕСТ показывает статистически подтвержденную положительную динамику конверсии. Тест необходимо продолжить для получения большего количества наблюдений и подтверждения эффективности теста по всем городам.</li>
</ol>



## Контактная информация
- Email: arina.olga@gmail.com
<!---
Arina-portfolio/Arina-portfolio is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
