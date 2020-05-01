# About Identities and Access

The Identity & Access Management page defines the users allowed to access the portal and the permissions to view and/or configure portal settings.


## What are Users?

Anyone who can log in to and be authenticated by the CDN360 portal is a user.


## What are Permissions?

The ability for users to perform actions within the portal is governed by permissions. Each permission has an intuitive name that describes its purpose. For example, certificate.create allows certificates to be created. A user must be granted a permission to perform the corresponding action in the portal.


## What are Roles?

Rather than assigning individual permissions directly to every portal user, permissions are grouped into roles. A role is a collection of users who share the same permissions. When you add a role, you specify a name for the role, select the permissions associated with the role, and then select the users who will be granted those permissions.

Initially, the portal provides three default roles: Admin, Operator, and Viewer.

- Admin can view and make changes to all settings available in the portal.
- Operator can view and make changes to all portal settings, except users and roles.
- Viewer has read-only permission and cannot change any portal settings.

## Identity & Access Management Page

To display the Identity & Access Management page, click your initials at the top right of the portal, and then select **Identity & Access Management**.

![null](</docs/resources/images/Selecting the Identity and Access Management Page.png>)

The following figure shows the key elements on the page, and the table following the figure describes them.

![null](</docs/resources/images/Identity & Access Management Page.png>)


| **Fields** | **Description** |
| :----------: | --------------- |
| 1 | Identity and access management tasks are organized into four tabs:<ul><br> <li>**Users** allows administrators to manage users. Operators and viewers are limited to seeing other portal users. This is the tab that appears when the Identity & Access Management page appears. <li>**Roles** allows administrators to manage roles. Operators and viewers are limited to seeing roles. <li>**Audit Logs** allows administrators to manage audit logs. This tab is not available to operators and viewers. <li>**Security**   allows administrators to define security for the portal. This tab is not available to operators and viewers.|
| 2 | To filter users on the **Users** tab or roles on the **Roles** tab, type characters in this field and then press the Enter key. All properties that do not contain the typed characters are hidden. Filtering is not case-sensitive. To remove the filter, click the **Reset** button.|
| 3 | Each user or role appears on a row within its respective tab.|
| 4 | The **Actions** drop-down list on each row has options appropriate for each tab|
| 5 | The **Users** tab has an **+ Add User** button that allows administrators to create new users. Similarly, the **Roles** tab has an **+ Add Role** button that allows administrators to [create new roles](<docs/portal/../../managing-roles.md>). These buttons do not appear for viewers.|

