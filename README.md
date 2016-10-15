# About
This is an Android Studio Project for showing a message in the screen through JNI.

#Getting Started
* Download the latest [NDK](https://developer.android.com/ndk/index.html);
* Enable the command `javah` to be used from console.

#Compiling
 * This version is coded to run on `armeabi-v7a` architecture;
 * You need to change the build.gradle  `commandLine "C:/android-ndk-r12b/ndk-build.cmd",` and 
 local.properties `ndk.dir=C\:\\android-ndk-r12b` to your current NDK folder.
