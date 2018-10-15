# Project-Assignment
Laravel Project with passport API

# Project Assignment


#Step 1: Get the code - Clone the repository

https://gitlab.com/aravinth.sakhi/sabay-assignment.git


#Step 2: Use Composer to install dependencies

	composer install 

	
#Step 3: Create database

	Need to create database and copy .env.example file and re name it as .env and change
	Default database connection name also corresponding data too.
	
	php artisan key:generate 
	
#Step 4: Install And to initial populate database use this.

	php artisan migrate
	
	
	php artisan db:seed

#Step 5: Authentication via API with Laravel Passport :

	php artisan passport:install
	
	
	php artisan route:list
	
	
	API URL's :	{URL}
	
	           Header : {
	                        Accept = application/json
	                        Authorization = Bearer .$token
	                   }  
	            
	            POST: http://127.0.0.1:8000/api/register
	            
	            POST: {URL}/api/login
	            
	            POST: {URL}/api/userList
	            
	            POST: {URL}/api/sendOtp
	            
	            POST: {URL}/api/verifyOtp
	            
	
Back office Url (Local Environment) :  php artisan serve
	
	Login URL :	 http://127.0.0.1:8000/login
	
	            
	            
PHP Laravel Test Driven Development( Unit Testing ) have to run :

	vendor/bin/phpunit
	
	
------------------------------*********---------------------------------------
