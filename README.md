# README #
Vhost allows you to create quickly virtual hosts on Apache2 even if you don't know anything about Apache.

Installation
------------

Clone this repository wherever you want

<b>$ git clone https://github.com/Jbuchs/vhost.git</b>

Enter the vhost directory

<b>$ cd /vhost</b>

Start the script in <i>/usr/bin</i>

<b>$ sudo ./vhost install</b>

And that's all folks !

From now on, call the script from wherever you want in a terminal with :

<b>$ sudo vhost</b>

Parameters
----------

-symfony :  Provide an access to the /web directory when calling the url

-chmod :    Chmod directly the created directory <i>/var/www/thisDirectory</i>

update :    To get the last Vhost's version
