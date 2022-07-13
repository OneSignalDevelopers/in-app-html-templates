# SMS + Email Form Template

This HTML template will let you request email addresses and phone numbers from users and create new SMS and Email players out of them. You will need to add your Onesignal App ID into this template at the appropriate place.

###### SMS Email form on Android
![Screenshot](readme_assets/sms_email_form.gif)

## E.164-formatted Phone Numbers
Our REST API requires [E.164-formatted phone numbers](https://support.twilio.com/hc/en-us/articles/223183008-Formatting-International-Phone-Numbers). To make this easier we are using the [intl-tel-input](https://github.com/jackocnr/intl-tel-input) library.
