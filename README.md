# Cloud Node.js Case Study 2

Prerequisite  for this toolchain creation 

* Create your bluemix account , You need to have bluemix organization 
   url : http://ng.bluemix.net
* Create a github account 
   url : https://github.com
   
Once completed, you have to click the Create toolchain button. Review the default information for the toolchain settings. The toolchain's name identifies it in IBM Cloud. If you want to use a different name, region, or organization, change them.

Note: Each toolchain is associated with a specific org. Because app names are unique, also make sure that the toolchain's name is unique within IBM Cloud. You can have only 200 toolchains per org. The org that you are currently working in is displayed by default. 

Once the application get deployed you have to check the deployed delivery pipeline. After the final job in the pipeline is completed, view your app as it runs on IBM Cloud by clicking the URL at the bottom of the deploy stage.

## Create the toolchain

1. Ensure you have 2GB of free memory and space for 3 additional services in your organization.

2. It is recommended to create a new space in your organization. This helps grouping the apps and services together in the console.

3. **To get started, click this button:**

 [![Deploy To Bluemix](./.bluemix/create_toolchain_button.png)](https://console.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/cainsomniac/dreamhome-finders-tool-01)

---
The toolchain is preconfigured for:

- issue tracking
- source control
- continuous delivery and integration (CI/CD)
- blue-green deployment

---
### Learn more

* Bluemix DevOps Services: https://new-console.ng.bluemix.net/devops
* Documentation on [Bluemix Toolchains][toolchains_overview_url]

<!--Links-->
[bot_github_url]: https://github.com/IBM-Bluemix/insurance-bot
[orders_github_url]: https://github.com/IBM-Bluemix/insurance-orders
[catalog_github_url]: https://github.com/IBM-Bluemix/insurance-catalog
[dashboard_github_url]: https://github.com/IBM-Bluemix/insurance-bot-dashboard
[ios_github_url]: https://github.com/IBM-Bluemix/insurance-bot-ios
[android_github_url]: https://github.com/IBM-Bluemix/insurance-bot-android
[toolchains_overview_url]: https://new-console.ng.bluemix.net/docs/toolchains/toolchains_overview.html
[toolchains_interconnect_video_url]: https://vimeo.com/156126035/8b04b8878a
[garage_method_url]: https://www.ibm.com/devops/method
