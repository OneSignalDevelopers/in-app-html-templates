# SMS + Email Form Template

This HTML template will let you request email addresses and phone numbers from users and create new SMS and Email players out of them. You will need to add your Onesignal App ID into this template at the appropriate place.

###### SMS Email form on Android
![Screenshot](assets/sms_email_form.png)

## Safe Area (notch) Detection
Certain mobile devices may have safe areas where operating system icons or a camera notch might exist. Our Onesignal SDK detects these areas and exposes them to the iam's HTML document via `safe-area-inset-*` CSS variables :point_down:

https://github.com/OneSignalDevelopers/iam-html-templates/blob/00e30f0240e22f2e72ae807ac9274c3d0ab97bc8/sms_email_form/index.html#L21-L31

## E.164-formatted Phone Numbers
Our REST API requires [E.164-formatted phone numbers](https://support.twilio.com/hc/en-us/articles/223183008-Formatting-International-Phone-Numbers). To make this easier we are using the [intl-tel-input](https://github.com/jackocnr/intl-tel-input) library.
