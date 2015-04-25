ORIGIN
======

The origin of this repostiroy, or a.k.a., the "upstream" of this repository, is:
git@github.com:googlesamples/android-BluetoothChat.git

This is the readme file by zerox
================================

Date: 2015-04-25

Nothing to be generated yet.

The intention of this project is to:

1.  Learn the Android Studio way to develop an Android application.
2.  Learn the Android way to use the Bluetooth for connectivity, preferrably
    employing the Bluetooth Low Energy feature.

To build it on Windows
======================

1.  Install JDK 1.7
2.  Open cmd at top-level (i.e., the parent directory of this file), I will
    mention the "top-level" directory as build home hereafter.
3.  Create `local.properties' at the build home, "example-local.properties"
    file here is for your reference, you just put your Android SDK path in
	it
4.  set JAVA_HOME, e.g.,

    set JAVA_HOME=C:\Program Files\Java\jdk1.7.0_75

5.  Execute this:

    gradlew build

6.	The first run will take a lot of time because the building system will need
    to download "gradle".  While anyway thereafter build will still be slow (may
    take 5 seconds or so) because IT IS JAVA!
