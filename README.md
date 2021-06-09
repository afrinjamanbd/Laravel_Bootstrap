# Laravel_Bootstrap
Application built on Laravel and Bootstrap.


## Features
- Todos CRUD.
- Form Validation.
- Flash Messages.
- Authentication.
- Email Verification.
- Password Reset.
- Eloquent One to Many and Many to One Relationship.
- Image Upload.


## Running this web application

- make sure you already have [xampp](https://www.apachefriends.org/index.html) installed.

- clone this repository.

- install [Composer](https://getcomposer.org/download) first, then run this command in your command-line (you should be inside your project directory). 
```bash
  composer install
```

- rename .env.example to .env and add your database and mail driver credentials ([mailtrap](https://mailtrap.io) is preferred).

- generate application key.

```bash
    php artisan key:generate
```

- create tables.

```bash
    php artisan migrate
```

- Link the public disk for image upload (this will create a symbolic link to storage/app/public directory).
```bash
    php artisan storage:link
```

- Start the development server.

```bash
    php artisan serve
```
