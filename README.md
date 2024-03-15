<!-- <p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[WebReinvent](https://webreinvent.com/)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Jump24](https://jump24.co.uk)**
- **[Redberry](https://redberry.international/laravel/)**
- **[Active Logic](https://activelogic.com)**
- **[byte5](https://byte5.de)**
- **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT). -->

# WD4307 WADT AS2 Assignment 2

## Table of Contents
1. [Part #1: Laravel Project Deployment Checklist]
- [Week 8](#week-8)
  - [Day 1: March 12, 2024](#day-1-march-12-2024)
  - [Day 2: March 15, 2024](#day-2-march-15-2024)
2. [Part #2: Git Enabled Laravel Project Checklist]
- [Week 8](#week-8)
  - [Day 1: March 15, 2024](#day-1-march-15-2024)

---
## Part #1: Laravel Project Deployment Checklist

## Week 8

### Day 1: March 12, 2024
- **Objective: WSL Installed and enabled.**
- *Comments:* To check WSL installed or not, I do it with the command, 'wsl --list'.
- *Comments:* To check if it's running in the background or not? Do it with the command, 'wsl --list --verbose'.
- *Comments:* If WSL hasn't been install yet, then do it with the command, 'wsl --install'.
- *Comments:* Once it has been installed, then you can download Ubuntu 22.04 at Microsoft Store.

---

- *Comments:* As mine has been downloaded during class, I just need to check it with the command, 'wsl --list --verbose' to see if its running or not.

---

- **Objective: WSL2 enabled and used.**
- *Comments:* For WSL2, we downloaded together in class called 'Docker Desktop'.

---
- **Objective: Windows Terminal installed.**
- *Comments:* For Windows User, the Windows Terminal has already been installed, and all you can do is just, search it on 'Search'.

---
- **Objective: Docker Desktop installed and running.**
- *Comments:* To run the Docker Desktop, go to settings, and go to 'Resources' and 'WSL Integration' to check both Ubuntu has been enabled by applying 'Apply & restart'.
- *Comments:* If already did, then can start the containers by clicking it at the 'action'.

---
- **Objective: Laravel installed in a folder named studentid-as2. E.g. 22ftt1234-as2**
- *Comments:* To have Laravel installed, first check that you're in Linux/home/username with the command, 'pwd'.
- *Comments:* To create a folder, command it with 'mkdir project-name' and with this, we created it with the name 'mkdir 22ftt1497-as2'.
- *Comments:* Then enter the project by the command, 'cd 22ftt1497-as2'.

---
- **Objective: Laravel website running locally in user browser.**
- *Comments:* After that, we did install it with [Installing Laravel][curl -s https://laravel.build/example-app | bash].
- *Comments:* On how to do it can be found on Laravel Documentation [Sail on Windows](https://laravel.com/docs/10.x#sail-on-windows).
- *Comments:* Wait for it to install, then command it with 'cd example-app && ./vendor/bin/sail up'.
- *Comments:* To check Laravel Website, type in 'localhost' on your FireFox or wherever it is, and then you'll find that there's the website.
- *Comments:* To alter the contents inside, just type in 'code .' to open the coding.

---

### Day 2: March 15, 2024

---
- **Objective: Laravel website’s .env file contains APP_NAME with student’s ID. E.g. 19ftt1234**
- *Comments:* How to open the .env file is through the command, 'code .'.
- *Comments:* From there, you can find the .env file and change the content acordingly according to being what being assigned.
- *Comments:* Find APP_NAME='Laravel' changed it to APP_NAME='22FTT1497' (school id).
- *Comments:* Making sure that APP_KEY has a valid value, and if it doesn't have value - we can generate it by:
- *Comments:* With the command, 'php artisan key:generate' - it will generate a random number.
- *Comments:* It should look like this 'APP_KEY=base64:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx' - as an example.

---
- **Objective: Laravel website landing page replaces default Laravel logo with student’s ID (e.g.19ftt1234) in h1 tag and white colour.**
- *Comments:* Inside the folder resources/views, there's the welcome.blade.php file and from there we can alter the logo.
- *Comments:* Find '<svg>' and commented that one to make '<h1 style="color: red;">19ftt1234</h1>'.
- *Comments:* After that save it, then you can see on the localhost to see if it has been made.

---
- **Objective: Composer installed and available on command line.**
- *Comments:* Open your command line, and then type in 'composer'.
- *Comments:* And if it has been installed properly, there should be an output that shows the version, usage and options.
- *Comments:* After confirming has composer, then we can create a new laravel projects with the command, 'composer create-project laravel/laravel my-project' - my-project can be changed to any name that you want.
- *Comments:* To verify installation path, we can do 'where composer' and 'which composer', then it'll display the path to the composer executable file - by confirming its installation and availability.

---
- **Objective: Install a Laravel 3rd party package called spatie/laravel-backup.**
- *Comments:* Finding your laravel project with the 'cd', command as usual.
- *Comments:* Then, install it with the command, 'composer require spatie/laravel-backup'.
- *Comments:* After that, once the installation has been done, open the 'composer.json' under the "require" section.
- *Comments:* Then configure the package depends on the packages, as usual run the necessary commands.

---
- **Objective: Customise the package spatie/laravel-backup.**
- *Comments:* First we publish the configuration file, with the command, 'php artisan vendor:publish --provider="Spatie\Backup\BackupServiceProvider"'.
- *Comments:* Then we modify the configuration file by opening the 'config/backup.php' file in your laravel project.
- *Comments:* To add prefix to compressed zip file name, need to customize the backup file name first using configuration file.
- *Comments:* Look for 'backup.destination.filename_prefix' configuration option in the 'config/backup.php' file and set it to "as2-".

- *Comments:* Examples:
'destination' => [
    'filename_prefix' => 'as2-',
    // Other destination configurations...
],

- *Comments:* After customizing it, then we can run the backup command to generate the backup with the modified settings with 'php artisan backup:run', command.
- *Comments:* To verify it's there, find the file in storage location, typically in 'storage/app/backup' directory.

---
- **Objective: Run on demand backup using laravel-backup’s php artisan command.**
- *Comments:* It's almost the same thing as the point up but this time it's verifying.
- *Comments:* First, we need it with the command, 'cd laravel-project'.
- *Comments:* Then we run the backup command, 'php artisan backup:run'.
- *Comments:* Verify that it's in the 'storage/app' folder. Then you can see that there's a new folder named 'backup' inside 'storage/app' directory containing the backup files.

---
- **Objective: Set spatie/laravel-backup to use password <studentid> to unlock zip file.**
- *Comments:* To do this, we need to configure password protection first in 'config/backup.php' file to ensure the password protection is enabled.

- *Comments:* Example:
'encrypt' => [
    'enabled' => true,
    'passwords' => [
        'password' => env('BACKUP_ENCRYPTION_PASSWORD', '22ftt1497'),
        // Other passwords...
    ],
],

- *Comments:* Then we run the backup command with, 'php artisan backup:run'.
- *Comments:* We unzip the backup file by, using the student's id as password.
- *Comments:* The comment goes, 'unzip backup-file.zip -P 19ftt1234'.
- *Comments:* Replace the 'backup-file.zip' with the name of the encrypted backup file.
- *Comments:* To verify extraction, we entered the password and the file is successfully extracted.

---
- **Objective: Laravel website uses database.**
- *Comments:* We need to check first whether .env file has the correct database configuration.
- *Comments:* It should include settings for DB_CONNECTION, DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME, and DB_PASSWORD.

- *Comments:* Example: depending on your own database.

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password

- *Comments:* And to verify MySQL server is running, can check it with the command, 'sudo service mysql status'.
- *Comments:* Then we connect to MySWL Database on command with the command, 'mysql -u your_database_username -p your_database_name'.
- *Comments:* To test it, we can create simple route to fetch some database.

- *Comments:* Example:
Route::get('/test-database', function () {
    $users = DB::table('users')->get();
    return $users;
});

- **Objective: Laravel website has authentication scaffolding enabled.**
- *Comments:* To install it, we need it with the command, 'composer require laravel/breeze --dev'.
- *Comments:* Then we setup the authentication with 'php artisan breeze:install', command.
- *Comments:* Before doing anything else, we migrate the database first with the command, 'php artisan migrate'.
- *Comments:* Continue starting the development server with, 'php artisan serve' command.
- *Comments:* We check it on the localhost to see if there's login and register.

---
## Part #2: Git Enabled Laravel Project Checklist

### Day 1: March 15, 2024

---
- **Objective: Laravel website repo is git enabled**
- *Comments:* 