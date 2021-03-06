### Типы публикаций

В Movable Type существует несколько типов публикации. Вы можете использовать любой тип и любую их комбинацию. Например, некоторые файлы, включающие в себя множество данных, рекомендуется кешировать и публиковать при помощи очереди публикации.

##### Статическая публикация

Файлы публикуются сразу, как только изменился тот или иной контент. Например, индексный шаблон «Главная страница» будет автоматически опубликован, когда вы добавите новую запись. Также этот шаблон будет опубликован, когда к этой записи добавят комментарий.

##### Динамическая публикация

Существуют следующие варианты:

* полная динамическая публикация, когда запросы обрабатываются скриптом `mt-view.php`;
* ручная, когда создаётся один индексный шаблон и один модульный, чтобы, например, сделать пейджинацию — [Пейджинация на PHP и Smarty](#doc-php-pagination);
* совмещение того и другого.

##### Ручная публикация
Этот вариант удобен для публикации различных индексных шаблонов типа CSS, Javascript и других неизменяемых файлов. Шаблон опубликуется только тогда, когда вы это сделаете.

##### Очередь публикации

Очередь публикации — это список задач, который выполняется при запуске скрипта `run-periodic-tasks` (скрипт находится в папке `tools`).

