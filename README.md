# website-dynamics-for-hotel-managment-using-lumen-laravel
Installation

The Lumen framework has a few system requirements. Of course, all of these requirements are satisfied by the Laravel Homestead virtual machine.
server required:
#PHP >= 7.3
#OpenSSL PHP Extension
#PDO PHP Extension
#Mbstring PHP Extension

Install Lumen
Install Lumen by issuing the Composer create-project:
     composer create-project --prefer-dist laravel/lumen blog
     serving the app
     php -S localhost:8080-t public
 download visual studio code
 install wamp/xamp server
 install postman
 
update the web.php to route all the testimonials.
migrate all the testimonials to be created the table on the database.
php artisan make:migration news
php artisan make:migration vacancies
php artisan make:migration contacts
php artisan make:migration awards  
php artisan make:migration rooms
php artisan make:migration gallery 
at the last use      php artisan migrate
creat a fill for each the above testimonials for controller, service, model,request
 example for news newscontroller.php, newsrequest.php ,and news.php
 make for all the above testimonials to creat those files.
 to cheak what you insert/change on the code use the web.php route to get/put/post or delete attributes.
 example for award to post an image use localhost:8089/hms/apis/v1/Award on postman
                    to get it use http://localhost:8089/hms/apis/v1/Award
                    to delete use http://localhost:8089/hms/apis/v1//trash/{id}
 the created testimonials are news, vacancies,contacts,awards,rooms,gallery,newssubscription
 






