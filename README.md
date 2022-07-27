Role Name
=========

Install Lighthouse

Requirements
------------

Должен быть установлен NGINX

Role Variables
--------------

Variables| default |Комментарии
---------|-------- |--------
lighthouse_dir| /home/lighthouse| домашняя дирректория
lighthouse_access_log_name|lighthouse_access| имя лог файла по пути /var/log/nginx/
lighthouse_git|https://github.com/VKCOM/lighthouse.git|репозитории от куда качается lighthouse

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - lighthouse

License
-------

MIT
