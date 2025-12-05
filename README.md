# Lara-do
Este é app bem simples, implementado para estudar o Laravel 12 com o Sanctum e Inertia.JS.

## Requisitos
-   PHP 8.3
-   Composer
-   Node 22
-   MySQL 8

## Instalação
Configure .env

Install PHP dependencies:

```sh
composer install
```

Install NPM dependencies:

```sh
npm install
```

Build assets:

```sh
npm run build
```

Generate application key:

```sh
php artisan key:generate
```

Run database migrations:

```sh
php artisan migrate
```

Aí agora é so rodar o comando:

```sh
composer run dev
```
PS: o comando acima roda tudo o que é necessário para o ambiente de desenvolvimento de uma vez só.
