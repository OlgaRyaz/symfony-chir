##Установка:
###Перейти в папку проекта:
```sh
cd ~/vagrant-project/
```
###Клонировать репозиторий:
```sh
git clone https://github.com/InnerFlameFact/symfony-chir.git
```
###Прописать hosts: 
 - Для windows: "windows/system32/drivers/etc/hosts, в нем вставить строчку:
  - 192.168.56.101 chir.dev www.chir.dev.
 
###Запустить vagrant:
Вся конфигурация находится: /puphpet/config.yaml.
```sh
vagrant up
```
###Подключится по ssh к vagrant (phpStorm/PUTTy):
login: vagrant, password: vagrant
###Перейти в проект (vagrant@192.168.56.101):
```sh
cd /vagrant/chir
```
###Запустить composer:
```sh
composer install
```
