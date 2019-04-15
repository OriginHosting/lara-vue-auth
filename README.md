# lara-vue-auth
A repo for laravel vue authentication tutorial.

# How to run 
1. Clone the repo
2. Run 
 	`composer install`
3. Run 
	`npm install`

4. Set your database credentials in .env
5. Run 
	`php artisan serve`
	
Full details here: https://codeburst.io/api-authentication-in-laravel-vue-spa-using-jwt-auth-d8251b3632e0

Have to use modified beta of JWTAuth 
https://github.com/tymondesigns/jwt-auth/issues/1764

Have to see here for fixes for using the beta auth package. 
https://github.com/tymondesigns/jwt-auth/issues/1038

https://github.com/tymondesigns/jwt-auth/issues/1298
Final solution at bottom.
