# Getting started

## Setting up your workshop development environment
This workshop is aimed at the intermediate Java or OO programmer who wants to start with native Android development. As a prerequisite, please set up a working Android development environment. Please check if you have already installed&mdash;and if not, download and install&mdash;the following software on your computer:

* A [Java Software Development Kit (JDK)](http://www.oracle.com/technetwork/java/javase/downloads/index.html), version 7 is recommended. We advise against using JDK 8 for this workshop. For one since it's not supported :-P On a Mac you need a Java Runtime Environment (JRE) version 6 to be able to run Android Studio. Note: A Java Runtime Environment (JRE) is not enough to do Android development, you need that Java SDK!
* The [Android Studio](http://developer.android.com/sdk/installing/studio.html) bundle, which includes: 
  * The Android Studio IDE, which is based on the community edition of IntelliJ IDEA. 
  * All the Android SDK Tools to design, test, debug, and profile your app. 
  * The latest Android platform to compile your app. 
  * The latest Android system image to run your app in the emulator
* **(Optional)** A [Git](http://git-scm.com/downloads) client or command line tool to clone the workshop repository. [Sourcetree](http://www.sourcetreeapp.com/) is a pretty cool Git GUI client. If you don't have an internet connection, or don't want the hassle of working with Git, you can get (or download) a zip-file with the repository contents on the day of the workshop.

![Android Studio Check for updates](img/android-studio-check-for-updates.png)

* After you have installed **Android Studio** you might need to update to the latest version. Click on “Android Studio” on a Mac or in the “File” menu on Windows and Linux and select “Check for Updates…”. We will use version 1.1.0 of Android Studio for this workshop.
* Fire up Android Studio and check that you have the latest **Tools**, **Android platform** and **Extras** installed. You can access the SDK manager by clicking on the SDK Manager Icon ![SDK Manager Icon](img/sdk-manager-studio.png) in the toolbar. Your configuration should look something like this

![SDK Tools](img/sdk-tools.png)
> You only need the latest versions of the **Tools**, **Platform-tools** and **Build-tools**

![Android 5.1.1 (API 22)](img/sdk-android-api-22.png)
> Select the packages that are selected in the screenshot. If you don't have an Android device install one of the Intel Atom images so you can create an emulator later on. If you have enough hard disk space simply click the checkbox before the **Android 5.1.1 (API 22)** folder to select and download everything.

![Extras](img/sdk-extras.png)
> Simply install everything in the **Extras** section for the workshop. FYI The **Google USB Driver** is only compatible with Windows machines. So install that if you run Android Studio on windows and want to connect your dev phone via a USB cable.

* If you have selected all the packages above click the “Install Packages” button and sit tight.
* Preferably we would like you to connect your phone to your computer and run and test the samples on a real device. If you don't own an Android device you can install an Android emulator, also known as an Android Virtual Device (AVD). Install at least one Android Virtual Device (AVD) running Lollipop for this workshop. All the capabilities of the AVD Manager are accessible directly from the Android Studio interface. Click the AVD Manager Icon ![AVD Manager Icon](img/avd-manager-studio.png) in the toolbar to open it and create new AVDs. **Note: If you connect your Android device to a Windows machine make sure you have installed the correct device driver for your Android device. If you have ever successfully connected your Android device to your PC you probably already have it.**

##Connecting your device to Android Studio

### USB Debugging

![USB Debugging](img/usb-debugging.png)

If you want to run apps on your device the first thing you need to do is enable **USB debugging** on the device itself (by starting the Settings app on your device and selecting **Developer Options | USB Debugging**). If you don't see the developer options item in your settings menu and you are running Android 4.0 (Ice Cream Sandwich) or higher you can enable them by clicking on the **Settings | About Phone | Build** item a couple of times to enable them. If you run an older Android version the USB Debugging checkbox might reside in the Applications section of your settings. 

### Unknown Sources

![Unknown Sources](img/unknown-sources.png)

You must also allow installation of apps from sources other than the Play Store by checking Unknown Sources in the security settings (on most phones). Now it’s simply a matter of plugging in your phone and running the Android application by clicking the run button in Android Studio

If you've installed all the necessary development kits described above you are all set for the workshop!

##Let's go!

You may want to keep this [cheatsheet](cheatsheet.md) at hand. Now let's [go to lesson 1](section1)!