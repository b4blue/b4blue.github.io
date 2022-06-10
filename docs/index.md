---
title: Overview
layout: docs
---

## Introduction {#anc1}
Notifications are closely tied to product timeline updates. Every time there is a change within a Property, Management, Pipeline, Directory or a Developer, this creates a new update in the timeline. Within each of the product, there are different types of updates. If you follow a Property or a Management, you have to define which changes you want to be notified on. This is done on Notification Settings page. Product updates are collected in the database and when it's time for sending notifications (defined by user), all these updates are funneled through different criteria in notification settings and the resulting updates are sent to a 3rd party service, like Zapier. There, user that created a Zap with Smart Integration, can decide what to do with received data and which other integrations should receive it. 

---

## Setting Up Notification Settings  {#anc2}

**Note**: User can find this page by clicking on an icon in the bottom left corner of main navigation, then `User Settings`.

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/settings.jpg" alt="">

Enable/disable
--------------------------------------------------
User can enable or disable all the settings with one click on the toggle button `Enabled`. If this button is off, notifications will not be active.


### Notifications

Button `Notifications` is a link to a page where user can see a list of previous notifications that were sent from Smart, based on user settings. If user never used notifications, this list will be empty.

### Followings

Button `Followings` opens a page where user can see a list of items he followed and will be taken into account when sending notifications.
From there you can also unfollow all the items.

### Followed Searches

Button `Followed Searches` opens a page with a list of saved user's searches that are followed. This is different from followed items. When user follows a search, items are generated from search results, just before notifications are dispatched. Depending on criteria defined in the search, these items can be different every time notifications are dispatched. This is very useful if you want to be notified about changes in certain markets or areas, but not tied to specific companies.

### Notifications interval

User can choose how often notifications should be generated and sent. Options are `Daily`, `Weekly` (with additional option to choose th day of the week), `Every month on the 1st` and `Every month on the last day of the month`. Next to these options the date for next notifications batch is calculated and displayed. 

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/notifications3.png" alt="">

---
---

### Product Fields


Every product has different fields that show what kind of changes user can expect from a product, and here, user can choose which are important. This granularity allows user to focus on only things that really matter, so that when notifications are sent, the data is not overwhelming. When these values are set, they will apply to all the items user is following.

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/notifications4.png" alt="">

---
---

### Integration Key
------

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/notifications5.png" alt="">

Integration Key is used on Zapier to Authenticate Zap that uses Smart Integration. Here you can copy it or generate a new one. Be sure to update it in your Zap.

---

## Following Items (Individual/Search)  {#anc3}

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/follow_product.png" width="360px" height="450px" alt="">

Simplest option for following an item is to find it through search and click `Follow` button in the top right corner of its info card.

### Unfollow an item

To unfollow an item just click the same button.

---
---

### Follow search results

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/notifications2.png" alt="">

To follow more items at a time, when you are doing a search on a specific product, under menu `Actions` select `Follow Results` and all the items from search results will be followed.

---

## Setting up Zapier  {#anc4}

---

## Setting up Zapier Paths  {#anc5}

---

## Conclusion and Test Zaps  {#anc6}

Option to send a test Zap is used once your Zap has been set up, published and turned on, so you can receive test data and see if everything works as expected. If Zap was sent successfully you will see a notification in the top left corner.


<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/notifications1.png" width="350px" height="110px" alt="">



