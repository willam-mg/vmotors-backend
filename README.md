
![Logo](https://laravel.com/img/logomark.min.svg)

## V MOTORS
This project is oriented to the administration of "work orders" through a type of CMMS information system of the VMTORS company.


## Features

- user management
- Create user authentication
- register customer
- Block system users
- Manage work order and vehicle
- Assign work order to a mechanic
- Manpower detail management.
- Material or spare parts detail management
- Generate vehicle entry report
- Generate vehicle departure report



## Requirements
- PHP 7 o 8
- Composer
- Apache 
- Mysql or Maria db
## Deployment

- To deploy this project run this command:

```bash
  composer install
```

- Config the file .env to seting the database:
- run this command
```bash
  php artisan migrate
```
- install passport to create personal access token
```bash
  php artisan passport:install
```
- run the project
```bash
  php artisan serve
```



## Documentation

[Laravel 8 documentation](https://laravel.com/docs/8.x/installation)

