Podcasts
========

A simple command line ruby script for downloading podcasts.


Setup
-----

Clone repo

 - git clone git://github.com/kaleworsley/podcasts.git

Install gems

 - cd podcasts && gem install xml-simple && gem install psych

Create ~/.podcasts.yml

 - vim ~/.podcasts.yml


Example ~/.podcasts.yml file
----------------------------

    Railscasts:
      path: ~/podcasts/railscasts
      url: http://feeds.feedburner.com/railscasts
    The Changelog:
      path: ~/podcasts/thechangelog
      url: http://feeds.feedburner.com/thechangelog



License
-------

               DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                       Version 2, December 2004

    Copyright (C) 2012 Kale Worsley <kale@egressive.com>

    Everyone is permitted to copy and distribute verbatim or modified
    copies of this license document, and changing it is allowed as long
    as the name is changed.

               DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
      TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

     0. You just DO WHAT THE FUCK YOU WANT TO.
