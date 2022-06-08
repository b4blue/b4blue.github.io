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


<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/notificationSettings.png" alt="">

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


Pass data between phases
------------------------

Often it is necessary to pass data from one phase to another.
For example, you might want to store user input from the interaction phase and use the input in the get data phase to build personalized requests to an API.

You can store data that you want to pass between phases using the `tableau.connectionData` property.
The property can only store data as a string, so if you want to store JavaScript objects, you must serialize and deserialize the data.

For example, to store a JavaScript object as a string, you might run the following code:

```
tableau.connectionData = JSON.stringify(example_data);
```

Then, to convert the string back into a JavaScript object, you might run the following code:

```
JSON.parse(tableau.connectionData);
```

For an example of how you might use this in a web data connector, see the [Multiple Tables Tutorial]({{ site.baseurl }}/docs/wdc_multi_table_tutorial).
