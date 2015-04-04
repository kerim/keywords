---
title: WordPress CMS
author: Kerim
layout: post
permalink: /archives/2007/03/08/wordpress-cms/
dsq_thread_id:
  - 825171207
categories:
  - Info Tech
---
I&#8217;ve recently gotten very good at using WordPress to power static websites. The reason being that recent changes to WordPress have made it really easy to do so. Most people think of WorPress as a blogging platform, and that is what it is setup to do out of the box. However, a few minor adjustments and you can hide the blog completely, or move it so that it isn&#8217;t the first thing you see when you visit the site. Used in this way WordPress becomes more than a blog; it becomes a CMS or Content Management System.

First, why would you want to use WordPress if you aren&#8217;t running a blog? For lots of reasons. In minutes you will be running a fully functional website which conforms to web standards, has an rss feed, which easily allows you to change the appearance of the site by selecting from among thousands of freely available &#8220;themes,&#8221; and which makes it as easy to add new content and modify existing content as it is to write an e-mail or create a new document in Word. You can easily export all of your site&#8217;s content for safekeeping or to import it onto another website, you can password protect posts, choose whether you want Google to index your site, turn on community features allowing comments on posts and static pages, or turn them off completely, and choose from hundreds of pre-made &#8220;widgets&#8221; which add all kinds of new features and content to your site (such as a sidebar displaying your photos from flickr).

So how do you do it?

<!-- technorati tags start -->

<div style="text-align:right;">
  <span style="font-size:x-small;">{<a href="http://www.technorati.com/tag/wordpress" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.technorati.com/tag/wordpress', 'wordpress']);"  rel="tag">wordpress</a>, <a href="http://www.technorati.com/tag/cms" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.technorati.com/tag/cms', 'cms']);"  rel="tag">cms</a>, <a href="http://www.technorati.com/tag/web 2.0" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.technorati.com/tag/web 2.0', 'web 2.0']);"  rel="tag">web 2.0</a>}</span>


<!-- technorati tags end -->

<!--more-->

Well, first you have to <a href="http://wordpress.org/download/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://wordpress.org/download/', 'install wordpress']);" >install wordpress</a>. Some web hosts, like <a href="http://www.dreamhost.com/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.dreamhost.com/', 'dreamhost']);" >dreamhost</a>, offer one-click installs of wordpress. If that wasn&#8217;t easy enough, you can even sign up for a free wordpress account at <a href="http://wordpress.com/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://wordpress.com/', 'wordpress.com']);" >wordpress.com</a>. The main disadvantage of wordpress.com is that you are limited in your choice of themes and you have less control over how you can modify those themes. For instance, if you wanted to add new text to the footer of a theme, you would not be able to do this on WordPress.com, but it would be possible on a self-installed version if you spent a little time learning how to use <a href="http://www.panic.com/transmit/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.panic.com/transmit/', 'FTP']);" >FTP</a>.

Personally, I have found that the theme <a href="http://www.johntp.com/2006/09/17/triplek2-a-three-column-k2-mod-for-wordpress/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.johntp.com/2006/09/17/triplek2-a-three-column-k2-mod-for-wordpress/', 'Triple K2']);" >Triple K2</a> works best for me. You can see it in action on the <a href="http://budhantheatre.org/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://budhantheatre.org/', 'Budhan Theatre']);" >Budhan Theatre</a> website (which is still a work in progress). But there are <a href="http://budhantheatre.org/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://budhantheatre.org/', 'many other options']);" >many other options</a> to choose from.

Now the fun part.

First you create a few pages. Do this by going to the &#8220;write&#8221; page in your dashboard and choosing &#8220;write page.&#8221; You&#8217;ll already have a page called &#8220;about&#8221; which you can rename or edit by going to &#8220;manage&#8221; and selecting &#8220;pages.&#8221; The pages you create now will be the top level pages for your website. You don&#8217;t want to have too many or people will have difficulty finding where to go in your site. Three to five top-level pages is usually optimal. Depending on your theme, these will appear as either a menu along the top of your page, as on <a href="http://budhantheatre.org/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://budhantheatre.org/', 'Budhan Theatre']);" >Budhan Theatre</a>, or in your sidebar. Each page can have multiple subpages.

If you have your own WordPress install (i.e. you aren&#8217;t using WordPress.com), I would recommend installing the <a href="http://www.almosteffortless.com/wordpress/mass-edit-pages/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.almosteffortless.com/wordpress/mass-edit-pages/', 'Mass Edit Pages']);" >Mass Edit Pages</a> plugin which &#8220;allows you to edit the Page Parent (post\_parent) and Menu Order (menu\_order) of many pages, on a single page.&#8221; You will want to use the &#8220;pages&#8221; sidebar widget under &#8220;presentation&#8221; &#8212; &#8220;sidebar widgets&#8221; to display the available subpages in your sidebar. If you are using the Triple K2 theme I mentioned above, you will want to install the &#8220;pages&#8221; sidebar module under &#8220;presentation&#8221; &#8212; K2 Sidebar Modules (which is what K2 uses instead of widgets).

If you don&#8217;t want the blog to be on the front page, go to the &#8220;reading&#8221; tab under the &#8220;options&#8221; screen. You will see this:

<a href="http://www.flickr.com/photos/kerim/415232252/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.flickr.com/photos/kerim/415232252/', '']);"  title="Photo Sharing"><img src="http://farm1.static.flickr.com/180/415232252_419574fb64.jpg" width="500" height="403" alt="Wordpress Reading Options" /></a>

Choose one of your static pages for your front page. If you want your blog to appear as another page on your site, create a blank static page called &#8220;News&#8221; or &#8220;Blog&#8221; or whatever you like, and then select that as the page for your blog to appear on.

You can use the RSS widget (or sidebar module) to display your most recent blog posts on your front page. In K2 you have the option to hide this sidebar module on your blog page.

Congratulations, you now have website powered by wordpress!

Other useful plugins: <a href="http://urbangiraffe.com/plugins/audit-trail/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://urbangiraffe.com/plugins/audit-trail/', 'Audit Trail']);" >Audit Trail</a> records &#8220;actions (such as who logged in and when) and [stores] this information in the form of a log. Not only that but it records the full contents of posts (and pages) and allows you to restore a post to a previous version at any time.&#8221; Very useful for sites managed by many people where some managers might not be very experienced. <a href="http://tantannoodles.com/toolkit/wordpress-reports/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://tantannoodles.com/toolkit/wordpress-reports/', 'WordPress Reports']);" >WordPress Reports</a> lets you track your Google Analytics and/or Feedburner account to see how people are using your website. <a href="http://alexking.org/projects/wordpress" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://alexking.org/projects/wordpress', 'Share This']);" >Share This</a> &#8220;will allow your visitors to share your content via social bookmarking sites and/or e-mailing the post to a friend.&#8221;

UPDATE: How could WordPress improve their CMS features?

The part I still find inadequate is the navigation system. The various widgets and sidebar modules are OK, but I think that this could be improved. How about having a plugin which creates a second layer on the menu, the same way that the WordPress control panel does? Or drop-down menus? I&#8217;m sure there are options to implement such features, but so far I haven&#8217;t found anything I like which can easily work with a variety of pre-built WordPress Themes. Recommendations are welcome!

Also, on WordPress.com they should offer more widgets, themes, and plugins for people who wish to use their sites in this way.

