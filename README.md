# Laravel 10 + Vue 3 + Vite example, simple app

## Requirements
```
Laravel Framework 10
```
<b>Note:</b>
<br />
We will use $ to describe the commands that will be used with regular user.

1- Run the following commands in sequence to deploy the project in a development
environment:

```
$ cp .env.example .env

$ composer install

$ npm install

$ npm run dev
```

2- Create and configure database in .env.

```
$ php artisan key:generate

$ php artisan migrate

$ php artisan serve
```

3- Next, you may navigate to you URL http://127.0.0.1:8000/