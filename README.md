# ClientConnectRouter
Сервер Маршутизатор для подключения клиента к удаленной машине. 
Ждет подключений от удаленных машин, которые ждут подключения, определяет их порт  и адресс и сохраняет в своей таблице.
Так же ждет подключений от клиентов с целью подключиться к ранее регистрировавшийся машины, он должен получить ее маршут
и отсоединится от сервера.
