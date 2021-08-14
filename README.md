node --version

npm --version

cd desktop/weatherapp



npm install expo-cli --global



**Go to Visual Studio Code, make the following changes in app.json

"ios": {

   "supportsTablet": true,

   "bundleIdentifier" : "com.suma_chandrasekhar.weatherapp"

  },

  "android": {

   "package" : "com.suma_chandrasekhar.weatherapp",

   "versionCode" : 1

  },



--------

npm install react-native-gesture-handler

npm install --force

expo start





Ctrl + C (Command + C for Mac) to stop the metro bundler you ran using expo start.



In the same folder, run the following commands: 

● For building apk, run the command -  expo build:android 

● For building ipa, run the command -  expo build:ios



Enter your username and password of your snack account and proceed to generate key store.



It will take some time to generate because it will be in queued. You can check the status of that bundle in your snack account! 

Hence apk will be genarated to publish on playstore.



Hope this helps! :)

