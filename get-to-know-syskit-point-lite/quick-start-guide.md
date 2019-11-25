# Quick Start Guide

In this article, we will take you through some of the common use cases and usual steps when accessing the application for the first time. We have provided you with an overview of the entire application and how to use it. For detailed information on particular features, please explore our other articles.

Get started with SysKit Point Lite - a free cloud-based solution for SharePoint Online and Office 365. It was created to help Global Administrators in Office 365 with controlling the security and gaining intelligent data for their environment.

Within a single dashboard, you can analyze data related to **Users, Office 365 groups, OneDrive, MS Teams** as well as **Security & Cleanup**.

After successfully logging into the web application using your **Global SharePoint admin credentials**, the application will start retrieving and analyzing your Office 365 tenant settings.

Afterwards, when all the data are retrieved, on the **Dashboard** screen, you will be able to explore various reports and settings for your Office 365 tenant and you will even be provided with the calculated score result.

If certain types of errors occur during the load process, you’ll be able to review all the errors and their details.

Some of the reports have a **lock icon** displayed, which means that they are available in our other tool – **SysKit Security Manager**. Other reports that have the **Coming soon** tag, will be available soon in SysKit Point Lite.

### Let's get started

On the **Total Users** tile, you can see a list of all users found in your Office 365 tenant and their licensing status.

On the **Access Requests** tile, you can see a list of access requests for first five site collections along with information on the requested site, person and date.

On the **Office 365 Groups** tile, you can see a list all Office 365 groups found in your Office 365 tenant. Groups with associated Microsoft Teams are included as well.

On the **External Users** tile, you can see a list of all external users in the Office 365 tenant. These users have access to your SharePoint Online Sites, but are not licensed within your organization.

Under the **External Sharing** section, you can explore the following reports:

* **Anonymous Access Links**: Lists the content in the site collections that has been shared with an anonymous guest link, along with information on the link type, date created and expiration date. _Note: This report displays data only for the first five site collections._
* **Site Collections with Enabled Anonymous Links**: Lists all site collections in your Office 365 tenant, which have anonymous links enabled.
* **Site Collections with Enabled External Sharing**: Lists all site collections in your Office 365 tenant, which have external sharing enabled, along with the sharing option that is allowed.
* **Users with Same Name**: List of external users who have identical usernames as users in the company. This situation can pose a potential security risk to your environment. _Note: This report is locked and available in the SysKit Security Manager._

Under the **Security** section, you can explore the following reports:

* **Customized Default Permission Levels**: Lists all site collections where the permissions contained within the default permission levels are customized.
* **Site Collection Administrators**: Lists all site collection Administrators within a site collection, along with their login names.
* **Differences in Permission Levels**: Lists all site collections where the permission levels are different when compared to other site collections. This will compare whether the permission levels with the same name, have different permissions across the site collections. _Note: This report will be available soon in SysKit Point Lite._
* **Multi-Factor Authentication for Admins**: Lists all Office 365 administrator accounts who have multi-factor authentication disabled on the Office 365 tenant. This includes site collection Administrators and Global Administrators. _Note: This report will be available soon in SysKit Point lite._

Under the **Items with Unique Permissions** section, you can find out which reports are available in the SysKit Security Manager and read description that is more detailed:

{% hint style="warning" %}
**Note!** These reports are locked and available in the SysKit Security Manager.
{% endhint %}

* **Subsite**: Shows all subsites with unique permissions. Organize your content to take advantage of permissions inheritance. Consider segmenting your content by security level - create a site or a library specifically for sensitive documents.
* **Document Library**: Shows all document libraries with unique permissions. Organize your content to take advantage of permissions inheritance. Consider segmenting your content by security level - create a site or a library specifically for sensitive documents, rather than having them scattered in a larger library and protected by unique permissions.
* **List**: Shows all lists with unique permissions. Organize your content to take advantage of permissions inheritance. Consider segmenting your content by security level - create a site or a library specifically for sensitive documents.
* **List Item**: Shows all list items or folders with unique permissions. Organize your content to take advantage of permissions inheritance. Consider segmenting your content by security level - create a site or a library specifically for sensitive documents, rather than having them scattered in a larger library and protected by unique permissions.

