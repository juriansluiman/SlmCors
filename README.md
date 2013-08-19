SlmMail
=======

[![Build Status](https://travis-ci.org/juriansluiman/SlmCors.png)](https://travis-ci.org/juriansluiman/SlmCors)
[![Latest Stable Version](https://poser.pugx.org/slm/cors/v/stable.png)](https://packagist.org/packages/slm/cors)

Created by Jurian Sluiman

Introduction
------------

SlmCors is a module that provides Cross-Origin Resource Sharing (CORS) inside Zend Framework 2 applications.

Requirements
------------

* PHP 5.3
* [Zend Framework 2](https://github.com/zendframework/zf2)

Installation
------------

Add "slm/cors" to your composer.json file and update your dependencies. Enable SlmCors in your
`application.config.php`.

If you do not have a composer.json file in the root of your project, copy the contents below and put that into a
file called `composer.json` and save it in the root of your project:

```
{
    "require": {
        "slm/cors": "@dev"
    }
}
```

Then execute the following commands in a CLI:

```
curl -s http://getcomposer.org/installer | php
php composer.phar install
```

Now you should have a `vendor` directory, including a `slm/cors`. In your bootstrap code, make sure
you include the `vendor/autoload.php` file to properly load the SlmCors module.

Usage
-------------

Once SlmCors is enabled, it provides by-default CORS headers in all requests and responses.
