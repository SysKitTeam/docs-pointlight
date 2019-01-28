---
title: User Permission Requirements
description: >-
  This article discusses the user permission requirements that are necessary in
  order to successfully use SysKit Point.
author: Andrea Budiša
date: 05/12/2018
---

# User Permission Requirements

In order to utilize the reporting options in SysKit Point, you need to use an account with **Global SharePoint Online Administrator** privileges.

## Why does SysKit Point need consent from a global administrator?

To achieve its functionality, SysKit Point is registered as an Azure Active Directory Application. Azure Active Directory Applications can use other resources from Azure. To use these resources the user running the web application must consent to the permissions that the application requires.

When a global administrator uses SysKit Point he will go through the normal consent flow where a popup with the Microsoft consent page is shown.

## What permissions does SysKit Point require?

SysKit Point requires the following delegated permissions:

* Have full control of all site collections 
* Read all usage reports 
* Read all users' full profiles 
* Read all groups 
* Read directory data
* Read items in all site collections 
* Access your data anytime 

Granting delegated permissions to an application means that the application may act on behalf of a user. This means that the **effective permissions that the user has are still limited by his own permissions**.

## Additional Info

If you at any time decide to revoke the given consent, you can do so by:

1. Go to [Microsoft Azure portal](https://portal.azure.com/).
2. Select **Azure Active Directory**. 
3. Select **Enterprise Applications**. 
4. Select **SysKit Point**.

