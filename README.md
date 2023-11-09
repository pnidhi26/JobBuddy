## JobBuddy-Mobile-App
This application is a job hunting mobile app.
![image](https://github.com/pnidhi26/JobBuddy/assets/30867614/c078bf26-eab1-4b68-88cb-56b16139a586)
![image](https://github.com/pnidhi26/JobBuddy/assets/30867614/8aa0d4d7-a36e-4dec-b804-9ea15239ec60)

## Tech Stack Used:
* React Native, Rapid API (JSearch), Expo, Expo Go, 
- https://expo.github.io/router/docs/


## Live Demo:
* Install Expo Go app and inside this app scan QR code are follow these below respective links with your Android/iOS.

* On Android - exp://u.expo.dev/update/7877ee6c-f691-484c-a73b-e406e772f224
![Alt text](image.png)

* On iOS  - exp://u.expo.dev/update/60651732-e517-4405-a77e-94507d3640e5
![Alt text](image-1.png)


## dependencies installation and other commands 
* npx create-expo-app@latest --example with-router ./
* npm install expo-font axios react-native-dotenv
* npm install -g expo-cli
* npx expo-doctor 
* npx expo install --check

## Run Server on Localhost
* To run your project, run one of the following npm commands as per need.
- npm start / npx expo start / expo-cli start --tunnel
- npm run android
- npm run ios
- npm run web


## build and deployment:

- Classic SDK < 49
* npm install expo@latest expo-cli@latest
* npx expo-cli publish

- EAS SDK > 50
* npm install --global eas-cli
* eas login
* eas update:configure
* eas build:configure
* eas build
* eas update


## Read more:
https://docs.expo.dev/eas-update/migrate-from-classic-updates/



