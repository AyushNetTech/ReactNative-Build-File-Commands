# ReactNative-Build-File-Commands

# FOR MAKING .APK FILE

npm install -g eas-cli

eas login

eas build:configure

eas build --platform android --profile preview


# FOR APP DIRECTLY IN MOBILE USING USB CABLE

set JAVA_HOME=C:\Users\ayush\AppData\Local\Programs\Eclipse Adoptium\jdk-17.0.17.10-hotspot

npx expo run:android


# FOR MAKING .APK FILE IN SYSTEM 

npx expo run:android --variant release

FILE LOCATION --> android/app/build/outputs/apk/release/app-release.apk
