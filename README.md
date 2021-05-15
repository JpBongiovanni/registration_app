# Registration application: 
<h3>Pull directly from Github and follow the readme directions to apply to your own django project. The Registration application utilizes bcrypt encryption to ensure password security and includes input validation for all registration or login information.</h3>

<hr>

<p>Register - Register your personal information into the SQL database.</p>
<img src="https://github.com/JpBongiovanni/registration_app/blob/main/movies/register.gif" width="530" height="350" />

<p>Log In - Once registered, you can log in to your application that you attached the registration app to.</p>
<img src="https://github.com/JpBongiovanni/registration_app/blob/main/movies/log_in.gif" width="530" height="350" />

<p>Validation - For security purposes, the registration app utilizes bcrypt encryption to keep you personal data safe, and validates all entries into the database, and log in form.</p>
<img src="https://github.com/JpBongiovanni/registration_app/blob/main/movies/validation.gif" width="530" height="350" />

<h3>Steps to integrate</h3>
<p>In order to integrate the registration application into your own project, follow these 4 easy steps:</p>

<p>1. Add registration_app to your settings.py file as shown below</p>
<img src="images/Screen Shot 2021-05-15 at 4.24.38 PM.jpg">
<p>2. In your urls.py file, at "path('', include('registration_app.urls'))," Your '' can be replaced with the path name of your choosing</p>
<img src="images/Screen Shot 2021-05-15 at 4.24.29 PM.jpg">
<p>3. In your views.py folder, change the return redirect of the register function, and the login function to the homepage of your website</p>
<img src="images/Screen Shot 2021-05-15 at 4.25.11 PM.jpg">
<p>4. Finally, in your terminal run "python manage.py makemigrations" and then "python manage.py migrate" to add the User database model to your own database</p>
