# otus-kernel-update
Обновление ядра ОС и создание образа для vagrant

Ссылка на готовый образ в Vagrantcloud

https://app.vagrantup.com/aastlt/boxes/centos7-new-cernel

Ядро обновлено из официального репозитория elrepo. Скрипт расположен в packer/scripts/stage-1-kernel-update.sh

Для проверки работы VirtualBox Shared Folders папка packer монтируется в /vagrant

Для проверки запустить

vagrant up
vagrant ssh
