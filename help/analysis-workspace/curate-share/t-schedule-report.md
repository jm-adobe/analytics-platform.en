---
description: Send an Analysis Workspace project via email or schedule it for delivery.
keywords: Analysis Workspace
title: Schedule projects
feature: Curate and Share
mini-toc-levels: 3
exl-id: 36b5133a-2cd3-4cf1-a6fa-93a02dba276a
---
# Schedule projects

From the Workspace **[!UICONTROL Share]** menu, you can send Analysis Workspace projects via email to selected recipients. Files can be sent in CSV or PDF format. 

## Send file now {#now}

To send a file immediately to recipients via email:

1. Click **[!UICONTROL Share] > [!UICONTROL Export file]**.
1. Specify the file type:
   * [!UICONTROL **CSV**]: Choose this option if you want plain-text data.
   * [!UICONTROL **PDF**]: Choose this option if you want the downloaded file to contain all the displayed (visible) tables and visualizations in the project.
1. (Optional) Add a description to include in the email to explain the file being received. 
1. Add recipients or groups. Email addresses can also be entered. 
1. (Only for Healthcare Shield customers) Provide a password. See the section Password-protect a scheduled report. 
1. Click **[!UICONTROL Send Now]**.
1. (Optional) Click **[!UICONTROL Show scheduling options]** to specify a delivery schedule.

![Send file now](assets/send-file-no-scheduling-options.JPG)

## Send file on schedule {#schedule}

To send a file on a recurring schedule to recipients via email:

1. Click **[!UICONTROL Share] > [!UICONTROL Schedule file export]**.
1. Specify the file type (CSV or PDF).
1. (Optional) Add a description that will be included in the email to explain the file being received. 
1. Add recipients or groups. Email addresses can also be entered. 
1. (Only for Healthcare Shield customers) Provide a password. See the section Password-protect a scheduled report. 
1. Specify the range the schedule should be delivered over by modifying Starting on and Ending on inputs. The end date must be within a year from the day the schedule is created or modified.
1. Specify the delivery frequency. Each frequency allows for different customizations. 
1. Click **[!UICONTROL Send on schedule]**.

![](assets/send-file.JPG)

## Scheduled Projects manager {#manager}

Scheduled Analysis Workspace projects can be managed under **[!UICONTROL Analytics] > [!UICONTROL Components] > [!UICONTROL Scheduled Projects]**.

For more information, see [Scheduled projects](/help/components/scheduled-projects-manager.md)

## Password-protect a scheduled project {#password}

>[!NOTE]
>
>The option to password-protect a scheduled project appears only for Customer Journey Analytics customers who have purchased the [Healthcare Shield](https://business.adobe.com/solutions/experience-cloud-for-healthcare.html) add-on product. 

Adobe uses the password to encrypt scheduled projects, whether they are sent in .pdf or .csv formats.

After your company has purchased the Healthcare Shield SKU and has been enabled for it, the prompt to create a password for a scheduled project pops up under two circumstances:

* When someone creates a new scheduled project.

* When an existing scheduled project is about to be sent. The currently scheduled project will be disabled until password protection is in place. The owner of the scheduled project will receive an email to this effect. 

![password protection](assets/password.png)

### Password requirements

The password requirements conform to the Adobe standard, requiring a minimum of 8 characters with at least one number and one special character. 

### Password-protect a new scheduled project

1. After you have saved your project, go to **[!UICONTROL Share]** > **[!UICONTROL Send file now]**, or [!UICONTROL Share] > **[!UICONTROL Send file on schedule]**.
1. Follow the instructions above, under [Send file now](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-workspace/curate-share/t-schedule-report.html#now) or [Send file on schedule](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-workspace/curate-share/t-schedule-report.html#schedule).

### Password-protect an existing scheduled project 

Prior to the time for which a project is scheduled, the project's owner will receive an email similar to this:

![email](assets/email-password.png)

1. Log back into Customer Journey Analytics.
1. Click **[!UICONTROL View Scheduled Project]**.
1. In the **[!UICONTROL Edit scheduled project]** dialog, enter and re-enter a password.
1. Let (only) the recipients of the scheduled project know about this password.


