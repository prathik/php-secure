php-secure
==========

Shell scripts to check if your PHP application is secure.

Designed to find basic security pitfalls.

Contributors
-------------

Created by Prathik Rajendran M (@prathikraj)

Requriements
------------

Sqlite3

Installation
------------

Clone the project where the php application is present.

Configuration
-------------

Provide execute permission for the script `sudo chmod 0775 php-secure`.

Running
-------

Run the script `./php-secure -f <folder-name>`.

Enhancing
---------

###Loading exploits database

`sqlite3 php-secure.db`

Add functions that can be injected (example `unlink($_GET['u'])`) into injection_functions table.