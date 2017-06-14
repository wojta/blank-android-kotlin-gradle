# blank-android-kotlin-gradle
Author: Vojtěch Sázel (vsazel@redhat.com)   
Level: Beginner   
Technologies: Java, Kotlin, Android,  RHMAP   
Summary: A template application which Initializes FeedHenry in a Fragment written in Kotlin (unofficial)   
Community Project : [Feed Henry](http://feedhenry.org)   
Target Product: RHMAP   
Product Versions: RHMAP 3.8.0+   
Source: https://github.com/wojta/blank-android-kotlin-gradle   
Prerequisites: fh-android-sdk : 3.0.+, Android Studio : 2.3.x or newer, Android SDK : 24 or newer   

## What is it?

This application provides a starting point for developing RHMAP applications in Kotlin instead of Java. The FeedHenry SDK is initialized in the class `app/src/main/kotlin/org/feedhenry/blank/InitFragment.kt`.

If you do not have access to a RHMAP instance, you can sign up for a free instance at [https://openshift.feedhenry.com/](https://openshift.feedhenry.com/).

If you want pure Java version, use the official Java template in [https://github.com/feedhenry-templates/blank-android-gradle](https://github.com/feedhenry-templates/blank-android-gradle) 

## How do I run it?

### RHMAP Studio

This application can be imported by  

### Local Clone (ideal for Open Source Development)
If you wish to contribute to this template, the following information may be helpful; otherwise, RHMAP and its build facilities are the preferred solution.

###  Prerequisites
 * fh-android-sdk : 3.0.+
 * Android Studio : 1.4.0 or newer
 * Android SDK : 24

## Build instructions
 * Edit `app/src/main/assets/fhconfig.properties` to include the relevant information from RHMAP.
 * Attach running Android Device with API 16+ running
 * ./gradlew installDebug

## How does it work?

### Initialization

The FeedHenry SDK is initialized in `app/src/main/kotlin/org/feedhenry/blank/InitFragment.kt`.

