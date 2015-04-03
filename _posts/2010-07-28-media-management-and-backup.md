---
title: Media Management and Backup
author: Kerim Friedman
layout: post
permalink: /archives/2010/07/28/media-management-and-backup/
posterous_678df9ff4da7c424c7dc64d0b819e75e_post_id:
  - 'O:16:"SimpleXMLElement":1:{i:0;s:8:"24353115";}'
posterous_678df9ff4da7c424c7dc64d0b819e75e_permalink:
  - http://scrapbook.oxus.net/media-management-and-backup
categories:
  - Old Blog Import
tags:
  - apple
  - backup
  - hard drives
  - media
  - RAID
---
I vividly remember throwing the 40MB hard drive for my Mac Plus out the window of my college dorm room when it died. Although I checked that the coast was clear, I still managed to scare someone who yelled at me for a long time before I was able to calm her down… Yesterday, nearly two decades after I bought that hard drive, I bought two 2TB drives and a RAID enclosure to make a 4TB media storage drive for Shashwati. We need that much to make an high resolution output of our film for festivals which will look much better than what we&#8217;ve been showing people. (For more about our film see <a href="http://dontbeatmesir.com" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://dontbeatmesir.com', 'dontbeatmesir.com']);" >dontbeatmesir.com</a>.) I&#8217;ve also had to adjust how I store media on my own computer, since the internal hard drive has no space for all the RAW photos I&#8217;m taking with my Cannon 500D. I easily shoot 16GB in a weekend and I only have about 20GB of space left on the drive. Add to that the fact that I need to back up everything and you quickly see how overwhelming media management has become in the days of high definition photos and videos. So what to do without breaking the bank? Below is the solution I&#8217;ve come up with. It might not work for everyone, but something like this should cover most people&#8217;s needs.

For backing up my main hard drive I need a dedicated <a href="http://support.apple.com/kb/ht1427" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://support.apple.com/kb/ht1427', 'Time Machine backup']);" >Time Machine backup</a> drive and a second drive I use for semi-monthly <a href="http://www.shirt-pocket.com/SuperDuper/SuperDuperDescription.html" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.shirt-pocket.com/SuperDuper/SuperDuperDescription.html', 'SuperDuper']);" >SuperDuper</a> backups. Both of these drives need to be as big, if not bigger than the main hard drive. It is also good to regularly take the SuperDuper clones somewhere off-site so that if the house burns you still have a copy of your data. (I also use <a href="https://www.dropbox.com/referrals/NTEyMjU1OQ" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'https://www.dropbox.com/referrals/NTEyMjU1OQ', 'DropBox']);" >DropBox</a> for cloud sync of the files I&#8217;m working on at the moment.) Then I need another hard drive for all my media. This needs to be backed up regularly as well. SuperDuper is what I&#8217;ve been using up till now, but I no longer feel that this is sufficient. I need something like Time Machine for this drive. The solution is a <a href="http://en.wikipedia.org/wiki/Disk_mirroring" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://en.wikipedia.org/wiki/Disk_mirroring', 'mirrored RAID']);" >mirrored RAID</a>. That means you have two drives of equal size in the same enclosure, and all data written to the first drive is simultaneously written to the second one as well. Since an electrical storm could conceivably wipe both drives out at the same time, it is still good to do regular SuperDuper backups which are kept off-site.

All this might seem like overkill, but anyone whose had a drive die on them will know that it is probably not cautious enough. Fortunately drives and RAID enclosures are cheaper than ever. There are also other devices like the <a href="http://www.drobo.com/" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.drobo.com/', 'Drobo']);" >Drobo</a> which improve upon the RAID concept, allowing more flexible disk configurations and other features, but at a price. In looking for a RAID enclosure it is good to find something which supports FireWire 800 or eSATA. Also some RAID devices allow you to more easily swap the drives, or even use the drives as two separate drives which can be useful. My plan is to buy two <a href="http://www.inxtron.com/products/hddmulti/nt2/nt2_800plus" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.inxtron.com/products/hddmulti/nt2/nt2_800plus', 'inXtron NT2 800+']);" >inXtron NT2 800+</a> drive enclosures and use one for my TimeMachine + SuperDuper backups, and the other for a mirrored RAID media drive. For the Hard Drives, the <a href="http://www.wdc.com/en/products/products.asp?driveid=336" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.wdc.com/en/products/products.asp?driveid=336', 'Western Digital Caviar Green']);" >Western Digital Caviar Green</a> series seems like the most energy efficient and cost effective option for storage drives. You&#8217;d want the <a href="http://www.wdc.com/en/products/products.asp?driveid=488" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.wdc.com/en/products/products.asp?driveid=488', 'Caviar Black']);" >Caviar Black</a> for something where speed is more important.

I can&#8217;t help but feel that by the time I post this blog post, the information will already be out of date. I certainly can&#8217;t imagine what we&#8217;ll be doing for media backup in another twenty years…

NOTES

1. The advantage of the Drobo is not needing to copy everything over when you upgrade your RAID you can do it a piece at a time. However, from what I can tell it isn&#8217;t worth it. The device costs more than five times as much and is also much slower.

2. For more on why I chose Western Digital <a href="http://hothardware.com/printarticle.aspx?articleid=1490" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://hothardware.com/printarticle.aspx?articleid=1490', 'read this']);" >read this</a>.

3. The eSATA version of the inXtron NT2 (the &#8220;Super-S Combo&#8221;) does not allow drives to function independently, without a RAID, the 800+ does. In Taiwan I recommend <a href="http://www.heyshopping.com.tw/index.asp" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.heyshopping.com.tw/index.asp', 'byja.com']);" >byja.com</a> for getting firewire RAID enclosures.

