Prerequisite:-
Step-1: You will need to have Node.js installed on your machine. (Recommended version 16 or above)
Step-2: You will need to have NPM installed on your machine.
Step-3: Create a simple test folder by running following cmd: $ mkdir webdriverio-test
Step-4: Install & configure WebdriverIO by running following cmd in the new directory which is created (webdriverio-test): npm init wdio .
Step-5: While configuring **Mocha framework** should be installed & base url : **https://device.pcloudy.com/quickappium/wd/hub**
Step 6: Copy the *wdio.android.parallel.conf.js* file and *test* directory in the new directoy *webdriverio-test* and remove *wdio.conf.js*
Step-7: Enter your <MailId> in ***pCloudy_Username="Enter your Email-id"*** in "wdio.android.parallel.conf.js".
Step-8: Enter your <ApiKey> in ***pCloudy_ApiKey="Enter your API Key"*** in "wdio.android.parallel.conf.js".
Step-9: Run the script with the following cmd: ***npx wdio run ./wdio.android.parallel.conf.js***
Step-10: Optional Capabilities : Can choose anyone of the below-:
Option1: pCloudy_DeviceManafacturer
Option2: pCloudy_DeviceVersion
Option3: pCloudy_DeviceFullName

