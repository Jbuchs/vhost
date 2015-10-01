# README #
Vhost allows you to quickly create virtual hosts on Apache2 even if you don't know anything about Apache.

Requirements
------------

Symfony Installer needs to be installed.
<b>$ sudo curl -LsS http://symfony.com/installer -o /usr/local/bin/symfony</b>
<b>$ sudo chmod a+x /usr/local/bin/symfony</b>

Installation
------------

Clone this repository wherever you want

<b>$ git clone https://github.com/Jbuchs/vhost.git</b>

Enter the vhost directory

<b>$ cd /vhost</b>

Install vhost

<b>$ sudo ./vhost install</b>

And that's all folks !

Use
---

From now on, call the script from wherever you want in a terminal with :

<b>$ vhost</b>

Parameters
----------

-symfony :  Install directly a new ready to use Symfony 2 project

Other
-----

sudo ./vhost install :	To enable vhost from everywhere on your computer

sudo ./vhost update :    To get the last vhost's version

<b>/!\ installation and updates have to be done from the installation directory</b>

