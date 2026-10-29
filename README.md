# xcom_dev
## Тестовый каталог для обновлений прошивки. 
### Список файлов:
- README.md - этот файл
- server.dat - файл для проверки соединения
- servers_list.cfg - список серверов с рабочими прошивками
- servers_list_dev.cfg - список серверов с тестовыми прошивками
- fw.1.0.1.dev.bin - прошивка 1.0.1.dev - не нужна и не используется
- fw.1.0.1.dev.upd - файл конфигурации обновления для прошивки 1.0.1.dev
- fw.1.0.2.dev.bin - прошивка 1.0.2.dev с отключенным SIP!

### Тестовая прошивка fw.1.0.2.dev.bin с отключенным SIP!
//Только для отладки!!!<br>
#define DEBUG_MODE_NOT_CREATE_SIP_SERVICE //xcom_wifi.c<br>
#define DEBUG_MODE_CONNECT_TO_XCOMM       //xcom_wifi.c<br>

### Путь для просмотра файлов средствами GitHub:
https://github.com/GushchinDmitry/xcom_dev/blob/main/[файл]
### Путь для прямого доступа к файлам извне:
https://raw.githubusercontent.com/GushchinDmitry/xcom_dev/refs/heads/main/[файл]
## Изменения
### 29.06.26
- никаких
### 16.10.26
- приведение в порядок [сервера] для обновления прошивки...
### 17.10.26
- добавлены файлы конфигурации
- файл servers_dev_list.cfg [везде] переименован в servers_list_dev.cfg
### 23.10.26
- выложена тестовая прошивка fw.1.0.2.dev.bin с отключенным SIP!
### 29.10.26
- добавлен файл server.dat для проверки соединения [...]
