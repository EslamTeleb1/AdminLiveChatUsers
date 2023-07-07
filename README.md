

#### To run this project make sure you ran these commands
<code>composer install</code><br><br>
<code>copy .env.example .env</code><br><br>
<code>php artisan key:generate</code><br><br>
<code>php artisan migrate</code><br><br>
<code>php artisan serve --port=3000</code><br><br>
<code>php artisan storage:link</code><br><br>
now you can visit localhost:3000 and see the project

To generate users, admin and messages, run this command <br>
<code>php artisan db:seed</code>
the password of the whole generated users is <code>password</code>
cluding files (Updated 09/04/2021)
