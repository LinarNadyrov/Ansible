### Запускаем сценарий 
#### ansible-playbook site.yml -i hosts.yml

Содержание папки - **roles**
```yaml
├── docker
│   ├── handlers
│   │   └── main.yml
│   ├── tasks
│   │   └── main.yml
│   └── vars
│       └── main.yml
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
├── reboot
│   └── tasks
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
├── timezone
│   ├── defaults
│   │   └── main.yml
│   └── tasks
│       └── main.yml
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
└── zabbix_install
    ├── handlers
    │   └── main.yml
    └── tasks
        └── main.yml
```
