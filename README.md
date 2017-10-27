# VioletDroid

An Android Application to easily create UML Diagrams
![VioletDroid on a Nexus 9](/images/nexus-9-violet.png "VioletDroid on a Nexus 9")

## Installation 
This app compiles at API 24, but compatible all the way back to API 15.

Compatible with most phones and tablets

### Android SDK 
You'll need to set your global `$ANDROID_HOME` variable to install, or, add a `local.properties` file in the `VioletDroidApplication` folder with your `sdk.dir` variable set.  That should look something like the following:

For macOS: 
```
sdk.dir=/Users/yourname/Library/Android/sdk/
```
For Windows:
```
sdk.dir=C:\\Users\\username\\AppData\\Local\\Android\\Sdk
```

### Building the app 
To build and install the app, first plug your Android into your computer, or start an [Android emulator](https://developer.android.com/studio/run/emulator.html). Then run the following command in the `VioletDroidApplicaton` folder
```
$ ./gradlew installDebug 
```

## Using VioletDroid
VioletDroid makes several features available to you. 
### Saving and Loading
You can save your diagram at any time by hitting **FILE** at the top and following the on-screen options to save and load your files.  You can come back to VioletDroid and load your previously saved VioletDroid files.  
### Adding Classes and Notes 
Tap **CLASS** or **NOTE** to add a Class item or a Note item to your diagram.
### Adding Arrows
Add an arrow by tapping **ARROW**.  A dialog will appear where you can make changes to the properties of the arrow.  Then, tap the item *from* which the arrow should be drawn, then on the item the arrow should draw *to*.  You can draw an arrow from an item to itself if desired.  
### Deleting an Item 
Delete an Item by pressing and holding an item to select it (it will appear highlighted) then press the delete button.
### Editing an Item 
Edit an Item by pressing and  holding an item to select it (it will appear highlighted) then press the *type* of item you have selected at the top.  For example, to edit an arrow, tap and hold the arrow to select the arrow, then tap the **ARROW** button.  
