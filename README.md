# mobile
Library Mobile App

## Get dependencies
```
npm install -g gulp bower && npm install && bower install
```

## Build the App
```
gulp
```

## To run the Cordova App (after cloning this repo and cd into it)
Note: If you do not have the Android SDK installed [you will need
to do that](http://developer.android.com/sdk/installing/index.html). 
Otherwise you will see an error when you attempt to
build the android version.
```
npm install -g Cordova
cordova prepare
cordova build android
cordova emulate android
```
If you see an error about no emulator images found when trying to 
execute cordova emulate android, follow the instructions provided to 
add the addition SDK content and create an emulator.

## To run the Polymer App
```
gulp serve
```
