# laravel install guide
Setting Up a Local Laravel Development Environment

## Prerequisites
- [PHP](https://www.php.net/manual/en/install.php)
- [Composer](https://getcomposer.org/download/)

## Install the Laravel Project
### Linux system
> From a terminal window, enter the following command to install laravel.
```sh
composer global require "laravel/installer"
export PATH=$PATH:$HOME/.composer/vendor/bin
```
## Test the laravel installation
```sh
laravel --version
```
You will get the below output if laravel is installed successfully. Maybe the laravel version may vary in your case.
```sh
Laravel Installer 4.2.9
```
## Create a new laravel project
> To start a Laravel project, run the following command.
```sh
laravel new myapp
```
This command will create a folder name `myapp` into the present directory.
## Run the laravel project
> To run a laravel project we need to run the below command into the project root from a terminal window.
```sh
php artisan serve
```
