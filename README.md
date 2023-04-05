# mariadb

ansible-playbook -i inventory plakbook.yml --extra-vars '{"ansible_become_pass":"passwd", "db_name":"dbName", "db_user":"root", "db_password":"passwd"}'