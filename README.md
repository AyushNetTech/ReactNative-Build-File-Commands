# ReactNative-Build-File-Commands

# FOR MAKING .APK FILE

npm install -g eas-cli

eas login

eas build:configure

eas build --platform android --profile preview


# FOR CHANGE THE EXPO EAS ACCOUNT FOR BUILD

eas logout

eas login

eas init

Update owner in app.json / app.config.js (Optional but recommended) IF PRESENT IN FILE

eas build:configure

eas build --platform android --profile preview

# FOR CHANGE GIT REPO WHO HAVE ALREADY CONNECTED WITH ONE REPO 

git remote remove origin

git remote add origin https://github.com/your-username/new-repo.git

git add .

git commit -m "message"

git push -u origin main

# FOR APP DIRECTLY IN MOBILE USING USB CABLE

set JAVA_HOME=C:\Users\ayush\AppData\Local\Programs\Eclipse Adoptium\jdk-17.0.17.10-hotspot

npx expo run:android


# FOR MAKING .APK FILE IN SYSTEM 

npx expo run:android --variant release

FILE LOCATION --> android/app/build/outputs/apk/release/app-release.apk


#EXPO Accounts (UserName & Password)
1. ayushupase369
2. ayushupase369.1
3. ayushupasetech
4. ayushupase333
