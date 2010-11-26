$Id$

Overview
--------
nocase is a simple module that allows for case-insensitive Drupal passwords. It
accomplishes this by converting the password to lower case during user
registration, password changes and during authentication via login forms. In
other words, this module stores the password in lower case in the database 
itself which is effectively an irreversible change.

It should also be noted that preexisting users with passwords not all in lower
case will not be able to log in once this module has been installed. They will
need to reset their passwords in order to do so. Similarly, once this module has
been installed, uninstalling it will lead to users using mixed-case passwords
being locked out.

Author(s)
---------
Karthik Kumar / Zen / |gatsby| : http://drupal.org/user/21209

Links
-----
Project page: http://drupal.org/project/nocase
