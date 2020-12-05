# ansible-role-install-atop

Общая роль для установки atop на хосты

Переменные:
```yaml
---
atop_packages:
  - atop
atop_config_path: "/etc/default/atop"
# Интервал через который делается снимок нагрузки сервера, в секундах.
atop_log_interval: 300
# Путь до логов atop.
atop_log_path: "/var/log/atop"
# хранить бэкапы за 10 дней.
atop_log_generations: 10
```
