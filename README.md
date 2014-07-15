CS 106 Section Website Template
================================

This is a template for CS106 Section leaders to host a static site related to the CS106 courses. It features a simple and easily customized framework for section leaders to host and post links/course material for their sectionees.

The current template and example site both use the Readable theme from bootswatch, but any css file can be used to modify the styles. Just replace the bootstrap.min.css file with a custom css file of your own, or redefine styles already defined in the file.

How to get started:
-------------------
1. Git clone this repository into a local folder
2. Open up the static files and make any content modifications you'd like.
3. Move the entire repository into a folder inside your Stanford www/ directory.
4. Check the new hotness out at http://web.stanford.edu/~[sunet id]/[folder name]/
[5] Install some sort of AFS software or bind your favorite text editor to that folder directory so you can make direct changes to the site.

To-dos:
-------
1. Implement a smart-navbar that updates links automatically if the index.html's home page has a new list element (or just write a script ot do it...)
2. Port it over to an express framework.