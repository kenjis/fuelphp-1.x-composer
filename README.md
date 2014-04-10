# FuelPHP 1.x Composer Setup

## Description

FuelPHP 1.x without git submodules. All submodules are installed via Composer.

## How to use

Clone this repository.

~~~bash
$ git clone git@github.com:kenjis/fuelphp-1.x-composer ProjectName
$ cd ProjectName
~~~

Checkout a branch which you like.

~~~bash
$ git branch -a
$ git checkout 1.7-master-composer
~~~

Run composer install command.

~~~bash
$ php composer.phar self-update
$ php composer.phar install
~~~

If you want a clean repository.

~~~bash
$ rm -rf .git
$ git init
~~~

## Thanks to

* https://github.com/chatii/fuelphp_setup
