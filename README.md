haaretz-reader-poc
==================

Overview
--------
Proof of concept for Haaretz website reader.

:bulb: This Chromium extension was created in order demonstrate that the premium identification mechanism of Haaretz web site is not effective.
Number of messages regarding to this issue sent to Haaretz using the website contact form on the site, and not responded so far.

:warning: This code is released without any warranty.
:warning: Do not use this code in any activity which is not for a demonstration.
:warning: Using of this code for any other purpose may violate copyrights or criminal law.



Description
-----------
Haaretz website allow none premium users to watch premium content if they click on an article link in social networks like Facebook or Twitter.
The current mechanism only check the "Referer" header sent with the HTTP request.
This extension is using chrome/API to add a "Referer" header to each 'Haaretz' request with random value (for now, only Facebook and Twitter).
