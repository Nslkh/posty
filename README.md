

# Laravel base web application for writing comments
## Used technologies
- PHP
- Laravel
- MySQL
- mailtrap.io
- TailwindCSS

##Hot to run
1. ```git clone https://github.com/Nslkh/posty```
2. Enter you credentials in .env file
    - Database info
    ```
   ...
   DB_CONNECTION=mysql
  DB_HOST=127.0.0.1
  DB_PORT=3306
  DB_DATABASE=posty
  DB_USERNAME=root
  DB_PASSWORD=
   ...
    ```
    - Mailtrap info
    ```
   ...
    MAIL_MAILER=smtp
    MAIL_HOST=smtp.mailtrap.io
    MAIL_PORT=2525
    MAIL_USERNAME=550653a265a942
    MAIL_PASSWORD=bc5e8e2eef3fdb
    MAIL_ENCRYPTION=null
    MAIL_FROM_ADDRESS=olluzran@gmail.com
    MAIL_FROM_NAME="${APP_NAME}"
   ...
    ```

## What's made
- Registration
- Authorization/Authentication
- View posts
  View user's posts
- Post component
- Liking/Unliking/Deleting posts
- Send an email when post is liked

## Screenshots

###Homepage
![](https://hosty.xxx/i/4e205d8613f77169943cfe9e24f3df25f86fed58.jpg)

###Login
![](https://hosty.xxx/i/d32824880531a1a8ff536813bb54c4fd55936381.jpg)

###Registration
![](https://hosty.xxx/i/7a9f73111b23789277c7bc5845bf8a5f79bf2cbd.jpg)

###Posts without authorization
![](https://hosty.xxx/i/25fea40b129c1340d01bb71ac202a59c175971ac.jpg)

###Posts after authorization
![](https://hosty.xxx/i/c7ef552df2dfe0e1f1debf3207f1de83e5aab6b6.jpg)

###Added new post
![](https://hosty.xxx/i/034b138926f54ce10fb9947dea269072a08b4de7.jpg)

###User posts
![](https://hosty.xxx/i/1b56f87d12e5ecf1c88768bcd409ea66db92fc2b.jpg)

###Sent email
![](https://hosty.xxx/i/6ac9174b3e27949bfd44c2dc73c4a23e55d0ea74.jpg)


<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
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

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[Curotec](https://www.curotec.com/)**
- **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
