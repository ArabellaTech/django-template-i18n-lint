Django Template i18n lint
=========================

A simple script to find non-i18n text in a Django template.

It can also automatically wrap the strings in `{% trans "" %}` tags, by running it with the `-r` command-line flag.
The translation will be written to a new file, `<filename>_translated.html`.

For more info see [Lint tool to find non-i18n strings in a django template](http://www.technomancy.org/python/django-template-i18n-lint/)

Code is copyright Rory McCann 2013, and dual licenced under the GNU GPL version3 (or at your option a later version), and the BSD licence. See the files LICENCE.GPLv3 and LICENCE.BSD for more information