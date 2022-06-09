---
title: Notifications Settings
layout: docs
---

This document explains all the settings for notifications. 

This is where user can set up criteria for notifications, granularity depending on products, time intervals for notifications, 

* TOC
{:toc}


Settings page {#page}
--------------------------------------------------


<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/notifications3.png" alt="">

**Note**: User can find this page by clicking on an icon in the bottom left corner of main navigation, then `User Settings`.

Enable/disable {#enabled}
--------------------------------------------------
User can enable or disable all the settings with one click on the toggle button `Enabled`. If this button is off, notifications will not be active.


Notifications {#notifications}
-------------------------
Button `Notifications` is a link to a page where user can see a list of previous notifications that were sent from Smart, based on user settings. If user never used notifications, this list will be empty.

Followed Items {#followed}
--------------------------------------------------------------
Button `Followed Items` opens a page where user can see a list of items he followed and will be taken into account when sending notifications.

Followed Searches {#followedsearches}
------------------------
Button `Followed Searches` opens a page with a list of saved user's searches that are followed. This is different from followed items. When user follows a search, items are generated from search results, just before notifications are dispatched. Depnding on criteria defined in the search, these items can be different every time notifications are dispatched. This is very useful if you want to be notified about changes in certain markets or areas, but not tied to specific companies.

Notifications interval {#interval}
-------------------------------------
User can choose how often notifications should be generated and sent. Options are `Daily`, `Weekly` (with additional option to choose th day of the week), `Every month on the 1st` and `Every month on the last day of the month`. Next to these options the date for next notifications batch is calculated and displayed. 

---
---
Product Fields {#fields}
----------------------------------

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/notifications4.png" alt="">


Every product has different fields that show what kind of changes user can expect from a product, and here, user can choose which are important. This granularity allows user to focus on only things that really matter, so that when notifications are sent, the data is not overwhelming. When these values are set, they will apply to all the items user is following.

---
---

Integration Key {#integrationkey}
------

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/notifications5.png" alt="">

Integration Key is used on Zapier to Authenticate Zap that uses Smart Integration. Here you can copy it or generate a new one. Be sure to update it in your Zap.

Test Zap {#testZap}
-----

Option to send a test Zap is used once your Zap has been set up, published and turned on, so you can receive test data and see if everything works as expected. If Zap was sent successfully you will see a notification in the top left corner.


<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/notifications5.png" width="350px" height="110px" alt="">