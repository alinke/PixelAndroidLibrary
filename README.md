
Android Library for PIXEL:LED ART for Android Studio
==========

Includes 3 Libraries and Sample App

PixelHelloWord - Sample App // A very simply example which writes an image of an Apple to the LED Matrix. Use this code to get started and then build off it.

IOIOLibAndroid - Library

IOIOLibBT - Library

IOIOLIbAccessory - Library

Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories: (do not add under buildscript)

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

  Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.alinke:PixelAndroidLibrary:2.1.0'
	}

[![](https://jitpack.io/v/alinke/PixelAndroidLibrary.svg)](https://jitpack.io/#alinke/PixelAndroidLibrary)
