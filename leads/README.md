# Leads Form Template (sms+email)

Gather leads through an in-app message. This in-app message template allows you to collect free-form input from users. With this template, you can capture a user’s phone number, email, and permission to contact them so that you can communicate with them through other channels such as email and SMS. This template is currently set up to send emails and phone numbers to your OneSignal user list through the OneSignal Rest API.

Other details can also be collected and used as tags to better segment users.

Lead forms are most effective in capturing data when shown to users at an “aha moment” of the user experience.

<img alt="SMS + Email Form Screenshot" src="readme_assets/sms_email_form.png" width="250px" />

## About This Template

This HTML template will let you request email addresses and phone numbers from users and submit requests the the Onesignal REST API to create new SMS and Email players out of them.

https://github.com/OneSignalDevelopers/in-app-html-templates/blob/db2d3e784ff8639335ea9560241212c2d8151909/sms_email_form/index.html#L215.

You will need to add your Onesignal App ID into this template on this line

<img alt="SMS + Email Form Animation" src="readme_assets/sms_email_form.gif" width="250px" />

## E.164-formatted Phone Numbers

Our REST API requires [E.164-formatted phone numbers](https://support.twilio.com/hc/en-us/articles/223183008-Formatting-International-Phone-Numbers). To make this easier we are using the [intl-tel-input](https://github.com/jackocnr/intl-tel-input) library.
