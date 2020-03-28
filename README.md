# Силовой модуль полумоста

Для упрощения и ускорения процесса макетирования силовых преобразователей можно использовать полумостовой модуль. Большинство современных топологий построены из одного или нескольких полумостов, что позволяет, собрав однотипный удобный для монтажа модуль, макетировать преобразователи энергии практически любой сложности на мощностях до 1500 Вт.

![Силовой модуль](https://habrastorage.org/webt/bp/_y/4n/bp_y4nwmd0wuvems9xmc-zyptug.jpeg)

Данный силовой модуль может быть собран в двух вариантах: низковольтным (до 100В) и высоковольтном (до 600В). Максимальное рабочее напряжение зависит от примененных конденсаторов С7-C9 и силовых транзисторов VT1-VT4. Примененная связка *"dc/dc + драйвер 1EDC60I12AHXUMA1"* позволяет устанавливать транзисторы с рабочим напряжение до 1200В.

# Технические характеристики

* Напряжение сток-исток: *до 1200В*
* Номинальный ток: *20А*
* Максимальная частота: *600кГц*
* Ток драйвера: *+6/-10А*
* Напряжение изоляции: *1500В*
* Защита по току: *да*
* Гальваническая развязка: *да*
* Индикация ошибок: *да*
* Температура эксплуатации: *-20...+65<sup>o</sup>C*

# Структура проекта

* Hardware
    * Documents
    * Manufacture
    * AltiumProject
    * Mechanical

# Лицензирование

Все исходные материалы для проекта распространяются по лицензии [MIT](./LICENSE "Описание лицензии"). Вы можете использовать проект в любом виде, в том числе и для коммерческой деятельности, но стоит помнить, что автор проекта не дает никаких гарантий на работоспособность устройства или частей проекта, а так же не несет никакой ответственности по искам или за нанесенный ущерб.

