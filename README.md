# In-app Messaging HTML Templates
 HTML Templates for in-app messaging
 
For more information on how to build HTML In-App Messages view our [documentation](https://documentation.onesignal.com/docs/design-your-in-app-message-with-html#key-features-with-the-in-app-html-editor) here.

## Templates

###### [Leads (SMS + Email)](./sms_email_form/README.md)
<img alt="Leads" src="./sms_email_form/readme_assets/sms_email_form.gif" width="200px">

###### [Survey (Ranking 1-5)](./ranking_survey/README.md)
<img alt="Survey" src="./ranking_survey/readme_assets/ranking_survey_iam.gif" width="200px">

###### [Carousel](./carousel/README.md)
<img alt="Carousel" src="./carousel/readme_assets/carousel_iam.gif" width="200px">

###### [Promo Wheel](./promo_wheel/README.md)
<img alt="Promo Wheel" src="./promo_wheel/readme_assets/promo_wheel_iam.gif" width="200px">

### Safe Area (notch) Detection
Certain mobile devices may have safe areas where operating system icons or a camera notch might exist. Our Onesignal SDK detects these areas and exposes them to the iam's HTML document via `safe-area-inset-*` CSS variables :point_down:

https://github.com/OneSignalDevelopers/iam-html-templates/blob/00e30f0240e22f2e72ae807ac9274c3d0ab97bc8/sms_email_form/index.html#L21-L31
