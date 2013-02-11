plone-dev-helpers
=================
A collection of simple shortcut/helper scripts to keep on the src folder of your Plone dev instance that save you those valuable extra minutes. They allow you to quickly create new products (using paster), add dependencies, update version numbers etc ...

Script with moderation
======================
These scripts are very specific for my needs but they are also pretty simple so you can easily adjust them. I've put them here just as a way to organize my stuff and in case they might help somebody. 
They assume a lot of defaults (i.e the XML files do NOT get parsed. just edited as text by finding the place to add the code and adding the necessary lines.) Check the code before you run to see if it works for you.

Documentation
=============
(Very incomplete. just a few notes)

edit shabang if needed:
default: #!/usr/bin/python

create
------
Creates a Plone product including SVN repository. Uses Paster templates to create the product.

depend
------
Adds a dependency to a product into another product.

update
------
Increases the version number of the product and prompts for history documentation (change log).

TODO
====
* Add proper documentation.
* Make all the scripts more general and configurable.
* All the SVN stuff should be optional or at least configurable.
* Some options on create script are not compatible with each other. for now you have to know what you are doing.
* SVN add on new files for app layer and dependencies.

Wish list
=========
  Would be great to have a config file where we setup stuff like which repository we are using (now collective SVN is hardcoded) and give a Git mode to it also.
