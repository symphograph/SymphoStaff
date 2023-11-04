# Команды терминала
### git pull
```bash
# Обновить SPA сайта
cd && cd sakh-orch.ru/public && git pull
```
```bash
# Обновить API сайта
cd && cd api.sakh-orch.ru && git pull
```
```bash
# Обновить SPA CRM
cd && cd staff.sakh-orch.ru/public && git pull
```
```bash
# Обновить API CRM
cd && cd api.staff.sakh-orch.ru && git pull
```
---
### Работа с сервером
```bash
# Проверка конфигурации nginx
nginx -t
```
```bash
# Перезапуск nginx
systemctl restart nginx
```
```bash
# Проверка службы fpm 8.2
systemctl status php8.2-fpm
```
```bash
# Перезапуск fpm 8.2 commands
systemctl restart php8.2-fpm
```
```bash
tree /a /f > структура.txt
```
