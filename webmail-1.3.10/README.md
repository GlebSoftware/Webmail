Webmail 
=================


INTRODUCTION
------------
Webmail is a browser-based multilingual IMAP client with an
application-like user interface. It provides full functionality you expect
from an email client, including MIME support, address book, folder management,
message searching and spell checking. Webmail is written in PHP and
requires the MySQL, PostgreSQL or SQLite database. With its plugin API it is
easily extendable and the user interface is fully customizable using skins
which are pure XHTML and CSS 2.

The code is mainly written in PHP and is designed to run on a webserver.
It includes other open-source classes/libraries from [PEAR][pear],
an IMAP library derived from [IlohaMail][iloha] the [TinyMCE][tinymce] rich
text editor, [Googiespell][googiespell] library for spell checking or
the [WASHTML][washtml] sanitizer by Frederic Motte.

The current default skin 'Larry' was kindly created by FLINT / Büro für
Gestaltung, Berne, Switzerland.


INSTALLATION
------------
For detailed instructions on how to install Webmail on your server,
please refer to the INSTALL document in the same directory as this document.

If you're updating an older version of Webmail please follow the steps
described in the UPGRADING file.


[pear]:         http://pear.php.net
[iloha]:        http://sourceforge.net/projects/ilohamail/
[tinymce]:      http://www.tinymce.com/
[googiespell]:  http://orangoo.com/labs/GoogieSpell/
[washtml]:      http://www.ubixis.com/washtml/
[kmgerich]:     http://kmgerich.com/
[gpl]:          http://www.gnu.org/licenses/