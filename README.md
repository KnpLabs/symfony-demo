Symfony Extended Demo Application
========================

The "Symfony Extended Demo Application" is a reference application based on ["Symfony Demo Application"](https://github.com/symfony/symfony-demo) 
created to show examples of Knp libraries and bundles.

Requirements
------------

  * PHP 5.5.9 or higher;
  * PDO-SQLite PHP extension enabled;
  * and the [usual Symfony application requirements](https://symfony.com/doc/current/reference/requirements.html).

If unsure about meeting these requirements, download the demo application and
browse the `http://localhost:8000/config.php` script to get more detailed
information.

Installation
------------

```bash
git clone https://github.com/KnpLabs/symfony-extended-demo
cd symfony-extended-demo
composer install
```

Usage
-----

There is no need to configure a virtual host in your web server to access the application.
Just use the built-in web server:

```bash
$ cd symfony-extended-demo/
$ php bin/console server:run
```

This command will start a web server for the Symfony application. Now you can
access the application in your browser at <http://localhost:8000>. You can
stop the built-in web server by pressing `Ctrl + C` while you're in the
terminal.

> **NOTE**
>
> If you want to use a fully-featured web server (like Nginx or Apache) to run
> Symfony Extended Demo application, configure it to point at the `web/` directory of the project.
> For more details, see:
> https://symfony.com/doc/current/cookbook/configuration/web_server_configuration.html
