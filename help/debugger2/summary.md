---
description: null
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;id service
seo-description: null
seo-title: Summary Screen
title: Summary Screen
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
---

# Summary Screen{#summary-screen}

> [!IMPORTANT]
>
> Adobe Experience Cloud Cloud Debugger 2.0 is currently in beta. The documentation and the functionality are subject to change. 

To run the Adobe Experience Platform Debugger, click the icon on your browser bar, then open the page you want to examine in the browser.

![](assets/start-icon.jpg)

The Adobe Experience Platform Debugger Summary screen appears.

![](assets/summary.jpg)

This screen shows information about each Adobe Experience Cloud solution. The information shown varies by solution, but typically includes information including the solution library and version (for example, "AppMeasurement v2.9") and account identifiers (such as the Analytics report suite ID, the Target client code, the Audience Manager partner ID, and so on)

## Information shown in the Debugger {#section-88a95ba53dca43d9b96a585e75e5f5cf}

The Debugger shows the following information for each solution:

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Report Suite(s) </p> </td> 
   <td colname="col2"> <p>A <a href="https://experiencecloud.adobe.com/resources/help/en_US/reference/report_suites_admin.html" format="html" scope="external"> report suite</a> defines the complete, independent reporting on a chosen website, set of websites, or subset of web pages </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>The <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/appmeasure_mjs.html" format="html" scope="external"> AppMeasurement</a> version defined for the page </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Visitor Version </p> </td> 
   <td colname="col2"> <p>The version of the <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> visitor ID</a> library. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Page Name </p> </td> 
   <td colname="col2"> <p>The <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/pageName.html" format="html" scope="external"> pageName</a> variable sent to Analytics that contains a user friendly name of the site. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Modules </p> </td> 
   <td colname="col2"> <p>The modules loaded by Adobe Analytics </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Partner </p> </td> 
   <td colname="col2"> <p>The <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external"> partner name</a> for the DIL instance </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>The<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external"> version number</a> for the DIL instance </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>The <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external"> Unique User ID</a> associated with the DIL instance </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Name </p> </td> 
   <td colname="col2"> <p>The name of the Adobe Launch <a href="https://docs.adobelaunch.com/administration/companies-and-properties" format="https" scope="external"> property</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>The version of <a href="https://developer.adobelaunch.com/guides/extensions/turbine-free-variable/" format="https" scope="external"> Turbine</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Build Date </p> </td> 
   <td colname="col2"> <p>The Launch <a href="https://docs.adobelaunch.com/publishing/libraries" format="https" scope="external"> library</a> build date </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Environment </p> </td> 
   <td colname="col2"> <p>The <a href="https://docs.adobelaunch.com/administration/environments" format="https" scope="external"> environment</a> used by the Launch library </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Extensions </p> </td> 
   <td colname="col2"> <p>The extensions used on the page </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Web SDK**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Library Version </p> </td> 
   <td colname="col2"> <p>The number of the AEB Web SDK <a href="https://docs.adobe.com/content/help/en/launch/using/extensions-ref/adobe-extension/aep-extension/overview.html" format="html" scope="external">library version</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Namespace</p> </td> 
   <td colname="col2"> <p>The name identified in the extension</p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Property ID </p> </td> 
   <td colname="col2"> <p>The name of the Launch property specified in the extension </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Edge Domain </p> </td> 
   <td colname="col2"> <p>The domain that the Adobe Experience Platform extension sends and receives data from </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>IMS Organization ID </p> </td> 
   <td colname="col2"> <p>The organization that you would like the data sent to at Adobe, as specified in the extension </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Logging Enabled </p> </td> 
   <td colname="col2"> <p>Specifies whether logging has been enabled for this property</p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID Service**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud Org ID </p> </td> 
   <td colname="col2"> <p>Your <a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/" format="https" scope="external"> Organization ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>The version of the<a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> visitor ID</a> library </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Client Code </p> </td> 
   <td colname="col2"> <p>Your Target <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> Client Code </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Your current <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> or mbox.js version </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Global Request Name </p> </td> 
   <td colname="col2"> <p>The<a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> global mbox</a> refers to the single server call made at the top of each web page in your Target implementation </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Page Load Event </p> </td> 
   <td colname="col2"> <p>The type of <a href="https://docs.adobe.com/content/help/en/launch/using/extensions-ref/adobe-extension/target-extension/overview.html" format="html" scope="external">event</a> that fires when the page loads </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Request Name </p> </td> 
   <td colname="col2"> <p>The name of a request around a <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> location</a> on the page. Available without authentication only if you implement the Debugging event listener in your code or tag manager and turn on the necessary <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> response tokens</a> in the Target UI. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Activity Name </p> </td> 
   <td colname="col2"> <p>The name of the Target <a href="https://docs.adobe.com/content/help/en/target/using/activities/activities.html" format="html" scope="external"> campaign or activity</a>. Available without authentication only if you implement the Debugging event listener in your code or tag manager and turn on the necessary <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> response tokens</a> in the Target UI. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Activity ID </p> </td> 
   <td colname="col2"> <p>The ID of the Target activity. Available without authentication only if you implement the Debugging event listener in your code or tag manager and turn on the necessary <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> response tokens</a> in the Target UI. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Experience Name </p> </td> 
   <td colname="col2"> <p>The name of the Target <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"> experience</a>. Available without authentication only if you implement the Debugging event listener in your code or tag manager and turn on the necessary <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> response tokens</a> in the Target UI. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Experience ID </p> </td> 
   <td colname="col2"> <p>The ID of the Target experience. Available without authentication only if you implement the Debugging event listener in your code or tag manager and turn on the necessary <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> response tokens</a> in the Target UI. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Offer Name</p> </td> 
   <td colname="col2"> <p>The name of the Target <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"> offer</a>. Available without authentication only if you implement the Debugging event listener in your code or tag manager and turn on the necessary <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> response tokens</a> in the Target UI. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Offer ID </p> </td> 
   <td colname="col2"> <p>The ID of the Target offer. Available without authentication only if you implement the Debugging event listener in your code or tag manager and turn on the necessary <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> response tokens</a> in the Target UI. </p> </td> 
  </tr> 
 </tbody> 
</table>

