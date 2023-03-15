<h1>Laravel Chart using <b>larapex charts Library</b></h1>

## About

"php": "^7.4|^8.0"<br>
"laravel": "9"<br>

## Steps

1- Install Laravel<br><br>
&nbsp;&nbsp;composer create-project laravel/laravel example-app<br><br>
2- Create Firebase Project and App<br><br>
&nbsp;&nbsp;Firebase Console => https://console.firebase.google.com/<br><br>
&nbsp;&nbsp;create web app on that project as like i added bellow screenshot:<br><br>
https://www.itsolutionstuff.com/upload/laravel-firebase-push-notification-2.png?ezimgfmt=rs:836x376/rscb5/ngcb5/notWebP<br><br>
&nbsp;&nbsp;After created successfully created app we will go to setting page and get server api key as like bellow screen shot:<br><br>
https://www.itsolutionstuff.com/upload/laravel-firebase-push-notification-4.png?ezimgfmt=rs:836x414/rscb5/ng:webp/ngcb5<br><br>
3- You can copy that key and add on .env file as bellow:<br><br>
&nbsp;&nbsp;FCM_SERVER_KEY=XXXXX<br><br>
4- Create Route in route/web.php file<br><br>
5- Create Controller<br><br>
6- Create View<br><br>
7- Run Laravel App:<br><br>
&nbsp;&nbsp;php artisan serve<br><br>
8- Now, Go to your web browser, type the given URL and view the app output:<br><br>
