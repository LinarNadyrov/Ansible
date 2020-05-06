### Запускаем сценарий 
#### ansible-playbook site.yml -i hosts.yml

Содержание папки - **roles**
- journald
- locale
- timezone
- docker
- software
- ssh
- zabbix_install
- zabbix_configure
- reboot

```yaml
├── journald
│   ├── tasks
│   │   └── main.yml
│   └── vars
│       └── main.yml
├── locale
│   ├── defaults
│   │   └── main.yml
│   ├── handlers
│   │   └── main.yml
│   ├── tasks
│   │   └── main.yml
│   └── templates
│       └── locale.j2
├── timezone
│   ├── defaults
│   │   └── main.yml
│   └── tasks
│       └── main.yml
├── docker
│   ├── handlers
│   │   └── main.yml
│   ├── tasks
│   │   └── main.yml
│   └── vars
│       └── main.yml
├── software
│   └── tasks
│       └── main.yml
├── ssh
│   ├── files
│   │   └── authorized_keys
│   ├── handlers
│   │   └── main.yml
│   ├── tasks
│   │   └── main.yml
│   ├── templates
│   │   └── sshd_config.j2
│   ├── vars
│   │   └── main.yml
│   └── vars copy
│       └── main.yml
├── zabbix_install
│   ├── handlers
│   │   └── main.yml
│   ├── tasks
│   │   └── main.yml
├── zabbix_configure
│   ├── files
│   │   ├── zabbix_container.conf
│   │   └── zabbix_proxmox.conf
│   ├── handlers
│   │   └── main.yml
│   ├── tasks
│   │   └── main.yml
│   ├── templates
│   │   └── zabbix_agentd.j2
│   └── vars
│       └── main.yml
├── reboot
    └── tasks
        └── main.yml
```
