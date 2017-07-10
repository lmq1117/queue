http://laravelacademy.org/post/2410.html
php artisan tinker
Mail::send('emails.test',['testVar'=>'lmq first email use laravel'],function($message){$message->to('lmq1117@qq.com')->subject('ceshiyoujian');});