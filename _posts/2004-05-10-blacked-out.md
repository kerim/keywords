---
title: Blacked-out
author: Kerim
layout: post
permalink: /archives/2004/05/10/blacked-out/
dsq_thread_id:
  - 825169448
categories:
  - Info Tech
  - Language
  - Law
---
The government is going to have to come up with new ways to block out information in public documents. Already there was a scandal when a sensitive document was released by the State Department as an electronic PDF file in which only the image of the words was blacked out, <a href="http://www.calpundit.com/archives/002533.html" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.calpundit.com/archives/002533.html', 'not the selectable text layer']);" >not the selectable text layer</a> underneath the image. Now, a cryptography expert has treated blacked out text as a &#8220;code&#8221; to be &#8220;cracked&#8221; and <a href="http://www.nytimes.com/2004/05/10/technology/10crypto.html?ex=1399521600&#038;en=1ff921ef003d104a&#038;ei=5007&#038;partner=USERLAND" onclick="_gaq.push(['_trackEvent', 'outbound-article', 'http://www.nytimes.com/2004/05/10/technology/10crypto.html?ex=1399521600&en=1ff921ef003d104a&ei=5007&partner=USERLAND', 'seems to have succeeded']);" >seems to have succeeded</a>. It all depends upon knowing the length of the blacked out word and then guessing how many words could be the same length in the same font.

> The program rejected all of the words that were not within three pixels of the length of the word that was probably under the blackened-out area in the document.
> 
> The software then reduced the number of possible words to just 7 from 1,530 by using semantic guidelines, including the grammatical context. The researchers selected the word &#8220;Egyptian&#8221; from the seven possible words, rejecting &#8220;Ukrainian&#8221; and &#8220;Ugandan,&#8221; because those countries would be less likely to have such information.

It seems that the government made things worse when they decided to switch from using Courier to Times New Roman:

> In January, the State Department required that its documents use a more modern font, Times New Roman, instead of Courier, Mr. Naccache said. Because Courier is a monospace font, in which all letters are of the same width, it is harder to decipher with the computer technique. There is no indication that the State Department knew that.

While it is always nice to see the hackers win one over on the government, there is reason to worry that this could lead to even less information being released to the public:

> Experts on the Freedom of Information Act said they feared the computer technique might be used as an excuse by government agencies to release even more restricted versions of documents.

