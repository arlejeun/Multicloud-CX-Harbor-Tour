---
title: "EOD Personal deployment and setup"
chapter: true
weight: 20
---
![Title](/images/UserConfig.jpg)
## Objective

By the end of this section you will know how to deploy and setup Azure Environment on Demand (EOD) that will allow you to create a Personal environment in the Genesys Engage Cloud production tenant. You will be able to demonstrate cloud functionality in the same environment used by customers.


![Title](/images/UserConfig2-768x300.jpg)
## Deployment of your Azure EOD Personal Environment

1. Creating Your Configuration
 - Go to the navigation in GDemo and select "Environments" from the Genesys Engage Cloud menu.
 - You will create a configuration and define the settings.
 - Select Microsoft Azure as the Cloud Provider.
 - 
Azure

Select EOD Personal as the type of Environment that you want to provision, and then click "Create EOD Personal".



Complete the Properties page and click "Provision"..



It may take a few minutes to provision. This is normal.


>Each role in Genesys Cloud contains one or more permissions. The permissions allow users with that role to do >various tasks, such as create groups, set up integrations, and supervise contact center activity.

>The Employee role has the lowest level of permissions and is assigned to all users. This role cannot be removed. A >user must be assigned additional roles by a Genesys Cloud Administrator to have additional permissions.
>The Admin role has permissions to make any changes to a Genesys Cloud organization. This role is automatically >assigned to whoever sets up the organization. This person is responsible for inviting others to a Genesys Cloud >organization and for assigning roles to invitees.




Follow along 
**Associate Master Admin role to the user**
1.	Admin > People > **select your User Account**
2.	On the right side of the Roles screen, change “View:” from **Assigned** to **All**
3.	Assign **master admin** permissions and save the account

![Add Role](/images/RolesPic.png)

Create Role for Genesys Cloud Voice permissions
Admin > Roles / Permissions > Click **"Add Role"**
1.	Name the role-Ex: GCV user or something you can easily find
2.	Switch to the permissions tab on the right and search for **“PureCloud Voice”** in the Permission field
3.	Check the box for all permissions and save
4.	Return to People and select your user again 
5.	Go to the right side of the Roles screen and change "View" from **Assigned** to **All**
6. Assign the GCV user you just created to yourself

![Permissions](/images/Permission.png)

Add people to your organization
When you create new users, Genesys Cloud automatically sets their status as active whether you send the invitation now or later.

If you choose to send invitations to new users later and manually set their status to inactive, when you send the invitations Genesys Cloud automatically changes their status to active <br>
1.	Click Admin <br>
2.	Under People and Permissions, click People <br>
3.	Click Add Person. The Add People to the Organization dialog box opens <br>

