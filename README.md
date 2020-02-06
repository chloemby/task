Форма регистрации пользователей

Инструкция:

Для работы на вашем компьютере должен быть установлен Docker. Также, для клонирования проекта на свой компьютер понадобится git.

1. С помощью консоли перейдите в директорию, где проект должен храниться.
2. Установите проект командой: git clone 
3. В консоли перейдите в папку проекта.
4. Далее с помощью Docker будет развернуто работее окружение приложения. Введите команду: docker-compose up -d
5. Дождитесь окончания установки всех необходимых сервисов(это может занять какое-то время).
6. Восстановите базу данных из файла dump.sql(mysql -u root -p root < dump.sql).
7. Далее приложение будет доступно в браузере по адресу: http://localhost:81/ 


Для проекта были использованы технологии и языки программирования: JavaScript(jQuery), PHP(7.3.2), HTML, CSS, MySQL.
В основе проекта лежит паттерн MVC. 

