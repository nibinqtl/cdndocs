# Editing a CNAME

1. In the left pane, click **CNAMEs**.
2. Click the CNAME you want to edit 
   <br><U>OR </u></br>
   Click the **Actions** drop-down list for the CNAME you want to edit, and then select **Edit**.<br><br>
3. At the top right of the page, click the **Edit** button.

![null](</docs/resources/images/Edit CNAME - Edit Button.png>)

The CNAME form that appears allows you to create, edit, and delete client region rules, and change advanced settings. Refer to the appropriate steps below.
![null](</docs/resources/images/Editing CNAME Form.png>)

4. To create one or more client region rules, perform the following steps.

**Note**: If you do not create a client region rule, or if you leave the **Client Region** field empty, a rule covering ALL regions is created automatically.

<ul>a. At the top right of the page, click the <strong>Create Client Region Rule</strong> button.

![null](</docs/resources/images/Create Client Region Rule Button.png>)

b. Complete all the fields, and then click the **Create Client Region Rule** button.
c. To add more client region rules, repeat this step for each additional rule.

![null](</docs/resources/images/Create Client Region Rule.png>)

| **Fields**        | **Description**                                            |
| ----------------- | ---------------------------------------------------------- |
| Client Region     | Select a region for this rule. If you leave this field empty, a rule covering ALL regions is created automatically.|
| Client ISP        | Select a client ISP.                                       |
| Action Type       | Select the type of action to be performed. Choices are:<br><li><strong>Deliver</strong> = specifies the server groups to deliver your traffic. Only one deliver action is allowed for each client region. All servers in the selected server group will be used as candidates in the load balancing algorithm.<li><strong>Redirect</strong> = directs traffic requests to the target specified in the Redirect target field (see below). This can be your origin site or another CDN provider. There can be multiple redirect actions for each client region.<li><strong>Reject</strong> = directs traffic requests to web servers that always respond with a 403 - forbidden error message. Only one reject action is allowed for each client region.</br>                                   |
| Server Group      | If <strong>Action Type</strong> is set to <strong>Deliver</strong>, select one or more server group options:<br><li><strong>Standard</strong> = standard server group.</li><li><strong>Premium</strong> = includes the standard server group.<li><strong>Premium+</strong> = includes the standard and premium server groups.<li><strong>Ultra</strong> = includes the standard, premium, and premium+ server groups.                                                                          |
| Redirect Target   | If <strong>Action Type</strong> is set to **Redirect**, specify an IP address or hostname to which CDN360 will redirect your traffic.|
| Weight | Adjust how this rule behaves relative to other rules for the same client region.                                      

5. To edit an existing client zone rule:
<ul>a. Click the <strong>Actions</strong> drop-down list next to the rule you want to edit, and then select <strong>Edit</strong>.<br><br></ul>
<<screen here>>??
<ul>b. Make your changes in the Update Client Zone Rule dialog box (for assistance, see the table above).<br><br></ul>
<ul>c. Click the <strong>Update Client Zone Rule** button.</strong></ul>

figure here??

6. To delete a client region rule:

<ul>a. Click the <strong>Actions</strong> drop-down list next to the rule you want to delete, and then select <strong>Delete</strong>.</ul>

![null](</docs/resources/images/CNAME Delete.png>)

<ul>b. When prompted to confirm the deletion, click <strong>OK</strong> to delete the client region rule.</ul><br>

7. To change the Has Beian setting, expand **Advanced Settings** and make your change.

![null](</docs/resources/images/CNAMEs - Advanced Settings.png>)

| **Fields**      | **Description** |
| --------------- | --------------- |
| Has Beian       |      Select whether content will be served from PoPs inside or outside China. Choices are: <br><li><strong>No</strong> = content is served to website visitors in China from PoPs located outside China. (*default*) <li><strong>Yes</strong> = content is served to website visitors in China from PoPs located in China.</li></br>|

8. Click **Update**.
9. When a message confirms that the CNAME was updated click **OK**.
10. Click **Close** to return to the main page.

