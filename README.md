# Estudos Laravel
#Instalar Laravel
composer global require "laravel/installer"

#Criar o Projeto
Laravel new Projeto1

#Atualizar a biblioteca Laravel
composer update

#criar o arquivo .env
copy .env.example .env

#criar a chave
php artisan:key:generate

#Limpar o cache para aplicar as mudanças
php artisan config:clear
php artisan config:cache

#criar a classe Migration
php artisan make:migration create_tabela_migration --create=tabela1

#rodar o script do migrate (criar/atualizar as tabelas)
php artisan migrate

#criar o Model
php artisan make:model Modelo1
php artisan make:model Modelo1 -mc (criar controller e migration ao mesmo tempo)

#inserindo menus (horizontal e vertical)
composer require laravel/laravel-menus

#atualizando tabela BD
php artisan migrate:refresh
