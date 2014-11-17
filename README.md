Nginx config - Multilang Wordpress
==================================


Introduction
------------

You would to have translate system in **wordpress** but you doesn't want to use plugin for manage you content. You Can make few wordpress installation and manage good redirection directly on your web server ( here : **Nginx** )

Folder Structure
----------------

Base path :

``` 
/var/www/mydomain.com
```

Few usefull folder :

```
/var/www/mydomain.com/logs
/var/www/mydomain.com/www
/var/www/mydomain.com/backup
/var/www/mydomain.com/cron
```

on **www** folder you put your wordpress installation like this :

```
/var/www/mydomain.com/www/fr
/var/www/mydomain.com/www/en
/var/www/mydomain.com/www/in
```

Rewrite System 
--------------

when yo go to `http://mydomain.com/fr`, you are redirect on `/var/www/mydomain.com/www/fr` folder.


Credit
------

Yanis Ghidouche - Creative Common