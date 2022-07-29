# Домашняя работа к занятию "08.04 Работа с Roles"

Данный playbook выполняет установку следующих пакетов: Clickhouse, Vector и Lighthouse с помощью ansible-role.Установка производится на хосты, приведенные в `inventory/prod.yml`. 

## Конфигурируемые парметры:
- в файле `prod.yml` задаются `IP-адреса` хостов.
- в файле `requimenets.yml` указываются версии ansible-role для установки вышеприведенных пакетов.

## Используемые теги:
- clickhouse
- vector
- nginx
- lighthouse

## Примечание:
Для установки ролей выполните в терминале следующую команду: `ansible-galaxy install -r requirements.yml -p roles` 