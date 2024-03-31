
# Домашние задания по модулю  «Отказоустойчивость»

В этом репозитории расположены ваши домашние задания к каждой лекции. 

Обязательны к выполнению задачи без звездочек. Их нужно выполнить, чтобы получить зачёт.

Задачи со звёздочкой (*) — дополнительные задачи или задачи повышенной сложности. Их выполнять не обязательно, но они помогут вам глубже понять тему.

Любые вопросы по решению задач задавайте в чате учебной группы. Ссылку вы найдёте в письме на вашей электронной почте.
=======
# Домашнее задание к занятию "Отказоустойчивость в облаке" - Лапшов Сергей
=======
### Задание 1

1. `Для бюджетирования проектов с последующим формированием финансовых аналитических отчетов и прогнозирования рисков лучше всего подходят реляционные базы данных, такие как PostgreSQL или Oracle. Они обеспечивают целостность данных и позволяют строить четкую структуру данных. Для ускорения работы с хешами можно использовать API, такие как Redis или Memcached, которые позволяют кэшировать данные и ускорять доступ к ним.`
2. `Для лендингов и CRM идеально подходят гибкие и быстрые NoSQL базы данных, такие как MongoDB или Cassandra. Они позволяют эффективно обрабатывать большие объемы данных и быстро масштабироваться. Возможно использование одной базы данных для обеих задач, например, MongoDB с различными коллекциями для лендингов и CRM.`
3. `Для отдела контроля качества подойдет реляционная база данных с простой и понятной структурой, такая как SQLite или MySQL. Для этой задачи можно использовать уже существующую СУБД из предыдущих задач, создав новые таблицы или даже базу данных в рамках существующего инсталляции.`
4. `Для задач логистики, связанных с быстрым формированием маршрутов доставки и распределением курьеров, наиболее подходят графовые базы данных, такие как Neo4j или Amazon Neptune. Они хорошо работают с данными, связанными с сетями и маршрутами. Можно использовать одну базу данных для логистики и закупок, если их процессы тесно связаны и требуют обмена данными.`
5. `Да, все перечисленные выше задачи можно решить, используя одну базу данных. Например, MongoDB предоставляет гибкость и масштабируемость для работы с различными типами данных, а также поддерживает функциональность кэширования для ускорения доступа к данным. Однако, для некоторых специфических задач может потребоваться комбинация различных типов баз данных для оптимальной производительности и функциональности.`
6. 

```

```

`При необходимости прикрепитe сюда скриншоты
![ ]( )
---

### Задание 2

`Приведите ответ в свободной форме........`

1. `Пополнение баланса счета телефона:
    1.Инициация запроса: Пользователь инициирует запрос на пополнение баланса своего телефона. Это может быть сделано через мобильное приложение, интернет-банкинг или другие доступные каналы.
    2.Валидация данных: Система проверяет данные, введенные пользователем, чтобы убедиться, что они корректны и соответствуют требуемым форматам. Например, проверка на наличие достаточного количества средств на счету пользователя или на правильность введенного номера телефона.
    3.Авторизация платежа: Система обращается к платежному шлюзу или платежной системе для авторизации транзакции. Платежная система проводит проверку наличия средств и подтверждает возможность проведения операции.
    4.Выполнение транзакции: После успешной авторизации система осуществляет фактическое списание средств со счета пользователя и зачисление их на баланс телефона.
    5.Обновление данных: Система обновляет данные о балансе телефона и транзакции в своей базе данных для отражения изменений.
    6.Отправка уведомления: Пользователю отправляется уведомление о результате транзакции - успешном пополнении баланса. Это может быть сделано через SMS, push-уведомление в мобильном приложении или по электронной почте.`
2. `Пополнение баланса счета телефона через автоплатеж:
    1.Автоматическая инициация: Платежная система автоматически инициирует транзакцию пополнения баланса в соответствии с заранее заданными настройками пользователя.
    2.Проверка наличия средств: Система проверяет, достаточно ли средств на счете пользователя для автоматического списания.
    3.Авторизация платежа: После проверки система направляет запрос на авторизацию платежа в платежный шлюз или платежную систему.
    4.Выполнение транзакции: При успешной авторизации платежа средства автоматически списываются со счета пользователя и зачисляются на его баланс телефона.
    5.Обновление данных: Система обновляет информацию о балансе телефона и записывает информацию о проведенной транзакции.
    6.Отправка уведомления: Пользователю отправляется уведомление о результате транзакции - успешном пополнении баланса телефона через автоплатеж.`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```

