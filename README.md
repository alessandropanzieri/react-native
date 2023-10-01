**How to use React Native with Expo**

Prerequisites:

- Install the *last* version of [Node.js](https://nodejs.org/)

- Create an [Expo](https://expo.dev/)account

- Install Expo Go Android or ios app and login

Terminal commands:

1° Install the dependencies
>>> npm i -g expo
>>> npm i -g eas-cli

2° Connect the Expo account
>>> npx expo login

3° Create a new application
>>> cd path/where/create/app/
>>> npx create-expo-app@latest

4° Run and see changes in real-time on Expo Go app (connect to the same network)
>>> npx expo start

5° Link the app to Expo project
>>> eas init --id <project id provided by Expo>