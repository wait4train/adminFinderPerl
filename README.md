# adminFinderPerl
This is script for admin page finder for perl


https://www.darksite.co.in/2013/04/how-to-find-admin-login-panel-of.html

Hello Friends this is that post which you might be looking for today i am going to tell you how to find admin panel of a website that you want to hack into so are you interested to know so let me list down ways by which you can easily get the admin login panel.
in various case i find some new born hacker able to get the user id and password by sql injection but still they give up as they unable to find the admin login panel so if you are in search of admin login panel of a website then this post will help you for sure.

Method 1:Adding URL
This is the first and easiest method to find admin login page. You can add some words
after the URL.Like

www.site.com/admin
www.site.com/administrator
www.site.com/login
www.site.com/wp-login.php
www.site.com/admin.php

Method 2:Using Various Script
You can use various scripts like various admin finder to get the admin page.Here I am
showing you an useful scripts which will help you to get the admin page.(I will release my own admin finder script soon and upadte here)
To run this script you first need to install Active Perl.get it from
http://www.activestate.com/activeperl/downloads

Now copy the code of http://pastebin.com/WWZszURW and save it as anything.pl and
run the script to get the login page of the desired site.(Remember its a python Script).

Method 3:Crawling software
You can use various crawling tool to crawl the website and get the login page. These
website crawl all the pages of the website and show the list of all pages and
directories.
Method 4:Crawling
By default various search engines crawl the entire site and by using robots.txt the site
owner actually gives the list of links that are not to be crawled by the engine.
Now most
of the time the admin ask the engine not to crawl the admin page so if you view the
robots.txt you can get the link to the login page.
www.site.com/robots.txt
Method 5:Google Dorks
Google dorks are some time very useful if you know to use it properly.so here are some example of useful Google dorks that will definitely help you in finding admin login panle of a website.

Site:site.com “admin”
Site:site.com inurl:login
site:site.com intitle:"admin login"

Method 6:Using Online Admin Finder/Scanner
There are many such online admin finder available but i am giving you the link for one of my favorite one This
site http://sc0rpion.ir/af/ will help you in finding admin login page online.

Method 7: Havij Tool
At last you can use the all time popular Havij to find admin page.Click on the HAvij Link to know more i have already written a nice post on it.
COUNTERMEASURES BY ADMIN
From this post it becomes very clear that if You (site owners) have not changed the
default URL of your site’s login page then it can easily be compromised if an attacked
gets the User name and password or even he can brute it.So it is advised that you
should change the default URL of yours login page to something uncommon which is
hard to guess like for example:
www.site.com/glass.php
www.site.com/myway.php
