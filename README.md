# Tестовое задание: 
подготовить ansible-playbook с установкой nginx, mysql, php. Чтоб по запуску одной команды поднимался веб-сервер, где выводится результат команды phpinfo(). Результат предоставить в виде ссылки на github/gitlab репозиторий.

# Выполнение:
Т.к. в задании не было конкретики, то написала плейбук для установки на сервер Ubuntu. Для простоты чтения не стала разделять на роли и многочисленные папки. При необходимости можно написать плейбук для установки LEMP стэка на различные дистрибутивы, уже выделяя роли, переменные и прочее в разные папки.
Для проверки правильности кода подняла сервер с помощью Vagrant.
После запуска по адресу сервера получаем данные:
!(phpinfo.png)
