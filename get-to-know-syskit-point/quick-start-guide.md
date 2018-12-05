---
title: Quick Start Guide
description: This article provides a quick overview of all the features and usual steps when accessing the application for the first time. 
author: Andrea Budiša
date: 05/12/2018
--- 

In this article, we will take you through some of the common use cases and usual steps when accessing the application for the first time. We have provided you with an overview of the entire application and how to use it. For detailed information on particular features, please explore our other articles. 

SysKit Point is a __free cloud solution__, which enables you to analyze your environment and keep it healthy all the time, providing you with actionable insights and reports for SharePoint Online and Office 365. Gain absolute control over your Office 365 tenant and review analytics and other intelligent data to maintain your environment secure. 

Within a single dashboard, you can analyze data related to __Users, Office 365 groups, OneDrive, MS Teams__ as well as __Security & Cleanup__. 

After successfully logging into the web application using your __Global SharePoint admin credentials__, the application will start retrieving and analyzing your Office 365 tenant settings.

Afterwards, when all the data are retrieved, on the __Dashboard__ screen, you will be able to explore various reports and settings for your Office 365 tenant and you will even be provided with the calculated score result. 

If certain types of errors occur during the load process, you’ll be able to review all the errors and their details. 

Some of the reports have a __lock icon__ displayed, which means that they are available in our other tool – __SysKit Security Manager__. Other reports that have the __Coming soon__ tag, will be available soon in SysKit Point.

### Let's get started 

On the __Total Users__ tile, you can see a list of all users found in your Office 365 tenant and their licensing status. 

On the __Access Requests__ tile, you can see a list of access requests for first five site collections along with information on the requested site, person and date. 

On the __Office 365 Groups__ tile, you can see a list all Office 365 groups found in your Office 365 tenant. Groups with associated Microsoft Teams are included as well. 

On the __External Users__ tile, you can see a list of all external users in the Office 365 tenant. These users have access to your SharePoint Online Sites, but are not licensed within your organization. 

Under the __External Sharing__ section, you can explore the following reports: 

+ __Anonymous Access Links__: Lists the content in the site collections that has been shared with an anonymous guest link, along with information on the link type, date created and expiration date. _Note: This report displays data only for the first five site collections._ 

+ __Site Collections with Enabled Anonymous Links__: Lists all site collections in your Office 365 tenant, which have anonymous links enabled. 

+ __Site Collections with Enabled External Sharing__: Lists all site collections in your Office 365 tenant, which have external sharing enabled, along with the sharing option that is allowed. 

+ __Users with Same Name__: List of external users who have identic usernames as users in the company. This situation can pose a potential security risk to your environment. _Note: This report is locked and available in the SysKit Security Manager._

Under the __Security__ section, you can explore the following reports: 

+ __Customized Default Permission Levels__: Lists all site collections where the permissions contained within the default permission levels are customized. 

+ __Site Collection Administrators__: Lists all site collection Administrators within a site collection, along with their login names. 

+ __Differences in Permission Levels__: Lists all site collections where the permission levels are different when compared to other site collections. This will compare whether the permission levels with the same name, have different permissions across the site collections. _Note: This report will be available soon in SysKit Point._ 

+ __Multi-Factor Authentication for Admins__: Lists all Office 365 administrator accounts who have multi-factor authentication disabled on the Office 365 tenant. This includes site collection Administrators and Global Administrators. _Note: This report will be available soon in SysKit Point._ 

Under the __Items with Unique Permissions__ section, you can find out which reports are available in the SysKit Security Manager and read description that is more detailed: 

> __Note!__ These reports are locked and available in the SysKit Security Manager. 

+ __Subsite__: Shows all subsites with unique permissions. Organize your content to take advantage of permissions inheritance. Consider segmenting your content by security level - create a site or a library specifically for sensitive documents. 

+ __Document Library__: Shows all document libraries with unique permissions. Organize your content to take advantage of permissions inheritance. Consider segmenting your content by security level - create a site or a library specifically for sensitive documents, rather than having them scattered in a larger library and protected by unique permissions. 

+ __List__: Shows all lists with unique permissions. Organize your content to take advantage of permissions inheritance. Consider segmenting your content by security level - create a site or a library specifically for sensitive documents. 

