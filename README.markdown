Strftimedammit is a single Vim documentation file that lists strftime-like
formatting characters for a variety of languages.

It was born when I finally got sick of having to open a browser with the
Django docs to look up how to use its date formatting template filter.

![Screenshot](http://i.imgur.com/CIvqB.png)

Usage
-----

Install with [Pathogen](http://www.vim.org/scripts/script.php?script_id=2332).

Make sure you `:call pathogen#helptags()` after installing to make Vim notice
the new documentation file.

Now you can use `:help strftimedammit` to open the documentation.

There are also tags in place for each language, so you can do
`:help strftime-python` or `:help strftime-django` to go right to that
section.

Contributing
------------

Add your favorite language to the doc file, fork, and send a pull request.
