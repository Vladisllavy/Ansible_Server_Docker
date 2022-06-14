# Ansible_Server_Docker

Сборка всех images

ansible-playbook -i inventory all.yml --tags "build"

Настройка серверов

ansible-playbook -i inventory all.yml --tags "preconfig"

Выкладка сервисов

ansible-playbook -i inventory all.yml --tags "deploy"
