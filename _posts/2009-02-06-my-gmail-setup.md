---
title: My Gmail Setup
author: Kerim Friedman
layout: post
permalink: /archives/2009/02/06/my-gmail-setup/
posterous_678df9ff4da7c424c7dc64d0b819e75e_post_id:
  - 'O:16:"SimpleXMLElement":1:{i:0;s:6:"396254";}'
posterous_678df9ff4da7c424c7dc64d0b819e75e_permalink:
  - http://scrapbook.oxus.net/my-gmail-setup
categories:
  - Old Blog Import
tags:
  - apple
  - filters
  - firefox
  - gmail
  - greasemonkey
  - imap
  - iphone
  - mail
---
I have e-mail going back to the 90s, but I started using <a href="http://mail.google.com/support/bin/answer.py?hl=en&answer=75725" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://mail.google.com/support/bin/answer.py?hl=en&answer=75725', 'IMAP']);"  target="_blank">IMAP</a> in 2002 and I&#8217;m pretty sure I have saved almost every e-mail I sent or received since then. About a month ago I moved these thousands of e-mails over to my Gmail account, which I&#8217;ve since using as my primary client. I&#8217;ve been very happy with the setup and I&#8217;m thinking of helping my wife do the same thing, but first I wanted to make a record of how I made the transition and of the various tweeks I applied to Gmail and Firefox so that I can remember it all. 

