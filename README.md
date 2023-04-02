1. Название проекта.
Бот ЧОУ ДПО "Альтернатива" город Челябинск (Официальный сайт https://alt174.ru/).

2. Описание проекта.
Этот телеграм-бот поможет Вам узнать:
- расписание занятий (индивидуальных и групповых);
- необходимые документы для получения или продления действующей лицензии на оружие;
- стоимость обучения;
- теоретические вопросы выносимые на экзамен для получения или продления действующей лицензии на оружие;
- контактную информацию о ЧОУ ДПО "Альтернатива";
- записаться на индивидуальное занятие.

Функционал пользователя:
- FAQ для владельцев личного оружия (владельцев лицензии на его приобретение);
- FAQ для тех, кто планирует получение лицензии на приобретение оружия;
- возможность записи на индивидуальное занятие для сдачи экзамена или повышения навыков владения оружием.

Функционал администратора:
- просмотр и редактирование (внесение, удаление) записи индивидуальных занятий;
- при появлении новой записи на занятия от пользователя, бот в личном сообщении оповещает об этом.

3. Как установить и запустить проект.
- Создайте в корне программы файл ".env" в соответствии с примером из файла ".env.example" и внесите в него свой токен,
полученный от BotFather и администраторов бота.
- установите зависимости, указанные в "requirements.txt".
- для работы с базой данных MongoDB в проекте используется установленная совместно с ботом локальная БД. Если вы 
планируете использовать удаленную БД, то необходимо внести изменения в "work_data/mongodb/database_access.py".
- точка входа - "bot.py".

4. Выражаю признательность за помощь в создании:
- Михаилу Крыжановскому, автору курса "Телеграм-боты на Python и AIOgram";
(https://stepik.org/course/Телеграм-боты-на-Python-и-AIOgram-120924/)
- Александру Харламову (https://github.com/itookyourboo).
 
5. Лицензия
Распространяется на основании GPLv3 (GNU General Public License Version 3)