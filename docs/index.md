---
title: Get Started
layout: docs
---
### Get started {#getstarted}

Notifications are closely tied to product timeline updates. Every time there is a change within a Property, Management, Pipeline, Directory or a Developer, this creates a new update in the timeline. Within each of the product, there are different types of updates. If you follow a Property or a Management, you have to define which changes you want to be notified on. This is done on Notification Settings page. Product updates are collected in the database and when it's time for sending notifications (defined by user), all these updates are funneled through different criteria in notification settings and the resulting updates are sent to a 3rd party service, like Zapier. There, user that created a Zap with Smart Integration, can decide what to do with received data and which other integrations should receive it. 

<div class="alert alert-info">
    <b>Note:</b> This site is for version 2.x of the WDC API, which is compatible only with Tableau 10.0 and later. Version 1 of the WDC API, used with earlier versions of Tableau, is no longer supported.  
</div>

<div class="alert alert-warning">
    <b>Note:</b> This site is for version 2.x of the WDC API, which is compatible only with Tableau 10.0 and later. Version 1 of the WDC API, used with earlier versions of Tableau, is no longer supported.  
</div>

<div class="alert alert-note">
    <b>Note:</b> This site is for version 2.x of the WDC API, which is compatible only with Tableau 10.0 and later. Version 1 of the WDC API, used with earlier versions of Tableau, is no longer supported.  
</div>

<div class="alert alert-important">
    <b>Note:</b> This site is for version 2.x of the WDC API, which is compatible only with Tableau 10.0 and later. Version 1 of the WDC API, used with earlier versions of Tableau, is no longer supported.  
</div>

-----

**Upgrading from WDC version 1.x**
 
If you have connectors that were created using WDC version 1.x, those connectors might not work in later versions of Tableau. If you want your connector to work in later versions of Tableau, or if you want to use the features available in version 2.x of the WDC, you will need to update the connector. For information about updating your connectors, see [Upgrading from WDC Version 1.x]({{ site.baseurl }}\docs\wdc_upgrade). For information about version compatibility, see [WDC Versions]({{ site.baseurl }}\docs\wdc_library_versions).


-----

This section will guide you through the process of setting up your development environment and running the sample WDCs in the simulator.

* TOC
{:toc}

### Confirm prerequisites

You're going to need a couple of things before we get started. Make sure you have the following dependencies installed:

* [Git](https://git-scm.com/downloads)
* [node and npm](https://nodejs.org/en/download/)

### Get the WDC SDK

1. Open a terminal in the directory where you want to download the WDC SDK.  Then run the following command to clone
   the WDC git repository:

   ```
   git clone https://github.com/tableau/webdataconnector.git
   ```

1. Change to the directory where you downloaded the repository:

   ```
   cd webdataconnector
   ```

### Run the simulator

1. Install dependencies with `npm`:

   ```
   npm install --production
   ```

   **Note**: You must run the command with administrator or sudo privileges.

1. Start the test web server:

   ```
   npm start
   ```

1. Open a browser and navigate to the following URL:


   ```
   http://localhost:8888/Simulator/index.html
   ```

   The WDC simulator appears.

   ![]({{ site.baseurl }}/assets/wdc_simulator_new_first_open.png)

**Note**: The `npm start` command also starts a test proxy server on port 8889 that you can route requests through in order to
circumvent Cross Origin Resource Sharing (CORS) restrictions. For more information, see
[Working with CORS]({{ site.baseurl }}/docs/wdc_cors).

### Try the sample WDCs

1. In the WDC URL field, confirm that the URL is set to the sample USGS
   Earthquake Data connector:

   ```
   ../Examples/html/earthquakeUSGS.html
   ```

   Alternatively, look in the Examples directory for more sample connectors.

1. Click the **Start Interactive Phase** button to display the user interface for the earthquake WDC.

1. Click the **Get Earthquake Data** button.

1. Click the **Fetch Table Data** button to download the data and display it in a table.


*Ready to make your own connector? Jump to the [WDC Tutorial]({{ site.baseurl }}/docs/wdc_tutorial).*
