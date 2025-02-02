ОПИСАНИЕ
--------

Плагин «Mailing» предназначен для создания и отправки больших рассылок.

* Есть возможность фильтра получателей по свойству «Пол» («мужчины»,
«женщины», «не указан»);
* Есть возможность фильтра получателей по свойству «Язык» (интеграция с плагином "L10n");
* Можно посмотреть список рассылок и статус хода рассылки;
* В списке рассылок можно приостановить начатую рассылку или возобновить приостановленную;
* Можно выбирать стартовать или не стартовать рассылку сразу после её сохранения;
* Рассылка производится не сразу, а пачками по 20 писем (количество можно
менять в конфиге). Для этого нужно поцепить на cron скрипт рассылки
/plugins/mailing/include/cron/send-mail.php
* Отправленные сообщения не отображаются в вашем списке сообщений до тех пор
пока пользователь не ответит на это сообщение (вам ведь важна обратная связь
с пользователями?).


ЛИЦЕНЗИИ
-------

Файлы в этом архиве распостраняются по лицензии GNU GPL. Вы можете найти копию
этой лицензии в файле LICENSE.txt.


ИСТОРИЯ ВЕРСИЙ
--------------
v0.3.0
- Переписан для работы с LiveStreet не ниже версии 0.5.0
- Работает с Mootools и jQuery шаблонами
- Добавлена очистка кеша после (де)активации плагина.
- Добавлен предпросмотр отредактированого письма рассылки.

v0.2.1
- Поправлена ошибка, которая появлялась при неактивном плагине L10n.

v0.2.0
- Добавлена поддержка плагина "L10n", именно фильтрация получателей рассылки по языку.

v0.1.0
- Релиз плагина