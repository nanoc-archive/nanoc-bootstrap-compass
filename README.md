nanoc+Compass bootstrap project
===============================

This directory contains a small nanoc project that uses Compass. It is based on a brand new nanoc site generated using `nanoc3 create_site`.

Places of interest:

* `config.rb` which contains the Compass configuration
* `content/style` which contains the Sass stylesheets (and a partial)
* `Rules` which contains the rules for processing the Sass stylesheets

How To Use
----------

Before you do anything, make sure that you have Compass installed. Issue `gem install compass` if you haven't already or if you're unsure.

To compile the site, simply use `nanoc3 co`.

You may want to edit the Compass configuration (`config.rb`) to suit your needs.