+ __List Item__: Shows all list items or folders with unique permissions. Organize your content to take advantage of permissions inheritance. Consider segmenting your content by security level - create a site or a library specifically for sensitive documents, rather than having them scattered in a larger library and protected by unique permissions. 

Under the __Cleanup__ section, you can explore the following reports: 

+ __SP Groups without Permissions__: Lists all SharePoint groups that have not been assigned any permissions. This will include groups with "Limited Access" that remain after they no longer have permissions for any specific item in the site collection. _Note: This report displays data only for the first five site collections._ 

+ __SP Groups with Disabled Owners__: Lists all SharePoint groups whose owners have been disabled in the Azure Active Directory. 

+ __SP Groups without Users__: Lists all SharePoint groups without any users. 

+ __Orphaned Users__: Lists all orphaned users. Orphaned users are users that are disabled or deleted in the Azure Active Directory but who had access to the tenant and can still be found in the site collection. 

+ __Site Collections with Disabled Administrators__: Lists all site collections in which the primary administrator (owner) or site collection administrator was disabled or deleted from the Azure Active Directory. 

+ __Identical SP Groups__: Lists all SharePoint groups with identical group members. This will only include groups that have more than one member. 

+ __Users without Permissions__: Lists all SharePoint users who have not been assigned to any SharePoint or Security group and to whom no permissions have been directly assigned. This will include users with "Limited Access" who remain even after they no longer have permissions for any specific item in the site collection. "Everyone" and "Everyone except external users" permissions are not evaluated in this report. _Note: This report is locked and available in the SysKit Security Manager._ 

Under the __OneDrive__ section, you can explore the following reports: 

+ __Total Disk usage__: You will see a graph of the OneDrive storage usage and the total amount of space available. 

+ __Number of OneDrive__: Lists all OneDrive found in your Office 365 tenant, along with their owners, OneDrive site URL and storage used in GB. 

+ __OneDrive Close to Quota Limit__: Lists all OneDrive which are close to exceeding the storage limit in the Office 365 tenant. It is highly recommended to manage the OneDrive Sites and keep an eye on how much space they’re using. If they’re getting close to the storage limit, advise the owners to free up some space. 

+ __Inactive OneDrive__: Lists all OneDrive that have not been accessed within the last 3 months. This will include any read, write or sync operation. 

+ __OneDrive Shareable Links__: Lists the content in the OneDrive Site that is shared to anyone with the link (previously referred to as "anonymous access links"), along with information on the link type, date created and expiration date. _Note: This report is locked and available in the SysKit Security Manager._ 

+ __Number of Files__: Lists all OneDrive and the number of items currently stored by each owner. This will include all files and folders. _Note: This report is locked and available in the SysKit Security Manager._ 

+ __Externally Shared Items__: Lists the content in the OneDrive Site that is shared with external users, along with information on their names and the permissions that they have on the content. _Note: This report is locked and available in the SysKit Security Manager._ 

Under the __Office 365 Groups & Teams__ section, you can explore the following reports: 

+ __Office 365 Groups__: Lists all Office 365 groups found in your Office 365 tenant. Groups with associated Microsoft Teams are included as well. 

+ __Microsoft Teams__: Lists all Microsoft Teams found in your Office 365 tenant. 

+ __Inactive Teams__: Lists all Microsoft Teams that have not been used within the last 3 months. _Note: This report will be available soon in SysKit Point._ 

+ __Inactive Groups__: Lists all Office 365 Groups that have not been used within the last 3 months. _Note: This report is locked and available in the SysKit Security Manager._ 

Under the __Point Results__ tile, you can explore the number of issues detected in your Office 365 tenant, upon which you can later take actions to improve the score and keep your environment healthy. 

### How the Point Results are calculated? 

SysKit Point figures out what Office 365 services you’re using (like OneDrive, SharePoint, and Microsoft Teams), then looks at your settings and activities and documents them through a set of reports and health checks established by SysKit. 

You’ll get a score based on the size of your Office 365 tenant and the sum of all the issues found there. After the score is recalculated, the reports used for the calculation will be highlighted in color. 


For detailed information on user permission requirements, see [this article](#internal/get-to-know-syskit-point/user-permission-requirements.md).