

# CONVERTING A WEBSITE TO AN IOS AND ANDROID APP GUIDELINE

This is the simplest way of converting your website into an IOS and Android app. Fistly you need to have a knowledge of XCODE and Android Studio/Intellij. Also you should have Cordova installed on your computer as explained in the website https://www.apache.cordova.org. You can use any of your websites to build both apps.

## GETTING STARTED

*First install cordova on your computer, in your terminal type npm install -g cordova(Windows) for the Mac type sudo npm install -g cordova. To test if cordoav is installed, type cordova in your terminal and follow the following steps to continue.

* On your terminal type sudo cordova create name of your app com.yourcompay/organisation.name of your app name of your app
in my case it will be sudo cordova create yourwebsite com.yourcompay/organisation.yourwebsite yourwebsite 
* Click enter on your terminal(enter password if asked)
* After project is created, cd <name of your app> in my case cd yourwebsite then click enter
* Then on your terminal type sudo cordova platform add ios android


### NEXT STEPS


* Next step is to go to your computer where your project was saved either Desktop or Development where ever you    keep them. Open your project and go to www folder, delete all the files that are there i.e CSS index.html JS and others.
* Replace those files with your own files of your website and save them.

* Now it is time to build your app, now type sudo cordova prepare
* In your terminal type sudo cordova build
* If your projects for both iOS and android were successfully built, you will get message 'BUILD SUCCESS'

* Next step is to go to IOS and double click on xcworkspace file and it will open your project in XCODE, you must have Xcode installed on your computer. Then run it and continue customising your Icons and so on.

* In Android Studio follow the same procedure as in IOS. Open your Android project in Android Studio and run it and customise it as per your wishes i.e changing Icons and so on.

* Then you have built an IOS and Android app for your website, you publish it as per your wishes.

