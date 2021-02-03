# NDIS-support-app
An Android app to help carers and support workers submit data on participant behaviour

## UI Prototype
An interactive layout prototype can be found here:
https://marvelapp.com/prototype/fjd2e7b

## Getting Started
The easiest way to test the app and see the work in progress is using Android Studio. Android studio is a development environment that includes an emulator which you can use to simulate an Android device on your computer, as well as tools for running the app on your physical Android device, if you'd prefer.  
Android Studio is also the easiest way to contribute - as a JetBrains IDE, it has pretty much all the tools you'll need.

### Android Studio
Install the latest version of Android Studio: https://developer.android.com/studio/

In the **Welcome to Android Studio** window, click **Get from Version Control**  
![Android Studio Step 1](https://github.com/joshdickie/NDIS-support-app/doobledeedoo)

TODO: PUT IN THE REST OF THE STEPS AFTER YOU FIGURE OUT HOW TO CLONE USING THE ANDROID STUDIO GUI
TODO: BASIC GIT COMMANDS FOR NON-TECHY PEOPLE TO CHECK ON WIP

## Running the App
### Running on a Physical Device (Recommended)
TODO: RUN ON MY OWN PHONE TO FIGURE IT OUT
### Running on an Emulator
Note: Creating a Virtual Device in order to run the emulator can take upwards of 9GB of storage space. If this space is not available, try [running on a physical device](#running-on-a-physical-device-recommended) instead.

### Create a Virtual Device
A Virtual Device contains all of the information that the emulator needs to simulate an Android device. 
In Android Studio, click **Tools > AVD Manager**  
![AVD Manager Location](https://github.com/joshdickie/NDIS-support-app/doobledeedoo)

Click **Create Virtual Device...**  
![AVD Manager Screen](https://github.com/joshdickie/NDIS-support-app/doobledeedoo)  
The **Select Hardware** page opens.

Select the device you would like to create an image of. Any device is fine - If you own an Android device, feel free to select the definition that matches it. If you're not sure, select **Pixel 4**.

Click **Next**

The **System Image** page opens.

Select an image from the **Recommended** tab. If you're not sure, select **Q**. If you see **Download** next to your selected image, you will need to click it in order to download the image.

The **Verify Configuration** page opens.

Click **Finish**.

### Start the Emulator
With a [Virtual Device](#create-a-virtual-device) created, select it in the target device drop-down menu.  
![Selecting Target Device](https://github.com/joshdickie/NDIS-support-app/doobledeedoo)

Click **Run** ![Run Button](https://github.com/joshdickie/NDIS-support-app/doobledeedoo)

Android Studio will start the emulator and install the app. It should open the app automatically.

## Contributing
Recommend using [Android Studio](#android-studio) as your IDE. I won't spend heaps of time selling it to you here, but suffice to say it can reduce the amount of XML you'll need to write by hand.  
I'm not sure how testing is usually done with UI stuff, aside from just opening it on a bunch of different devices and manually stress-testing it, which sounds shitty. If you know how to automate this kind of testing, we can integrate that!  
I'll do my best to keep features off Main until they're shippable - generally I'm planning to make each activity of the app at least two issues: the layout, and the associated Kotlin functions. I'd personally consider a feature "shippable" if its asociated issue is finished up and closed (i.e. I might merge to include an activity that has a completed layout, but doesn't yet have associated functions). I won't merge an activity to Main if it has any half-finished features (i.e. the layout is complete, and the associated functions are half done).

This is going to be a weekend thing for us mostly, so we can talk on Saturdays or whatever to catch up, show Dan what we've made and check in that he's happy with it, etc.
