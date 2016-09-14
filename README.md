# OutthinkMobile

The IBM Bluemix cloud ewnvironment provides several mobile technologies and services that can be used for creating mobile apps. This short guide will help mobile app developers select the products that best fit their needs.

Selecting the best tools for creating cool mobile apps

#1) Use the <a href="https://appbuilder.ibmcloud.com/">Mobile App Builder </a> to create catalog apps. 
The Mobile App Builder makes it super easy to quickly create mobile GUIs without coding. You can then connect the user interface to backend data sources, again without coding.  

For a tutorial on using the Mobile App Builder, please check <a href="https://console.ng.bluemix.net/docs/services/apiconnect/apic_tutorial.html#apic_tutorial">this linke<a>
<p>
<img src="https://developer.ibm.com/bluemix/wp-content/uploads/sites/20/2016/04/1-2.png">

Launch <a href="https://new-console.ng.bluemix.net/mobile/"> Mobile App Builder</a>

Step 1) Create the GUI from templates
Step 2) Use the <a href="https://github.com/ibm-bluemix-mobile-services">IBM Mobile Dashboard Store Catalog Backend</a> 
    It uses an API Connect and Node.js runtime with the Cloudant NoSQL DB, Object Storage, Mobile 
    Client Access, Push Notifications, and Mobile Analytics services on Bluemix. 

   The template exhibits common architectural design patterns that developers can use to model their backend    
   on Bluemix for mobile applications. 
 
   This backend has been created to support the new IBM Mobile Dashboard Store Catalog template. It has 
   the ability to browse a list of products and supports the viewing of images for each item in the product list

A step by step description on this link: https://github.com/ibm-bluemix-mobile-services/mobile


dW articles on this process:
<table>
<tr><td>https://developer.ibm.com/bluemix/2016/07/13/bluemix-mobile-creating-store-catalog-app-part1/<td>
<tr><td>https://developer.ibm.com/bluemix/2016/07/14/bluemix-mobile-integrating-custom-backend-part2/<td>
<tr><td>https://github.com/ibm-bluemix-mobile-services/mobiledashboard-storecatalog-backend<td>
<tr><td>https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-swift-core<td>
</table>


#2) Use MobileFirst Services Starter to create Mobile apps with Bluemix services
 
 <a data-flickr-embed="true"  href="https://www.flickr.com/photos/dpu/29385313710/in/dateposted-public/" title="MobileFirstServicvesStarter"><img src="https://c7.staticflickr.com/9/8095/29385313710_63671ff7d3_z.jpg" width="640" height="239" alt="MobileFirstServicvesStarter"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>
 
 <a href="https://console.ng.bluemix.net/catalog/starters/mobilefirst-services-starter/">Mobile First Services Starter</a> allows you to develop, deploy, and scale server-side JavaScript® apps with ease. The IBM SDK for Node.js™ provides enhanced performance, security, and serviceability.
 Services included:
 <ol>
 <li><a href="">SDK for Node.js</a>
 <li><a href="https://console.ng.bluemix.net/catalog/services/mobile-client-access/">Mobile Client Access</a>
 <li><a href="https://console.ng.bluemix.net/catalog/services/push-notifications/">Push Notifications</a>
 <li><a href="https://console.ng.bluemix.net/catalog/services/cloudant-nosql-db/">Cloudant NoSWL DB</a>
 </ol>
 
#3) Use Watson Developercloud iOS SDK to create Swift mobile apps with IBM Watson Services
 
#4) Use Watson Developer Cloud Android SDK to create Java mobile apps with IBM Watson Services
 
#5) Use <a href="https://www.ibm.com/support/knowledgecenter/SSNJXP/welcome.html">IBM MobileFirst Platform Foundation </a> to create Enterprise Apps
