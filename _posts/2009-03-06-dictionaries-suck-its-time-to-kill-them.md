---
title: Dictionaries suck. Its time to kill them.
author: Kerim Friedman
layout: post
permalink: /archives/2009/03/06/dictionaries-suck-its-time-to-kill-them/
posterous_678df9ff4da7c424c7dc64d0b819e75e_post_id:
  - 'O:16:"SimpleXMLElement":1:{i:0;s:6:"484740";}'
posterous_678df9ff4da7c424c7dc64d0b819e75e_permalink:
  - http://scrapbook.oxus.net/dictionaries-suck-its-time-to
categories:
  - Old Blog Import
---
When I look up a word I need for a lecture on political-economy or colonial theory, I know I will not find the word I need in my dictionary. And I have the largest Chinese-English dictionary I could buy: the ABC dictionary included in Wenlin. Even if I do find a phrase, I can be fairly certain that the one in my dictionary is not the one most commonly used by scholars, or which is used in Taiwan. Accordingly, I do the following. I suspect you do the same as well:

1. Look it up in Wikipedia. If I&#8217;m lucky there is a Chinese version of the same page and the title of the Chinese version is the word I want. Great for proper names.

2. Look it up in Google translate. Can&#8217;t really trust this, but sometimes it gives me a phrase which i can then plug into my own dictionary or a google search to see if it is correct.

3. Do a search in Google restricted to Traditional Chinese results, but for the English word. I&#8217;ll often find academic papers which use the English word in brackets after the Chinese phrase.

4. Do a Google search on Traditional Chinese pages for various possible translations to see the context in which they are used and the frequency in which they occur. 

So the question is whether it is possible to create a application or web-app which harnesses these various tools and combines them together to make this process even easier? For instance, you put in an English word on top and get results for the Chinese Wikipedia, Google Translate, CDICT (a free Chinese-English dictionary), and straight Google search results limited to TC pages. In addition, all the most common phrases are pulled out and listed in an easy-to-use manner, showing both the frequency the phrased is used (Google hits) as well as samples of the phrase being used in context (Google search results). Perhaps even throw in Google Image search as well &#8211; for some things that can quickly show you if you&#8217;ve found the right phrase.

An even better implementation would allow you to refine your search and narrow down various possibilities.

Feel free to steal this idea and build something fantastic!

UPDATE: Here are three examples:

  * &#8220;<a href="http://www.google.com/search?hl=en&as_q=subaltern+studies&as_epq=&as_oq=&as_eq=&num=30&lr=lang_zh-TW&as_filetype=&ft=i&as_sitesearch=&as_qdr=all&as_rights=&as_occt=any&cr=&as_nlo=&as_nhi=&safe=images" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.google.com/search?hl=en&as_q=subaltern+studies&as_epq=&as_oq=&as_eq=&num=30&lr=lang_zh-TW&as_filetype=&ft=i&as_sitesearch=&as_qdr=all&as_rights=&as_occt=any&cr=&as_nlo=&as_nhi=&safe=images', 'Subaltern Studies']);" >Subaltern Studies</a>&#8221; (Click for Google search in Traditional Chinese. The first and third results are different, but a google search for each will reveal that 底層研究 gets 2.7 million hits, while 賤民研究 gives only 83,400, suggesting that the third result &#8211; 底層研究 &#8211; offers the more appropriate translation.)
  * &#8220;<a href="http://en.wikipedia.org/wiki/Slumdog_Millionaire" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://en.wikipedia.org/wiki/Slumdog_Millionaire', 'Slumdog Millionaire']);" >Slumdog Millionaire</a>&#8221; (Click on the Wikipedia link, then click on <a href="http://zh.wikipedia.org/wiki/%E8%B2%A7%E6%B0%91%E7%99%BE%E8%90%AC%E5%AF%8C%E7%BF%81" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://zh.wikipedia.org/wiki/%E8%B2%A7%E6%B0%91%E7%99%BE%E8%90%AC%E5%AF%8C%E7%BF%81', '中文']);" >中文</a> to see Chinese)
  * &#8220;<a href="http://images.google.com/images?hl=en&num=30&q=%E6%AA%B3%E6%A6%94%E8%A5%BF%E6%96%BD&lr=lang_zh-TW&um=1&ie=UTF-8&sa=N&tab=wi" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://images.google.com/images?hl=en&num=30&q=%E6%AA%B3%E6%A6%94%E8%A5%BF%E6%96%BD&lr=lang_zh-TW&um=1&ie=UTF-8&sa=N&tab=wi', '檳榔西施']);" >檳榔西施</a>&#8221; (A Google Image search tells you all you need. Warning, might not be safe for work.)

My idea is to combine these tools into a single interface, together with a traditional dictionary and some usage statistics, etc.

