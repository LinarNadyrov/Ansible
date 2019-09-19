# Ansible
Config files for configuration system management
---
**folder - install_config_zabbix**
- Установка zabbix agent на ОС Ubuntu 14/16/18

- Настройка zabbix agent 
---
**file - first_setting.yml**
- Первоначальная настройка системы
---
**folder - Auto_Deploy**
- Auto Deploy in GlassFish Server Open Source Edition version 4.1.1
    - Блокировка пользователей
    - Tаймаут
    - Бэкапы lxc контейнеров в Proxmox 
    - Разблокировка postgres-пользователя
    - Релиз на GlassFish Server
    - Релиз на JBoss by Red Hat (guvnor) 
    - Блокировка postgres-пользователя
    - Разблокировка пользователей
---
**folder - UpdateLicensePentaho**
- Update the license on the Server Pentaho
    - Verify and rename the license file for the Pentaho server version 7.0.0
    - Copy file lisense to localhost/Server Pentaho
---
**file - UnfoldingProdShard.yml**
- восставливает контейнеры с нужным номером (номер указываем мы) из нужного нам бэкапа (название бэкапа указываем мы)
- параметризует создание Linux Bridge на Proxmox (версия )
- параметризует создание внутренних ip адресов для контейнеров 
- параметризует название контейнеров
- настраивает - /etc/host для контейнеров
---
