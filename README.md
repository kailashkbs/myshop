
# ShoppingPoint shop system

:star: Star us on GitHub — it helps!


## Table of content

- [Requirements](#requirements)
- [Installation](#installation)
- [Frontend](#frontend)
- [Backend](#backend)
- [Customize](#customize)
- [License](#license)
- [Links](#links)

## Requirements

The ShoppingPoint shop distribution requires:
- Linus/Unix or WAMP/XAMP environment
- PHP >= 7.0.4
- MySQL >= 5.1
- Web server (Apache, Nginx or integrated PHP web server for testing)

If required PHP extensions are missing, `composer` will tell you about the missing
dependencies.

## Installation

To install the ShoppingPoint shop application, you need [composer](https://getcomposer.org).
On the CLI, execute this command for a complete installation including a working setup:

`composer create-project ShoppingPoint/ShoppingPoint myshop`

You will be asked for the parameters of your database and mail server as well as an
e-mail and password used for creating the administration account.

In a local environment, you can use the integrated PHP web server to test your new ShoppingPoint
installation. Simply execute the following command to start the web server:

```
cd myshop
php artisan serve
```

## Frontend

After the installation, you can test the ShoppingPoint shop frontend by calling the URL of your
VHost in your browser. If you use the integrated PHP web server, you should browse
this URL: [http://127.0.0.1:8000](http://127.0.0.1:8000)

[![ShoppingPoint frontend](http://shopping-point.kindlebit.com/images/shopping-point.png)](http://shopping-point.kindlebit.com)

## Backend

The ShoppingPoint administration interface will be available at `/admin` in your VHost. When using
the integrated PHP web server, call this URL: [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

[![ShoppingPoint admin backend](https://aimeos.org/fileadmin/aimeos.org/images/aimeos-backend.png)](http://admin.demo.aimeos.org/)

# myshop
