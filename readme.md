Clone or download the repository.

run command
composer update

php artisan serve 


open postman
http://localhost:8000/api/auth/login

journey4tech@gmail.com
developer

http://localhost:8000/api/auth/login
http://localhost:8000/api/auth/logout
http://localhost:8000/api/auth/me
http://localhost:8000/api/auth/payload
http://localhost:8000/api/auth/refresh

Route List

POST     | api/auth/login   |      | App\Http\Controllers\AuthController@login   
POST     | api/auth/logout  |      | App\Http\Controllers\AuthController@logout  
POST     | api/auth/me      |      | App\Http\Controllers\AuthController@me      
POST     | api/auth/payload |      | App\Http\Controllers\AuthController@payload 
POST     | api/auth/refresh |      | App\Http\Controllers\AuthController@refresh 


Vist http://www.journey4tech.com