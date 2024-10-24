### Задание 1

- Создать рабочий каталог pr1 (для работы в отладчике Kdbg в названии каталогов не должно быть кириллицы), скопировать в рабочий каталог программу task1.c, получить исполняемый файл task1-exe-c согласно инструкции в программе, запустить его в отладчике (kdbg task1-exe-c), отобразить значения переменных в окне локальных переменных (Вид/Locals или Вид/Watched expressions), выполнить программу пошагово, объяснить ее работу.
- Скопировать программу task1.S и файл my-macro в рабочий каталог. Пользуясь конспектом лекций и комментариями в программе изучить алгоритм и работу команд.
- Изучить команды ассемблирования as и редактирования связей ld из файла task1.S, добиться отсутствия синтаксических ошибок, получить файл листинга task1.lst. Для редактирования и компиляции рекомендуется использовать emacs. 
Образец файла task1.lst
- Внимательно ознакомиться со всеми деталями файла листинга, при необходимости записать пояснения инструктора.
- Понять и записать структуру и функции макроопределения и макровызова Finish.
- Выполнить команду ld из файла task1.S, добиться отсутствия сообщений об ошибках.
- Запустить отладчик kdbg, научиться управлять ходом выполнения программы, устанавливать контрольные точки, активировать окно Registers (меню Вид/Registers), просматривать значения переменных в окне Watched expressions (меню Вид/Watched expressions) или Locals (меню Вид/Locals). 

Внимание! Файлы названные с цифры могут не корректно обрабатываться отладчиком kdbg.

Зачет: самостоятельно получить выполняемый файл (с другим именем), запустить его под управлением отладчика, создать окна отображения регистров и переменных программы, выполнить программу в шаговом режиме, правильно поясняя изменения регистров и переменных. Объяснить работу макрокоманды Finish.