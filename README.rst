=============================
Site styles for rosslaird.com
=============================

This repository is provided primarily for my students, but is open to anyone
who wishes to view the styles (CSS) that I use at rosslaird.com_. I have also
included various Javascript files, images, and site-specific files I use to
deploy my site using Mezzanine_.

If you are building a site with Mezzanine_, you should be aware that this
repository represents a theme application and should live as an application
inside your Mezzanine project. (Please consult the Mezzanine docs_ for more
information.) You should also be aware that the CSS file included in this
repository is designed to work with the templates provided by Mezzzanine and
the styles provided by the Twitter Bootstrap_ framework. (The basic Bootstrap
theme can be modified using Bootswatch_.)

Web design is a rapidly-evolving and highly complex area. If you are one of my
students, and you wish to experiment with the CSS styles or Javascripts
included in this repository, please do so. But please do not simply copy and
paste snippets of code into a live website (such as your blog). That would be
unwise, and would probably have unintended (and bad) consequences. Instead,
use these files on your local machine to experiment, play, learn, break,
rebuild, and explore. And, if you have trouble, ask me in class.

What's Here, Exactly?
----------------------

The `README.rst` files is what you are reading now.

The `__init__.py` and `__init__.pyc` files are for Django_. You can ignore these files.

The `static` directory includes several subdirectories: `css`, `img`, `js`,
`media`, and `prettify`. These directories contain most of the files that will
be of interest to my students: a style sheet, some image files (used with
Mezzanine), and various Javascripts. The `prettify` directory contains scripts
for rendering code snippets in web pages. The `media` directory contains a few
images used on the rosslaird.com_ site.

The `templates` directory contains files used with Mezzanine. If you are
building a site with Mezzanine, you can adapt these files to your own needs.
If not, you can ignore these files. They won't be of any use outside the
Mezzanine framework.

How to use these files?
------------------------

View them online, download them, clone the repository: it's up to you. If you want to clone the repository (which, overall, is the best way to use these files), first make sure you have Git installed, then run this command from a command prompt:

`git clone git://github.com/rosslaird/ibis.git`

This will clone the repository into a subdirectory called `ibis` beneath whatever directory you called the command from. You will have all of the files, and you can play with them as you like.

.. _rosslaird.com: http://rosslaird.com
.. _Mezzanine: http://mezzanine.jupo.org
.. _rosslaird.com: http://rosslaird.com
.. _docs: http://mezzanine.jupo.org/docs/frequently-asked-questions.html#how-do-i-create-install-a-theme
.. _Bootstrap: http://twitter.github.com/bootstrap/
.. _Bootswatch: http://bootswatch.com/
.. _Django: https://www.djangoproject.com/
