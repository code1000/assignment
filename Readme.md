1 Get clone to the web server document root. 

2 Go to the "api" project and  open command prompt.

3 Intall php dependencies (composer install)

4 open the .env file and change database settings accordingly .

   Current Database name = customer_registration

                  Username          = root

                         Password     =jkllll      

5 create database with the name

6 migrate the data base – command (php artisan migrate)

7 Seed the database – php artisan db:seed

8 in the web folder , open config.js.change the url  if necessary 

9 You can access the project by following url

http://localhost/assignment 



If you create a vhost make sure to configure for CORS erros