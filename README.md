# mysite
Простейший чат, не приспособленный пока для небезопасных сетей.

Реализован с использованием django и tornado. Для запуска django используется uwsgi.
В качестве основного web-сервера - nginx.

comet-сервер реализован на tornado, для запуска достаточно `python mycomet.py`.

