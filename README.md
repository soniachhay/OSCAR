# OSCAR EMR projects (scripts and PHI redacted)

### 1. Display healthcard status on demo page:

When opening the demo page for a patient on OSCAR, it will automatically grab the info (renew date, status, message) from the card swipe page and update it on the demo page (works for missing version codes too)

![image](https://user-images.githubusercontent.com/46382421/195668668-31e3cbc0-33dd-4a7c-8079-72b72c52839a.png)

![image](https://user-images.githubusercontent.com/46382421/195668695-17242dcb-e015-471c-bb93-ed9f5b851d84.png)


### 2. Display healthcard status on eChart + blink alert:
- Shows the healthcard status in the echart header & includes renew date
- It will display valid HC (green), valid but expired HC (yellow), invalid or no HC (red) -> also differentiates if patient is IFH
- Alert if no healthcard on record
- Version code status (e.g. INVALID) will blink 5 times if HC is invalid/valid but expired/missing

![image](https://user-images.githubusercontent.com/46382421/195669161-c2fe6661-9341-43e4-927d-7ff0fa3c0eb8.png)


### 3. Compose email on eChart + autopopulate:
- Allows user to compose email on echart/use templates provided in OSCAR and send with default email client
- Autopopulates subject and content of email using template format
- Ability to edit notes on echart + send email with those changes
- Email button only appears on echart notes with email template to ensure only the info that should be sent, can be sent

![image](https://user-images.githubusercontent.com/46382421/195669334-64e9fb18-7e2e-4dbc-ace9-440c72cf264b.png)

Email with no changes made to template:

![image](https://user-images.githubusercontent.com/46382421/195669388-d90abc9c-534e-4909-ae46-63a482b4bb19.png)
