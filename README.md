# Convert-any-website-to-IOS-and-Android-with-Cordova

This is a simplest and very convenient way of converting your website to and iOS and Android app and even Publish it. I have used my own website  https://www.artificialintellidev.com to convert it to both IOS and Android apps. All you need as a Developer is to know how to use Android Studio/Intellij and Xcode. Also you need to have cordova installed on your computer as explained on the website https://www.apache.cordova.org.

#GETTING STARTED

On terminal create a cordova project:
type sudo cordova create <name of your app> com.yourdomain.<name of your app> <name of your app>
	in my case i will type sudo cordova create artificialdev com.artificialintellidev.artificialdev artificialdev
	 then you click enter on terminal 
	
	After project is created type cd <name of your app>
	in my case cd artificialdev then click enter on terminal
	
	#Next step is to build your project
	First you need to add platforms you want to create your app on:
	In terminal type sudo cordova platform add ios android
	
	After running you will get message 'project created successfully' now you have added IOS and Android.
	Then you need to build your project,
	In terminal type sudo cordova prepare
	After that, type sudo cordova build
	
	When your project is successfully build you will get the message 'BUILD SUCCEEDED' on your terminal.
	
#NEXT STEPS
	
	The next step is to go to where your project is saved on your computer that is Desktop or Development:
	Open the project and go to www folder, that is where you will find the default files index.html CSS JS and others 
	delete all of them. And replace them with your own website files.Then save them. 
	
	You can now open your ios project in XCODE and Android in ANdroid Studio/Intellij and run them.
	
	XCODE you can just double click on xcworkspace file and it will open your project on XCODE(Have it installed on your
	computer. Then you can run and test your app. 
	
	Android Studio/Intellij still follow the same procedure as in XCODE. Open your project and run it.
	
	And continue adding your Icons and so on,...


