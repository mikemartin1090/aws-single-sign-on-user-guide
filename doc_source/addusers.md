# Add users<a name="addusers"></a>

Users and groups that you create in your AWS SSO identity store are available in AWS SSO only\. Use the following procedure to add users to your AWS SSO identity store\. 

**To add a user**

1. Open the [AWS SSO console](https://console.aws.amazon.com/singlesignon)\.

1. Choose **Users**\.

1. Choose **Add user** and provide the following required information:

   1. **Username** – This user name will be required to sign in to the user portal and cannot be changed later\. It must be between 1 and 100 characters\.

   1. **Password** – Choose from one of the following choices to send the user's password\.

      1. **Send an email to the user with password setup instructions\.** – This option automatically sends the user an email addressed from Amazon Web Services\. The email invites the user on behalf of your company to access the AWS SSO user portal\.
**Note**  
All emails sent by the AWS SSO service will come from either the address [no-reply@signin.aws](no-reply@signin.aws) or [no-reply@login.awsapps.com](no-reply@login.awsapps.com)\. We recommend that you configure your email system so that it accepts emails from these sender email addresses and does not handle them as junk or spam\. 

      1. **Generate a one\-time password that you can share with the user\.** – This option provides you with the user portal URL and password details that you can manually send to the user from your email address\.

   1. **Email address** – The value you provide here must be unique\.

   1. **Confirm email address**

   1. **First name** – You must enter a name here for automatic provisioning to work\. For more information, see [Automatic provisioning](provision-automatically.md)\.

   1. **Last name** – You must enter a name here for automatic provisioning to work\.

   1. **Display name**
**Note**  
\(Optional\) You can provide additional attributes such as **Employee number** and **Office 365 Immutable ID** to help map the user's identity in AWS SSO with certain business applications that the user needs to use\. 

1. Choose **Next**\.

1. Select one or more groups that you want the user to be a member of\. Then choose **Next**\.

1. Review your information from **Step 1: Specify user details** and **Step 2: Add user to groups \- optional**\. Choose **Edit** by either step to make any changes\. Once you are satisfied with what you have entered in Step 1 and Step 2, choose **Add user**\.