**<span style="font-size: medium;">Migration</span>**

  * First, make sure you <a href="http://mail.google.com/support/bin/answer.py?answer=77695" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://mail.google.com/support/bin/answer.py?answer=77695', 'enable IMAP']);"  target="_blank">enable IMAP</a> in Gmail, and configure your current client.
  * Second, if you have a lot of folders already, you&#8217;ll probably want to keep these on Gmail. It isn&#8217;t widely known, but it is possible to support hierarchical folders on Gmail by naming folders with a slash. So, &#8220;school/students&#8221; and &#8220;school/faculty&#8221; will group the folders &#8220;students&#8221; and &#8220;faculty&#8221; under the &#8220;school&#8221; folder. This is a bit of a hack, however, as it requires the <a href="http://userscripts.org/scripts/show/8810" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://userscripts.org/scripts/show/8810', 'Folders4Gmail']);"  target="_blank">Folders4Gmail</a> greasemonkey script to work. You can also install this via the <a href="https://addons.mozilla.org/en-US/firefox/addon/4866" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'https://addons.mozilla.org/en-US/firefox/addon/4866', 'Better Gmail']);"  target="_blank">Better Gmail</a> Firefox extension. (I find I also need the <a href="http://userscripts.org/scripts/show/15741" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://userscripts.org/scripts/show/15741', 'GmailSidePaneWidth']);" >GmailSidePaneWidth</a> script to make the folder names readable.) 
  * Third, simply drag and drop your e-mail from your current mail client to the matching folder in Gmail. In my experience you don&#8217;t want to do more than 1000 e-mails at a time, so if you have a large folder, do it in batches. Also, the count at the other end might not be the same because Gmail deletes duplicates, merges multiple mails into a single &#8220;conversation&#8221; and catches SPAM you might have missed earlier.
  * Finally, you&#8217;ll want to make sure your address book is imported. There are a number of ways to do this, but the easiest is to sign up for <a href="http://spanningsync.com/?r=W47SE6" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://spanningsync.com/?r=W47SE6', 'Spanning Sync']);" >Spanning Sync</a>, which will keep your Apple address book and Gmail in sync everytime you make a change! 
  * [If you are switching from another online e-mail service, try Google&#8217;s <a href="https://mail.google.com/support/bin/static.py?page=switchguide.html&switch=1" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'https://mail.google.com/support/bin/static.py?page=switchguide.html&switch=1', 'interactive switching guide']);" >interactive switching guide</a>. Although it doesn&#8217;t really tell you how to import your actual e-mail, just your contact list. **UPDATE**: See <a href="http://googlesystem.blogspot.com/2009/02/import-contacts-and-mail-to-gmail.html" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://googlesystem.blogspot.com/2009/02/import-contacts-and-mail-to-gmail.html', 'this post']);" >this post</a> about new mail import options.]

**<span style="font-size: medium;">Using (and Tweaking) Gmail</span>**

  * Although I mostly use Gmail via the web interface, you&#8217;ll still want to tweak the IMAP experience to make sure that everything is working right. 
      * Turn on &#8220;<span class="jwjW1c">Advanced IMAP Controls&#8221; under the &#8220;<a href="https://mail.google.com/mail/#settings/labs" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'https://mail.google.com/mail/#settings/labs', 'labs']);" >labs</a>&#8221; setting panel. This will allow you to go to your &#8220;<a href="https://mail.google.com/mail/#settings/labels" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'https://mail.google.com/mail/#settings/labels', 'labels']);" >labels</a>&#8221; panel and turn off IMAP sync for individual folders. If all your e-mail is assigned a label you can turn off sync for the &#8220;all mail&#8221; folder, thus preventing your client from wasting time downloading duplicates. You can also turn off sync for the spam folder, and if you subscribe to e-mail lists, uncheck all those as well.</span>
      * <span class="jwjW1c">IMAP on Gmail works a little differently than it does on other platforms. For instance, if you have it set up the way Google <a href="http://mail.google.com/support/bin/answer.py?answer=78892" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://mail.google.com/support/bin/answer.py?answer=78892', 'recommends']);" >recommends</a>, deleting an e-mail on your client should &#8220;archive&#8221; the e-mail on Gmail rather than actually deleting it. If you have an iPhone follow <a href="http://mail.google.com/support/bin/answer.py?hl=en&answer=77702" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://mail.google.com/support/bin/answer.py?hl=en&answer=77702', 'these instructions']);" >these instructions</a> for setting up IMAP on your phone, don&#8217;t use the default Gmail settings. <br /> </span>
  * <span class="jwjW1c">Turn on &#8220;Offline&#8221; under labs to enable access to your most recent 10,000 e-mail messages when you are offline, via google gears. This also seems to speed up Gmail.<br /></span>
  * Get notified of new mail via the <a href="http://toolbar.google.com/gmail-helper/notifier_mac.html%20" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://toolbar.google.com/gmail-helper/notifier_mac.html%20', 'Gmail notifier']);" >Gmail notifier</a> application. This will also set Gmail as the default way to send e-mails when you click on an e-mail address. (You may need to follow <a href="http://lifehacker.com/392287/set-firefox-3-to-launch-gmail-for-mailto-links" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://lifehacker.com/392287/set-firefox-3-to-launch-gmail-for-mailto-links', 'these instructions']);" >these instructions</a> for Fireforx.) 
  * <a href="http://is.gd/dWkS" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://is.gd/dWkS', 'Search Gmail']);" >Search Gmail</a> directly from the firefox toolbar.
  * Once you&#8217;ve set up <a href="http://mail.google.com/support/bin/answer.py?answer=6579&topic=13285" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://mail.google.com/support/bin/answer.py?answer=6579&topic=13285', 'filters']);" >filters</a> to automatically label most of your e-mail as it comes in, you just need to &#8220;archive&#8221; a message to get it out of your inbox when you are done. Often, however, you need to reply to a message first. This is where the labs option for a &#8220;<span class="jwjW1c">Send & Archive&#8221; button comes in very handy.</span>
  * <span class="jwjW1c">There are many other options in labs, with new ones coming out all the time, but one more which I highly recommend is &#8220;Multiple Inboxes.&#8221; With this you can have all your &#8220;starred&#8221; e-mail appear on the same screen as your inbox. This is very useful for conversations which are still &#8220;active&#8221; but which you don&#8217;t need to reply to immediately. For instance, when you are waiting for the other person&#8217;s reply.</span>
  * <span class="jwjW1c">Google also allows you to <a href="http://mail.google.com/support/bin/answer.py?answer=80637&topic=12857" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://mail.google.com/support/bin/answer.py?answer=80637&topic=12857', 'assign colors']);" >assign colors</a> to labels. (If you are using Folders4Gmail I find it useful to set all subfolders to the same color.)</span>

**<span style="font-size: medium;">Hints and Tips</span>**

  * Take the time to learn about Gmails <a href="http://mail.google.com/support/bin/answer.py?hl=en&answer=7190" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://mail.google.com/support/bin/answer.py?hl=en&answer=7190', 'advanced search operators']);" >advanced search operators</a>.&nbsp;
  * You can copy and paste search results from Gmail and send them to another user. If they use Gmail as well they will find the same e-mails you find (if the search is well constructed.)
  * Create filters to automatically move all non-important e-mail out of your mailbox.   
      * When I sign up for social web services like Twitter, Facebook, etc. I now use my <a href="http://www.otherinbox.com/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.otherinbox.com/', 'Otherinbox']);" >Otherinbox</a> account, so I don&#8217;t even need to see these in Gmail. Otherinbox can also work with Gmail to do this automatically, but I prefer to do it myself.&nbsp;
  * When looking at an e-mail it has a unique number in the URL. You can copy and paste this, or bookmark it to find it again, even if you move it to a different label/folder. (I use this with <a href="http://culturedcode.com/things/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://culturedcode.com/things/', 'Things']);" >Things</a>.)
  * Turn on &#8220;<span class="jwjW1c">Quick Links&#8221; in labs to save custom searchs, like &#8220;has:attachment is:unread&#8221; for all unread e-mails with attachments.</span>

I think that&#8217;s enough to get anyone started. If you have any other suggestions or tips, leave them in the comments.

<span style="font-size: large;"><strong>Updates</strong></span>

  * I forgot to link to the <a href="http://lifehacker.com/5137921/gcompose-is-the-fastest-way-to-compose-a-gmail-message" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://lifehacker.com/5137921/gcompose-is-the-fastest-way-to-compose-a-gmail-message', 'gCompose bookmarklet']);" >gCompose bookmarklet</a>.

&nbsp;

