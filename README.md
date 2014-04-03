php-secure
==========

Shell scripts to check if your PHP application is secure.

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

Author
------

Prathik Raj

Feature Request/Bugs
--------------------

Add a comment or mail me.

License
-------

Free to use, copy, modify and distribute. GPL 2.
