
# Домашнее задание к занятию 4 «Работа с roles»

## 1. Создайте в старой версии playbook файл requirements.yml и заполните его содержимым:

```
---
  - src: git@github.com:AlexeySetevoi/ansible-clickhouse.git
    scm: git
    version: "1.13"
    name: clickhouse 
```

![Задание 1](https://github.com/arccos2x-lwr/playbook/blob/main/img/1-01.png)

## 2. При помощи `ansible-galaxy` скачайте себе эту роль.

![Задание 2](https://github.com/arccos2x-lwr/playbook/blob/main/img/02-01.png)

## 3. Создайте новый каталог с ролью при помощи `ansible-galaxy role init vector-role`.

## 4. На основе tasks из старого playbook заполните новую role. Разнесите переменные между `vars` и `default`.

## 5. Перенести нужные шаблоны конфигов в `templates`.

## 6. Опишите в `README.md` обе роли и их параметры. Пример качественной документации ansible role по ссылке.

## 7. Повторите шаги 3–6 для LightHouse. Помните, что одна роль должна настраивать один продукт.

![Задание 7](https://github.com/arccos2x-lwr/playbook/blob/main/img/07-01.png)

## 8. Выложите все roles в репозитории. Проставьте теги, используя семантическую нумерацию. Добавьте roles в `requirements.yml` в playbook.

## 9. Переработайте playbook на использование roles. Не забудьте про зависимости LightHouse и возможности совмещения `roles` с `tasks`.

## 10. Выложите playbook в репозиторий.

## 11. В ответе дайте ссылки на оба репозитория с roles и одну ссылку на репозиторий с playbook.

[playbook](https://github.com/arccos2x-lwr/playbook)

[vector-role](https://github.com/arccos2x-lwr/vector-role)

[lighthouse-role](https://github.com/arccos2x-lwr/lighthouse-role)
