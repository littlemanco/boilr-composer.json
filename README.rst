====================
boilr-composerjson
====================

Project Outline
----------------

Project Goals
'''''''''''''

Make it easy to generate composer.json files with all the fields I like filled out

Similar Work
''''''''''''

composer init


Justification
'''''''''''''

I want to be more specific and complete then composer init


Summary
'''''''

============= ==============
License       Language
------------- --------------
MIT           en-AU [lang]_
============= ==============

Installation
-------------

.. Code:: bash

  $ boilr template download littlemanco/boilr-composer.json composerjson
  
Updates
-------

I update these templates regularly. If you need to fetch the newer version, try this:

.. Code:: bash

  $ boilr template download littlemanco/boilr-composer.json composerjson -f 

Usage
-----

Swap `foo` and `bar` for your own values.

.. Code:: bash

  $ mkdir foo
  $ cd foo
  $ git init
  $ git remote set-url origin git@github.com:foo/bar.git
  $ boilr template use boilr-composerjson .
  $ git add .
  $ git commit -m "Initial Commit"
  $ git push

Thanks
------

- The team behind boilr (https://github.com/tmrts/boilr)

Contributing
------------

Contributions are always welcome! Nothing is to small, and the best place to start is to open an issue.

References
-----------

.. [lang] Lingoes.net,. (2015). Language Code Table. Retrieved 4 June 2015, from http://www.lingoes.net/en/translator/langcode.htm
