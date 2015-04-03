---
title: 'Travel, Time Zones, Google Cal, &#038; iOS'
author: Kerim Friedman
layout: post
permalink: /archives/2010/11/14/travel-time-zones-google-cal-ios/
posterous_678df9ff4da7c424c7dc64d0b819e75e_post_id:
  - 'O:16:"SimpleXMLElement":1:{i:0;s:8:"33438655";}'
posterous_678df9ff4da7c424c7dc64d0b819e75e_permalink:
  - http://scrapbook.oxus.net/travel-time-zones-google-cal-ios
categories:
  - Old Blog Import
---
I finally figured it out. The last time I traveled abroad for a conference I tried setting up a Google Calendar to schedule my conference events and it was a complete disaster, but this time finally go tit working and I thought I'd write a quick note about how I did it, including getting the calendar to show the correct time on my iOS device. 

**#1 The time zone setting in Google Calendar is useless.**

When you create a new Google Calendar it is possible to set a time zone. Don't let this setting fool you. All this does is set the default time zone for calendars which are published to the web. All items are still associated with the default time zone in your Google Calendar settings. So if your New Orleans calendar's default time zone is US Central Time (-6 GMT), but your account settings are for Taipei (+8 GMT), creating an event for 8PM on Thursday in the New Orleans calendar will still be set for 8PM in Taipei (+8 GMT), not 8PM in New Orleans. The only way around this is to change your Google account time zone setting before creating the new event.

**#2 Your iOS device has two time zone settings.**

Once you've followed the instructions in step #1, your Google calendars will work fine, but you may still have problems on your iPhone or iPad if you sync calendars with Google. Here's how to fix that. From a Google employee's post to an online discussion about this problem: <a href="http://j.mp/dxJf3r" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://j.mp/dxJf3r', 'http://j.mp/dxJf3r']);" >http://j.mp/dxJf3r</a> 

> There are two timezone settings on the iPhone &#8211; one is the global one under Settings->Date & Time->Time Zone, and one is the sync-specific one under Settings->Mail, Contacts, Calendars->Time Zone Support

Neither of these fixes is difficult, but they are not obvious and can cause a lot of frustration. Google should allow you to create events in a time zone other than the default one, and Apple should show you if you have "Time Zone Support" turned on within the calendar application by stating the current time zone being used by the application.

