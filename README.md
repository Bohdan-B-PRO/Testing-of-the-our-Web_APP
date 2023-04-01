Прежде нам приступить к тестированию на нужно обсудить некоторые моменты по которым я распишу тоесть допишу наш план тестирования.
# Шаг 1. Анализ продукта

При создании плана тестирования нам необходимо разбить наш продукт на более мелкие компоненты. Это позволит нам определить лучший процесс тестирования в зависимости от типа создаваного нами продукта тоесть:
- Определить все функции нашего продукта
- Определить, сколько тестовых сценариев необходимо для каждой функции
- Составьте список, что должно быть проверено

# Шаг 2. Разработайте стратегию

Для разработки стратегии тестирования нам нужно определить некоторые моменты, тобишь:

**Соберить все тестовые сценарии** — это поможет нам определить не только то, что нужно протестировать, но и то, когда это следует протестировать для получения оптимальных результатов. **Напомю!** Тестовый сценарий — это описание начальных условий, входных данных, действий пользователя и ожидаемого результата.
Хорошая практика — написание тестовых сценариев на основании вариантов использования (Use cases).

**Определяем объема тестирования.** Прежде чем приступить к работе, необходимо определить объем тестирования. Это включает в себя решение о том, что необходимо протестировать, кто будет проводить тестирование и когда оно должно быть завершено.

**Определяем виды тестирования.** После того, как мы определили объем, нужно определить, какие виды тестирования необходимо выполнить. 

**Разработка подхода к тестированию.** После того, как мы определили объем, виды тестирования и определили сопутствующие риски, нужно создать свой подход к тестированию. Что я подрозумиваю под этим? Это какие уровни тестирования у нас будут.

# Шаг 4. Определить цели

Что это значит? Это — нужно выяснить, каковы цели нашего тестирования. Это включает в себя определение ответственных за тестирование, решение о том, что будет тестироваться, когда оно должно быть завершено, и как будут оцениваться результаты. Нам также необходимо определить, какие функции необходимо протестировать и как они будут разбиты (например, основные и второстепенные цели). Нам следует рассмотреть возможность использования целей SMART для нашего теста обеспечения качества. Если кто-то читал ту тиорию которою я состовлял там чётко и полноценно расписано что это и зачем. Но, а если в кратце это - цели, по которым мы максимально точно и детально расписываете желаемый результат для проекта, компании и тд. В нашем случае и в данный момент это целили тестирования. Цель будет понятна и эффективна, если она обладает следующими характеристиками:
- Конкретная; Тоесть какого именно результата мы хотим достичь от нашего тестирования?
- Измеримая; По какому показателю мы поймём что мы пришли к цели?
- Достижимая; Достижима ли наша цель?
- Актуальная; Насколько актуально в данный момент та или иная цель?
- Ограниченная во времени; Когда мы хотим придти к цели?

# Шаг 5. Определяем критерии теста
Для каждой функции вашего продукта нам необходимо определить, какие критерии должны быть соблюдены, чтобы тест прошел успешно. Эти критерии можно разделить на две основные подкатегории:

**Критерии приостановки** — это условия, которые требуют временной остановки тестирования. То есть статус теста Failed, bloked, skipped...
**Критерии выхода** — это условия, при котором мы будем считать что испытаени / тест успешне. Когда критерий выхода выполнен, тест может перейти к следующему этапу. Тут понятно, статус - Passed

# Шаг 7. Спланированировать тестовую среду

Это включает в себя все, от того, где будут проводиться тесты, до того, как это должно быть сделано и кто будет это делать. Вот основной список дел:
- Определите конкретное место, где будет проходить тестирование. Допустим на разных браузерах.
- Определите типы устройств, необходимых для тестирования. Допустим на разных устройствах

Теперь перйдём к более подробному разбору наших вопросов https://docs.google.com/spreadsheets/d/15uEZOkarMuQwPsIlFRrn7Zjw-rTRVEATTZ_y7j-Li-s/edit#gid=0

















# Примечание

**Этот репозитории мы можем использовать как для тестирования нашего проекта, так и в дальнейшем для нашей работы. Также предлогаю в нём делится и добавлять все интересные ссылки на материалы о тестировании. Ссылки не дублируются, даже если название одинкаовое и информация какбы о одном и томже но нет, всегда есть что подчеркнуть!**

**Правила использования, можно: делится; forking и добовлять свои источники(**это даже нужно!**), пулить с обновлённой инфой.**

**Запрещено: присылать пулы с удалённой информацией с исходника, т.к я могу не заметить изминений с удалением!**

# Материалы для тестирования:

## Основное

### Руководство по сквозному тестированию: что такое E2E-тестирование с примерам
https://habr.com/ru/company/otus/blog/681066/

### Разные подходы к тестированию: в чем их суть и какой выбирать для своих проектов
https://habr.com/ru/company/sbermarket/blog/665260/

### Фундаментальная теория тестирования
https://habr.com/ru/post/549054/

### Виды тестирования
https://gb.ru/lessons/284433

### Виды тестирования ПО
https://qaevolution.ru/testirovanie-po/vidy-testirovaniya-po/

## Тестовая документаация

### Создание чек-листов. Практика
https://gb.ru/lessons/263284

### Создание тест-кейсов. Практика
https://gb.ru/lessons/263286

### Создание баг-репортов. Практика
https://gb.ru/lessons/263288

## Иструменты тестирования Web

### DevTools
https://gb.ru/lessons/263290

### Chrome DevTools
https://gb.ru/lessons/283280

### Charles Proxy
https://gb.ru/lessons/263293

## Здесь также можно найти много интересной информации

Тестирования ПО # Лёша Маршал 
https://www.youtube.com/c/ЛёшаМаршал

Artsiom Rusau 
QA Life https://www.youtube.com/@rusau

okiseleva 
https://www.youtube.com/@okiseleva/featured
