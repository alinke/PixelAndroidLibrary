
PixelAndroidLibrary for Android Studio
==========

Includes 3 Libraries and Sample App
=======
PixelHelloWord - Sample App
IOIOLibAndroid - Library
IOIOLibBT - Library
IOIOLIbAccessory - Library
==============

A very simply example which writes an image of an Apple to the LED Matrix. Use this code to get started and then build off it.

Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

  Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.alinke:PixelAndroidLibrary:1.0.0'
	}