```

`При необходимости прикрепитe сюда скриншоты
![ ]( )


---

### Задание 3

`Приведите ответ в свободной форме........`

1. `Преимущества SQL-систем по отношению к NoSQL:
    1.Структурированные данные: SQL-системы предоставляют схему данных, что обеспечивает строгую структуру и типы данных, что упрощает разработку и поддержку приложений.
    2.ACID-транзакции: SQL базы данных обеспечивают транзакционную целостность данных благодаря ACID-свойствам (атомарность, согласованность, изолированность, долговечность), что гарантирует надежность и целостность данных.
    3.Мощный язык запросов: SQL предоставляет богатый и выразительный язык запросов, который позволяет выполнять сложные аналитические запросы, объединения данных и агрегации.
    4.Поддержка соединений: SQL базы данных обеспечивают мощные механизмы для объединения данных из разных таблиц, что позволяет эффективно работать с связанными данными.
    5.Широкое распространение и поддержка: SQL базы данных, такие как MySQL, PostgreSQL, Microsoft SQL Server, имеют долгую историю развития, широкое распространение и обширную базу знаний и сообщества для поддержки.`
2. `Преимущества NewSQL систем перед SQL и NoSQL:
    1.Горизонтальное масштабирование: NewSQL системы предлагают возможность горизонтального масштабирования, что позволяет эффективно управлять большими объемами данных и обеспечивать высокую производительность.
    2.Высокая производительность: NewSQL системы обеспечивают высокую производительность и надежность при работе с транзакционными данными, что делает их привлекательным выбором для критически важных приложений.
    3.Поддержка ACID-транзакций: В отличие от некоторых NoSQL систем, многие NewSQL системы поддерживают ACID-транзакции, обеспечивая высокую надежность и целостность данных.
    4.Совместимость с SQL: NewSQL системы обычно поддерживают SQL-совместимый интерфейс, что упрощает разработку приложений и интеграцию с существующими системами.
    5.Гибкость и масштабируемость: NewSQL системы обладают гибкостью и масштабируемостью, позволяя адаптироваться к различным требованиям приложений и обеспечивать высокую производительность при росте нагрузки.`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`

### Задание 4

`Приведите ответ в свободной форме........`

1. `При выборе типа СУБД и модели распределенных вычислений для обработки большого объема данных на 1000 машинах, следует учитывать несколько ключевых критериев:
    1.Типы данных и вычислений: Необходимо понять, какие типы данных обрабатываются и какие вычисления требуются. Если данные представляют собой структурированные таблицы или требуют выполнения сложных SQL-запросов, то реляционные СУБД, такие как PostgreSQL или MySQL с поддержкой распределенных вычислений, могут быть подходящим выбором. Если требуются более сложные аналитические вычисления, то можно обратить внимание на NoSQL базы данных, такие как Apache Cassandra или Apache Hadoop.
    2.Масштабируемость: Важно выбрать СУБД и модель распределенных вычислений, которые обеспечивают горизонтальное масштабирование на 1000 машин. Это может быть реализовано с помощью технологий, таких как Apache Hadoop, Apache Spark или Google Cloud BigQuery, которые позволяют распределить вычисления и данные на большое количество узлов.
    3.Производительность: Необходимо оценить производительность выбранной СУБД и модели распределенных вычислений при обработке данных на 1000 машинах. Это включает в себя анализ скорости выполнения запросов, обработки данных и масштабируемости при увеличении нагрузки.
    4.Сложность развертывания и управления: Важно учитывать сложность развертывания и управления выбранной СУБД и модели распределенных вычислений на 1000 машинах. Некоторые системы могут требовать большего усилия для настройки, мониторинга и обслуживания.`
2. `С учетом этих критериев можно принять решение о выборе оптимального типа СУБД и модели распределенных вычислений. Например, если требуются сложные аналитические вычисления и большая гибкость в структуре данных, то Apache Spark с использованием NoSQL базы данных, такой как Apache Cassandra, может быть хорошим выбором для обработки данных на 1000 машинах. В то же время, если необходима поддержка транзакций и структурированных данных, то можно обратить внимание на реляционные базы данных с поддержкой распределенных вычислений, такие как Google Cloud BigQuery или Amazon Redshift.`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`
>>>>>>> 73d1e2b (commit)