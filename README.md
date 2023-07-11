How to use React Native with Expo

Prerequisites:

- Install the last version of Node.js
  Donwload: https://nodejs.org/

- Create an Expo account
  Signup: https://expo.dev/

- Install Expo Go Android or ios app and login

Terminal commands:

1° Install the dependencies
>>> npm i expo
>>> npm i -g eas-cli

2° Connect the Expo account
>>> npx expo login

3° Create a new application
>>> cd path/where/create/app/
>>> npx create-expo-app --template blank@48

4° Run and see changes in real-time on Expo Go app
>>> npx expo start

5° Create Android and ios production build
>>> eas build --platform all