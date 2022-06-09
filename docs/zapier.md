---
title: Smart Integration
layout: zapier
---
### Creating a Zap {#anc1}

If you have done all the necessary steps, like opening an account with Zapier, followed products on Smart and set up Notification Settings, you are ready to create your first Zap.

Click on `+ Create Zap` button on the left menu, to start the process.

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap1.png" height="542px" width="294px" alt="">


---
---
### Choose Smart Integration {#anc2}

To start the first step you have to find Smart Apartment Data integration on Zapier.


<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap2.png" alt="">


---
---
### Choose a Zap Event {#anc3}

Smart Integration only has one Event defined. Notifications Subscription Event has built in mechanism to work with Smart system in delivering notifications to your Zap.


<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap3.png" alt="">


---
---
### Authentication {#anc4}

Next, you have to Authenticate your Zap with Smart platform. A popup window will open, where you need to insert an Integration Key that you copied from Smart in the Notification Settings.


<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap4.png" alt="">


---
---
### Testing the trigger {#anc5}

You are now ready to test if integration receives data from Smart. Click `Test Trigger` button.


<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap5.png" alt="">


---
---
### Notifications received {#anc6}

A test notification was sent to Zapier to validate and show a typical payload sent to a Zap. This is the end of the first step.


<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap6.png" alt="">

---
---
### Integration or Path {#anc7}

Next step could be just choosing another integration, like Gmail, Office, Slack etc. or creating paths. 


<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap7.png" alt="">

---
---
### Diverging to paths {#anc8}

Here we show how you can decide to use different integrations on step #2, depending on data that is received. By default you can have two starting paths.

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap8.png" alt="">

---
---
### Path A {#anc9}

On a path, we can set up rules for incoming data. Here is an example of a rule that lets through only notifications with "Type" set to "Property" and "Field" to "Management".

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap9.png" alt="">

---
---
### Testing the path {#anc10}

When path is tested, we see that the test notification would pass, since these are exact values that were in test notification.


<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap10.png" alt="">

---
---
### 3drd Party Integration on path A {#anc11}

This is the next step, where we choose where the data from Smart will go, from the choice of 3rd party integrations.

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap11.png" alt="">

---
---
### Gmail example {#anc12}

Here we can see how path A can be connected to a 3rd party integration like Gmail. Login with your Gmail account and choose
the type of Event this integration offers, like sending an email.

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap12.png" alt="">

---
---
### Choosing data from notification {#anc13}

There are a lot of properties in payload for the notification. You don't have to send all of it. Here you can choose which ones will be part of the content of an email and add some text to give it context. At the end of this step you can test it and a test email will be sent to the address of your choice.

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap13.png" alt="">

---
---
### Publish Zap {#anc14}

Once you have repeated steps for path B, Zap is ready to be published, which you can do by pressing on the button `Publish` in the top right corner.

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap14.png" height="75px" width="130px" alt="">

---
---
### Turn it On {#anc15}

When you return to the main page, you new Zap will be in the list of your Zaps and you can turn it on.

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap15.png" height="75px" width="700px" alt="">

---
---
### Zap History {#anc16}

On Smart platform you can now send a test Zap, which will have all the possible combinations of notifications, according to Type and Field values, so you can easily see if everything works as expected. Then you can click on an icon with three dots on your Zap and choose "History".

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap16.png" height="400px" width="310px" alt="">

---
---
### History list {#anc17}

All the notifications that were received by your Zap are listed here. 

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap18.png" alt="">

---
---
### Details {#anc18}

When you choose an item from the History list, you will see details and data that was sent. After that, you can also check if the integrations you used in your Zap have correctly received/sent data.

<img class="img-responsive docs-img" src="{{ site.baseurl }}/assets/zap17.png" alt="">

