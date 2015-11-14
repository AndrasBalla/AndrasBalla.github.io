---
layout: post
title: Pre-compiling CSS
date:   2015-11-13 15:43:50
author: Andras Balla
---

I will now talk about how Pre-compiling CSS code works. 

1. Compared to regular CSS SASS is a life saver it makes writing CSS code easier by adding features like variables, mixins, inheritance and much more.
For me the biggest and best feature is that it removes a lot of the repeticion of CSS with the use of nesting and variables.
On the other hand it is a bit harder to use since you need software that will build your main css file from all the SASS files you created but CSS files are getting larger every year
so this approach makes the code easier to maintain and to update/upgrade.

2. For creating this site i created one main css file where i wrote in all the variables and then imported 3 other css files to create the look of the site.
The 3 files got split up in 3 categories: 
    * base
    * layout
    * highlighting 
The base file offers a baseline for the hole website so that you have the same style acros the hole page. Highlighting offers style for errors, comments etc and the layout file determines 
as tha name says the layout of the site in therms of looks and placement.

3. Pros:
    * Less code.
    * Easy to maintain/update. 
    * Easy to work with smaller files.
    
4. Cons:
    * Setup required. 
    * Harder to debugg.
    * Finished CSS file can be messy and hard to follow. 
