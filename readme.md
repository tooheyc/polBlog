This is a generic version of a blog project written for a political candidate.

It's designed to be used by candidates to post on issues and collect contributions. Note that it is not fully functional. The contact page does not send emails and the donate page only uses a PayPal test account.

To install, edit the .env file to set your database information, then use normal composer commands. Finally, seed your database:

php artisan db:seed

The default username and password for the admin are:

jo@jo.com
password

You should change them for your install!

