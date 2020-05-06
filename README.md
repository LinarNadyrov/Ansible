# Ansible
Config files for configuration system management
---
**folder - install_config_zabbix**
- Установка zabbix agent на ОС Ubuntu 14/16/18
- Установка zabbix agent на Proxmox 6
- Настройка zabbix agent 
---
**file - first_setting_for_Srv.yml**
- Первоначальная настройка системы
---
**file - install_and_configuration_Proxmox.yml**
- Установка Proxmox на Debian
- Первоначальная настройка Proxmox
----
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
- параметризует создание Linux Bridge на Proxmox (версия 5.3)
- параметризует создание внутренних ip адресов для контейнеров 
- параметризует название контейнеров
- настраивает - /etc/host для контейнеров
---
**file - install_docker.yml**
 - Установка docker на ОС Ubuntu 
----
**file - Programs_for_work.yml**
 - Установка необходимого ПО для работы на ОС Ubuntu 
----
**folder - ansible-role**
 - Установка необходимого ПО с помощью ролей
----

