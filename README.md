# Laravel (tested on v5.6)

This repo contains files usefull for everyone who does web development with Laravel.

The folder Change Password contains the Controller, View, and the Routes to change the password of a user after login.
 * __app.blade.php__: layout; Move this to _ressources/views/layouts_
 * __changePassword.blade.php__: form to change password; Move this to _ressources/views/auth_
 * __ChangePasswordController.php__: Controller with methods; Move this to _app/Http/Controller/Auth_
 * __web.php__: Contains the Routes of the changePassword View; copy lines inside your _routes/web.php_
