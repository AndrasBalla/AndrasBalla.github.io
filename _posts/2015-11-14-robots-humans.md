---
layout: post
title: robots.txt & humans.txt.
date:   2015-11-14 13:44:50
author: Andras Balla
---

### What exactly is it?

There are two text files that can be good to include when building a website.

1. robots.txt 
    * This file is used by the robots that are constantly searching the web for information or to index information. In this file you can talk to these robots and configure which parts of your site
     you want indexed and which parts you want to stay hidden from the robot. So called bad robots will mostly ignore this file and search your site for lets say emails but it is still a good 
     thing to have if you don´t want certain parts of your site to appear in search engines. You can also block all robots during development so that they don´t index placeholder material which 
     could mess with your search ranking in the future.
     * To start with i configured my own robots.txt to block all robots and when the site is finished or at least all of the placeholder material is gone I will leave the site open for all bots.
     
2. humans.txt 
     * Is a text file where you write in all of the contributors of the site this can be a short list but good to do. 
     * I have personally configured it with Name/Twitter/Location.
     * I also added some information about the site like last time is was updated, code standard used, IDE used and technology powering the site.
