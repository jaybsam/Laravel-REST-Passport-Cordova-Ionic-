## Laravel-REST-Passport-Cordova-Ionic-
Hybrid Mobile App

This project is a authenticates with FB login using laravel &amp; Ionic Cordova which is a Hybrid Web application.

### Getting Started
Follow the instructions below:

### Frontend Mobile
`Note:` Only run this command if ionic-cli is not installed in your system:

```bash
 npm install -g @ionic/cli
```

1. Run `npm install`
2. Run `ionic serve`
3. (optional) Run `ionic platform add android`
4. (optional) Run `ionic build` --generates testapk

Ionic Setup Reference: https://ionicframework.com/docs/cli


### Backend Server

1. Run `composer install`
2. Open Mysql & create a new DB
3. Configure `.env.example` file with the newly created `DB` and remove extension `.example`
4. Run command `php artisan migrate`
5. Run command `php artisan db:seed`
6. Run `php artisan passport:install`
7. Run `php artisan passport:keys`
8. Start/Serve the app with command `php artisan serve`

Laravel Passport Reference: https://laravel.com/docs/9.x/passport




