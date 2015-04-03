---
title: Internationalization vs. Localization
author: Kerim Friedman
layout: post
permalink: /archives/2009/01/21/internationalization-vs-localization/
posterous_678df9ff4da7c424c7dc64d0b819e75e_post_id:
  - 'O:16:"SimpleXMLElement":1:{i:0;s:6:"353663";}'
posterous_678df9ff4da7c424c7dc64d0b819e75e_permalink:
  - http://scrapbook.oxus.net/internationalization-vs-locali
categories:
  - Old Blog Import
---
The vast majority of the world is multilingual. Not only are they   
multilingual, but many people use multiple scripts as well, including   
character based scripts like Chinese and right-to-left scripts like   
Hebrew and Arabic. In the old days of computing each of these various   
scripts was handled differently, with each computer platform using   
various different ways of implementing each script. This meant that   
one had to choose your default script (i.e. Traditional Chinese) and   
stick with that. It was difficult to mix and match scripts, and if you   
were using a computer which wasn&#8217;t set for that script as your default   
you had to know which script a website was encoded in before you could   
read it properly. In short, it was a pain in the ass to be   
multilingual on the internet. 

&nbsp;All that changed with the development of &#8220;unicode&#8221; a standard which   
allows (almost) all scripts to peacefully coexist. And most websites   
have adopted this new standard. But many have not. In Taiwan, for   
instance, many sites still expect your browser to be set for   
Traditional Chinese in order to work properly. Some sites (like the   
site I have to use to enter grades at my university) won&#8217;t even work   
unless you are using a Traditional Chinese version of Internet   
Explorer running on a Traditional Chinese version of Windows. Ugh!   
Other sites are botched because they use Adobe Flash which doesn&#8217;t yet   
accept unicode input methods on OS X. And still other sites, like   
Soup.io, are botched because they strip all unicode data when doing   
something as simple as uploading files. One reason I love my iPhone so   
much is because Palm never introduced unicode support on its PalmOS.   
Fortunately its new WebOS is built on WebKit, which has unicode   
support built in. Things are getting better, but there is still a long   
way to go. 

&nbsp;But the biggest hurdle is in the mentality of web designers. I often   
write to complain that some site or another falls short in its support   
for international text. Not just to complain, but because I like the   
site but can&#8217;t use it because it won&#8217;t accept Chinese language file   
names, book titles, contact information, or some other international   
text I need in order to do my work here in Taiwan. What drives me   
crazy is when, in response to such an e-mail, I get a blanket response   
telling me that the developers are working on a Chinese version of   
their website. This is \*not\* what I want. Localization means that all   
the menus, help text, etc. are translated into Chinese. This is great   
for people whose English is less than fluent, but even many of my   
Taiwanese colleagues here in Taiwan prefer to use websites in English.   
What they want is to use Chinese data! Support for international   
scripts is not the same thing as localization. 

&nbsp;I think the problem is that these web designers assume a one-to-one   
correspondence between users and languages. If you are Taiwanese you   
want to use their site in Chinese. Google assumes this every time I   
log in to their mobile website from my iPhone. This is even worse   
because it assumes I am Taiwanese simply because I am logging in from   
Taiwan. Not everyone in Taiwan is Taiwanese. At least on the iPhone   
they have a button to access the site in English &#8211; but on some of   
their websites, like Youtube, it seems impossible to figure out how to   
get the site in English (it is easier from some other language sites,   
but the Taiwan website makes it very difficult). Even worse, if you   
want to change the default language of the main Google homepage, the   
list of languages appears in Chinese &#8211; which not everyone using the   
website in Taiwan can read. Would you know to click on 英文 to get   
English? 

&nbsp;Web designers need to put more thought into the fact that users might   
be non-native speakers in the country in which they reside. Spanish   
speakers in the US might want a Spanish interface, and English   
speakers in China might want an English interface. They also need to   
understand that people who speak one language might need to use and   
access data in other scripts. Many Taiwanese websites have an &#8220;English   
language&#8221; version which is devoid of most of the data on the Chinese   
version, and is rarely updated. Even worse, important information,   
like a business address, are presented entirely in Latin text. Even   
non-native speakers who can&#8217;t read Chinese often need to have the   
Chinese characters for a name or address since most locals can&#8217;t read   
the romanized version of their language. The solution is to not   
ghettoize the English version of the website, but to present the two   
languages side-by-side. 

&nbsp;The internet is multilingual in that there are many different   
languages spoken on the web, but very few websites have really thought   
through the needs of multilingual users. Understanding the problem is   
the first step.

