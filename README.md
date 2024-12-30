# xui-install-configure-script
Скрипт для установки 3x-ui панели из официального репозитория bash скриптом.
https://github.com/MHSanaei/3x-ui
Автоматичсекая настройка сертификатов и базовая настрйока сервера.

Требования перед установкой:
1. VPS сервер в Европе с ОС Ubuntu 22.04 или новее.
2. Наличие DNS A записи для ip адреса VSP сервера.

Выполнить команду на VPS сервере:
```
/bin/bash <(curl -Ls https://raw.githubusercontent.com/maou0/xui-install-configure-script/refs/heads/main/xui-install-configure.sh)
```
