# Проект "Предобработка данных"
## Описание проекта

Заказчик — кредитный отдел банка. 
Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

## Цели проекта:

1) На основе статистики о платёжеспособности клиентов исследовать влияние целей кредита, уровня месячного дохода, семейного положения, количества детей клиента на вероятность возврата кредита в срок.

2) Получить практические навыки в предобработке данных, оценивать, подходят ли данные для проверки гипотез:

- узнать методы обработки пропусков;
- научиться преобразовывать один тип данных в другой;
- определять дубликаты и обрабатывать их различными способами;
- понять, как разделять данные на категории.
### Задачи проекта

- Проанализировать данные о статистике платежеспособности клиентов
- Выделить группы целей на получение кредита
- Проанализировать причины задолженностей клиентов по кредитам

## Итоги:

- Среди целей на получение кредита было выделено 4 категории: операции с автомобилем, операции с недвижимостью, проведение свадьбы, получение образования.
- Были проанализированы задолженности клиентов по кредитам в зависимости от количества детей, семейного положения, уровня месячного дохода и цели кредита.
- По всем категориям доли клиентов с задолженностями не превышала 10%, а различия значений между отдельными группами разделения не превышали 3.5%.

Используемый стек инструментов:

- python
- pandas
