<div align="center">
<h1> Mōbile Security Cōursework 2 </h1>
ICT22Ø7 Mōbile Security Cōursework 2. Tweaking an Android app to improve its security.
</div>

<div>
<h1> Background </h1>
We are from Team <b>Survivors</b>. In this project we will be refining an Android application to enhance its security features. <br />
<br />
The scope of this project includes: <br />
1. Reverse engineering an Android application. <br />
2. Modify it to make at least one improvement to its security. <br />
3. Repackage the app for deployment. <br />
<br />
The Android application we have selected from Google Playstore is: <b> LibreTorrent </b>, a BitTorrent 2.0 app. <br />
</div>

## Pre-requisites
* Android Device, version 7.0 and above (≥ API level 24)
* Android Studio
* Android Debug Bridge (ADB)

The Original LibreTorrent app can be found here [LibreTorrent](https://play.google.com/store/apps/details?id=org.proninyaroslav.libretorrent&hl=en) on Google Playstore.

## Setup
1. Import the repository into Android Studio
> File > New > Import Project...
2. Build the application
> Make Project or Ctrl + F9
3. Upon successful Build, generate a signed APK
> Build > Generate Signed Bundle or APK > APK > Define keystore > Generate
4. Install the generated apk file on either emulator (x86) or Android Devices (ARM)
> adb install <apk_file>

## Enhanced Security Features
1. Screenshot Prevention
> Disabling screenshots in a mobile application can be a useful security improvement in certain situations, such as when the application handles sensitive information, contains copyrighted or proprietary material, or needs to comply with regulations.

2. Pin Authentication 
> Before the user uses the LibreTorrent app, the user will be prompted to enter his/her own password and it ensures that the user must have knowledge of the pin before having access to this application. 

3. Logging Application Last Usage
> Help detect unauthorised usage of the application. Application last usage date and time will be presented in a Toast message whenever user enters the application.
