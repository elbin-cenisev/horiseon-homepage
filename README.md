# Horiseon Homepage
Homework Assignment: Refactoring code for the Horiseon Homepage
Author (of refactoring): Elbin Cenisev

This assignment involved refactoring existing html and css code.

The existing HTML code is contained in original-annotated.html. The comments are my own.
The original code was already functional (except for one of the links) and my refactoring of the code did not affect any functional or visual aspects of the page.

My refactoring of the HTML code only aimed at improving search engine optimization by adding accessibility elements and generally optimizing the code by replacing parts of the HTML code with semantic elements. The code is now divided into clear sections defined by unique <id="">s.

The only real problem was that the Search Engine Optimization link did not work due to its <a href=""> element linking to a class instead of an id. That has been fixed now, all links should be working.

The original css code is contained in original.css. It is not commented.
The original CSS code was unnecessarily bloated and unorganized. 
My refactoring aimed at conslidating some of the selectors so that the page can load faster and generally making it easier to read. 
