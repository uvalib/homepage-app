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
## Note: If you do not have the Android SDK installed you will need
## to do that. Otherwise you will see an error when you attempt to
## build the android version.
```
npm install -g Cordova
cordova prepare
cordova build android
cordova emulate android
```

## To run the Polymer App
```
gulp serve
```
