# README #
Vhost allows you to quickly create virtual hosts on Apache2 even if you don't know anything about Apache.

Requirements
------------

Symfony Installer needs to be installed.

```bash
$ sudo curl -LsS http://symfony.com/installer -o /usr/local/bin/symfony

$ sudo chmod a+x /usr/local/bin/symfony
```

Installation
------------

Clone this repository wherever you want
```bash
$ git clone https://github.com/Jbuchs/vhost.git
```
Enter the vhost directory
```bash
$ cd /vhost
```
Install vhost
```bash
$ sudo ./vhost install
```
And that's all folks !

Use
---

From now on, call the script from wherever you want in a terminal with :
```bash
$ vhost
```
Parameters
----------

-symfony :  Install directly a new ready to use Symfony 2 project

Other
-----

sudo ./vhost install :	To enable vhost from everywhere on your computer

sudo ./vhost update :    To get the last vhost's version

<b>/!\ installation and updates have to be done from the installation directory</b>

