# Cowin-Notifier
Simple email notifier app to scrape the cowin portal for getting available vaccination slots for your age and pincode

### Usage
*   Generate an app password for your gmail application using steps given [here](https://support.google.com/accounts/answer/185833p=InvalidSecondFactorvisit_id=637554658548216477-2576856839&rd=1) (you might have to enable two-factor authentication for this)
*   Fill in the requisite details in the .env file
*   To start the application, run:
    ```bash
    npm i -g pm2
    npm i && pm2 start notify.js
    ```
*   To close the app, run: 
    ```bash
    pm2 stop notify.js && pm2 delete notify.js
    ```

**Please use this application responsibly. The portal might blacklist your IP as a DDoS source. Do stop the app when you get a slot**