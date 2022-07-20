# Домашняя работа к занятию "08.03 Использование Yandex Cloud"

## Данный playbook выполняет три play:
- Clickhouse 
    - загрузку установочного пакета clickhouse
    - создание рабочего каталога
    - распаковку пакета
    - создание базы данных
- Vector
    - установку пакета Vector
    - создание конфигурационного файла для Vector
    - создание systemd unit
    - запуск сервиса
- Lighthouse и Nginx
    - установка пакетов epel и Nginx
    - создание config файла для Nginx
    - перезапуск Nginx
    - установка git и Lighthouse
    - создание config файла для Lighthouse
    - перезапуск Nginx

## Конфигурируемые парметры:
- в файле `prod.yml` задаются `IP-адреса` хостов.
- в файлах `vars.yml` можно указать версия пакета Clickhouse и Vector.
- в файле vector/vars.yml указываются параметры конфигурации сервиса Vector.

## Используемые теги:
- clickhouse
- vector
- nginx
- lighthouse
