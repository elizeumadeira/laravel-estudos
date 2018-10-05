# Estudos Laravel
#
## Instalar Laravel
* composer global require "laravel/installer"

## Criar o Projeto
* Laravel new Projeto1

## Atualizar a biblioteca Laravel
* composer update

## criar o arquivo .env
* copy .env.example .env

## criar a chave
* php artisan:key:generate

## Limpar o cache para aplicar as mudanças
* php artisan config:clear
* php artisan config:cache

## Criar a classe Migration
* php artisan make:migration create_tabela_migration --create=tabela1

## Rrodar o script do migrate (criar/atualizar as tabelas)
* php artisan migrate

## Criar o Model
* php artisan make:model Modelo1
* php artisan make:model Modelo1 -mc (criar controller e migration ao mesmo tempo)

## Inserindo menus (horizontal e vertical)
* composer require laravel/laravel-menus

## Atualizando tabela BD
* php artisan migrate:refresh