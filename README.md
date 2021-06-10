Домашняя работа номер 4 курса "Системы управления конфигурациями"

Состоит из следующих задач:
    Установка приложения

    1) MySQL
    1.1*) Выполнить установку MqSQL в виде роли, перед установкой DB, выполнить бекапирование (любое подходящее)

    2) WordPress

    3) FPM

    4) nginx
    4.1*) Перед установкой сделать бекап статического содержимого (www, htdocs). Также сделать бекапирование конфигурации (conf.d), размесить конфигурацию в каталоге $HOME/backups/nginx/$(date) (Например, /home/app_tech/backups/nginx/2021-06-20_14_20_24

    5*) Развернуть приложение в докере FTP-сервер, настроить проексировать через nginx

Заметки:
- Попытаться настроить yamllint, ansible-lint.
- Ознокомитсья с документацией molecule https://molecule.readthedocs.io/en/latest/installation.html
- Будет плюсом, если ДЗ будет сдана в виде Pull request в github/gitlab/bitbucket


В процессе подготовки и выполнения задания, были использованы следущие ресурсы:
    0) https://docs.google.com/document/d/1RWHQucwWsrvFM5k_kGhAka_h9lqvjVWP2Ctxz0RJo1w/edit#heading=h.30j0zll
    1) https://docs.ansible.com/ansible/2.9/index.html
    2) https://github.com/leucos/ansible-tuto
    3) https://www.nginx.com/blog/official-ansible-galaxy-nginx-roles-out-now/
    4) https://galaxy.ansible.com/nginxinc/nginx
    5) http://www.linuxsql.ru/content/izuchaem-ansible-playbook-urok-4
    6) https://stackoverflow.com/questions/26597926/install-mysql-with-ansible-on-ubuntu
    7) https://github.com/metabrainz
    8) https://github.com/hrendoh/ansible-wp-nginx-php-fpm 

В процессе поиска ответов на возникающие вопросы нашел 8) сделал флрк и поправил в сооответствии с ДЗ
yamlint взял из учебника 2) по ансибл 

Все роли выполняются в тестовом окружении vagrant. 

Выполнил Руслан Чирятьев.


