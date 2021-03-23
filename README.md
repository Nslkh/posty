

# Laravel base web application for writing comments
## Used technologies
- PHP
- Laravel
- MySQL
- mailtrap.io
- TailwindCSS


##How to run
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
    MAIL_ENCRYPTION=tls
    MAIL_FROM_ADDRESS=olluzran@posty.com
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


