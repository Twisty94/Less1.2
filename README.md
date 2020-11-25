Описание задания
1. Опишите, что происходит, при выполнении любой команды в консоли, например:
`$ ls -l`

2. Используя ключ 'o', выведите с помощью `ps` список всех процессов в таком формате:
`PID USER %CPU VSZ TT COMMAND`
пояснение: ID процесса, пользователь (real user), % загрузки CPU, размер виртуальной памяти, управляющий терминал, команда

прикрепите вывод к задаче, перенаправив вывод на `head`:

`$ ps ... ваши опции ... | head`

3. Создайте процесс sleep с помощью
`$ sleep infinity &`

- найдите его в списке процессов с помощью `ps`.
- отфильтруйте вывод `ps` чтобы получить строку только с этим процессом.
- убейте процесс, отправив ему сигнал '-9' программой `kill`.
- убедитесь, что процесса больше нет в списке выдачи `ps`.
