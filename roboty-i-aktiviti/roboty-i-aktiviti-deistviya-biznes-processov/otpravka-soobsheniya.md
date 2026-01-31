# Отправка сообщения

### Настройка робота

Для отправки сообщения добавьте робота «\[OLChat: Telegram] Отправка сообщения». Для этого перейдите в **Роботы ‒ Создать ‒ Выбор стадии ‒ Другие роботы ‒ \[OLChat: Telegram] Отправка сообщения ‒ Добавить.**

<figure><img src="../../.gitbook/assets/Отправка сообщения (1).png" alt=""><figcaption></figcaption></figure>

Выполните настройку робот&#x430;**.** Для этого на добавленном роботе нажмите на кнопку «изменить», чтобы открыть интерфейс редактирования робота:

1. В поле **Линия коннектора** укажите линию, через которую планируете сделать отправку
2. Укажите **Тип идентификатора чата**. В качестве идентификатора может выступать **ID чата, Номер телефона** или **Имя пользователя**.
3. В зависимости от выбранного типа идентификатора, в поле **Идентификатор чата** укажите **Номер телефона, ID чата** или **username,** куда будет отправлено сообщение.
   *   <sub>Если в поле</sub> <sub></sub><sub>**«Идентификатор чата»**</sub> <sub></sub><sub>вы выбираете вариант</sub> <sub></sub><sub>**«Номер телефона»**</sub><sub>, важно убедиться, что в настройках робота указано</sub> <sub></sub><sub>**корректное поле с номером телефона**</sub><sub>.</sub>

       <sub>Например, если в карточке клиента заполнено поле</sub> <sub></sub><sub>**«Мобильный телефон»**</sub><sub>, а в настройке робота в строке</sub> <sub></sub><sub>**«Номер телефона»**</sub> <sub></sub><sub>указана переменная</sub> <sub></sub><sub>**\{{Рабочий телефон\}}**</sub><sub>, робот</sub> <sub></sub><sub>**не сможет найти номер**</sub> <sub></sub><sub>— в результате сообщение</sub> <sub></sub><sub>**не будет отправлено**</sub><sub>.</sub>\ <sub>Чтобы робот корректно подставлял номер из</sub> <sub></sub><sub>**любого**</sub> <sub></sub><sub>заполненного телефонного поля, рекомендуем в строке</sub> <sub></sub><sub>**«Номер телефона»**</sub> <sub></sub><sub>выбрать переменную</sub> <sub></sub><sub>**\{{Телефон (текст)\}}**</sub><sub>.</sub>

       <sub>Указать её можно через меню</sub> <sub></sub><sub>**«…» (три точки)**</sub> <sub></sub><sub>напротив строки</sub> <sub></sub><sub>**«Номер телефона»**</sub><sub>.</sub>
4. Введите текст **Сообщения.**
5. В поле **Публикация в чате открытой линии?** укажите каким образом отправленное роботом сообщение отобразится в чате Открытой линии. Доступны варианты: **Входящим сообщением в ОЛ, Без публикации в ОЛ** и **Исходящим в ОЛ.**

{% hint style="warning" %}
В настоящее время **Публикация в чате открытой линии** возможно только **Входящим сообщением!** Публикация **Исходящим в ОЛ** недоступна. Техотдел работает над добавлением такой возможности.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (943).png" alt=""><figcaption></figcaption></figure>

Остальные настройки можно оставить по умолчанию. Нажмите на кнопку «СОХРАНИТЬ»

### Настройка активити (действия) бизнес-процесса

Для отправки сообщения из бизнес-процесса добавьте действие «\[OLChat: Telegram] Отправка сообщения».&#x20;

<figure><img src="../../.gitbook/assets/image (941).png" alt=""><figcaption></figcaption></figure>

Выполните настройку параметров действия:

1. В поле **Линия коннектора** укажите линию, через которую планируете сделать отправку
2. Укажите **Тип идентификатора чата**. В качестве идентификатора может выступать **ID чата, Номер телефона** или **Имя пользователя.**
3. В зависимости от выбранного типа идентификатора, в поле **Идентификатор чата** укажите **Номер телефона, ID чата** или **username,** куда будет отправлено сообщение.
   *   <sub><mark style="background-color:$info;">Если в поле<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">**«Идентификатор чата»**<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">вы выбираете вариант<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">**«Номер телефона»**<mark style="background-color:$info;"></sub><sub><mark style="background-color:$info;">, важно убедиться, что в настройках робота указано<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">**корректное поле с номером телефона**<mark style="background-color:$info;"></sub><sub><mark style="background-color:$info;">.<mark style="background-color:$info;"></sub>

       <sub><mark style="background-color:$info;">Например, если в карточке клиента заполнено поле<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">**«Мобильный телефон»**<mark style="background-color:$info;"></sub><sub><mark style="background-color:$info;">, а в настройке робота в строке<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">**«Номер телефона»**<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">указана переменная<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">**\{{Рабочий телефон\}}**<mark style="background-color:$info;"></sub><sub><mark style="background-color:$info;">, робот<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">**не сможет найти номер**<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">— в результате сообщение<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">**не будет отправлено**<mark style="background-color:$info;"></sub><sub><mark style="background-color:$info;">.<mark style="background-color:$info;"></sub>\ <sub><mark style="background-color:$info;">Чтобы робот корректно подставлял номер из<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">**любого**<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">заполненного телефонного поля, рекомендуем в строке<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">**«Номер телефона»**<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">выбрать переменную<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">**\{{Телефон (текст)\}}**<mark style="background-color:$info;"></sub><sub><mark style="background-color:$info;">.<mark style="background-color:$info;"></sub>

       <sub><mark style="background-color:$info;">Указать её можно через меню<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">**«…» (три точки)**<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">напротив строки<mark style="background-color:$info;"></sub> <sub><mark style="background-color:$info;"> </sub><sub><mark style="background-color:$info;">**«Номер телефона»**<mark style="background-color:$info;"></sub><sub><mark style="background-color:$info;">.<mark style="background-color:$info;"></sub>
4. Введите текст **Сообщения.**
5. В поле **Публикация в чате открытой линии?** укажите каким образом отправленное роботом сообщение отобразится в чате Открытой линии. Доступны варианты: **Входящим сообщением в ОЛ, Без публикации в ОЛ** и **Исходящим в ОЛ.**

{% hint style="warning" %}
В настоящее время **Публикация в чате открытой линии** возможно только **Входящим сообщением!** Публикация **Исходящим в ОЛ** недоступна. Техотдел работает над добавлением такой возможности.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (942).png" alt=""><figcaption></figcaption></figure>

Остальные настройки можно оставить по умолчанию. Нажмите на кнопку «Сохранить».
