Атака грубой силы на telegram
Вступление
Приложение Telegram (Android) может быть защищено паролем. Этот пароль представляет собой 4-значный код.
Этот скрипт позволяет взломать этот пароль.
Режим работы
Код доступа сохраняется в хешированном виде в XML-файле (см. ниже). 
Метод хеширования - sha256. 
Хэш имеет двойную соль: одна и та же соль вводится до и после кода доступа. 
Часть пароля представляет собой строку UTF-8, состоящую из 4 цифр