Under the **Cleanup** section, you can explore the following reports:

* **SP Groups without Permissions**: Lists all SharePoint groups that have not been assigned any permissions. This will include groups with "Limited Access" that remain after they no longer have permissions for any specific item in the site collection. _Note: This report displays data only for the first five site collections._
* **SP Groups with Disabled Owners**: Lists all SharePoint groups whose owners have been disabled in the Azure Active Directory.
* **SP Groups without Users**: Lists all SharePoint groups without any users.
* **Orphaned Users**: Lists all orphaned users. Orphaned users are users that are disabled or deleted in the Azure Active Directory but who had access to the tenant and can still be found in the site collection.
* **Site Collections with Disabled Administrators**: Lists all site collections in which the primary administrator \(owner\) or site collection administrator was disabled or deleted from the Azure Active Directory.
* **Identical SP Groups**: Lists all SharePoint groups with identical group members. This will only include groups that have more than one member.
* **Users without Permissions**: Lists all SharePoint users who have not been assigned to any SharePoint or Security group and to whom no permissions have been directly assigned. This will include users with "Limited Access" who remain even after they no longer have permissions for any specific item in the site collection. "Everyone" and "Everyone except external users" permissions are not evaluated in this report. _Note: This report is locked and available in the SysKit Security Manager._

Under the **OneDrive** section, you can explore the following reports:

* **Total Disk usage**: You will see a graph of the OneDrive storage usage and the total amount of space available.
* **Number of OneDrive**: Lists all OneDrive found in your Office 365 tenant, along with their owners, OneDrive site URL and storage used in GB.
* **OneDrive Close to Quota Limit**: Lists all OneDrive which are close to exceeding the storage limit in the Office 365 tenant. It is highly recommended to manage the OneDrive Sites and keep an eye on how much space they’re using. If they’re getting close to the storage limit, advise the owners to free up some space.
* **Inactive OneDrive**: Lists all OneDrive that have not been accessed within the last 3 months. This will include any read, write or sync operation.
* **OneDrive Shareable Links**: Lists the content in the OneDrive Site that is shared to anyone with the link \(previously referred to as "anonymous access links"\), along with information on the link type, date created and expiration date. _Note: This report is locked and available in the SysKit Security Manager._
* **Number of Files**: Lists all OneDrive and the number of items currently stored by each owner. This will include all files and folders. _Note: This report is locked and available in the SysKit Security Manager._
* **Externally Shared Items**: Lists the content in the OneDrive Site that is shared with external users, along with information on their names and the permissions that they have on the content. _Note: This report is locked and available in the SysKit Security Manager._

Under the **Office 365 Groups & Teams** section, you can explore the following reports:

* **Office 365 Groups**: Lists all Office 365 groups found in your Office 365 tenant. Groups with associated Microsoft Teams are included as well.
* **Microsoft Teams**: Lists all Microsoft Teams found in your Office 365 tenant.
* **Inactive Teams**: Lists all Microsoft Teams that have not been used within the last 3 months. _Note: This report will be available soon in SysKit Point Lite._
* **Inactive Groups**: Lists all Office 365 Groups that have not been used within the last 3 months. _Note: This report is locked and available in the SysKit Security Manager._

Under the **Point Lite Results** tile, you can explore the number of issues detected in your Office 365 tenant, upon which you can later take actions to improve the score and keep your environment healthy.

### How the Point Lite Results are calculated?

SysKit Point Lite figures out what Office 365 services you’re using \(like OneDrive, SharePoint, and Microsoft Teams\), then looks at your settings and activities and documents them through a set of reports and health checks established by SysKit.

You’ll get a score based on the size of your Office 365 tenant and the sum of all the issues found there. After the score is recalculated, the reports used for the calculation will be highlighted in color.

For detailed information on user permission requirements, see this article: 

{% page-ref page="../requirements/user-permission-requirements.md" %}

