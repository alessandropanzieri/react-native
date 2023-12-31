# ⚛️How to use React Native with Expo

## Prerequisites

- Install the *last* version of [Node.js](https://nodejs.org/)

- Create an [Expo](https://expo.dev/) account

- Install Expo Go [Android](https://play.google.com/store/apps/details?id=host.exp.exponent) or [ios](https://apps.apple.com/it/app/expo-go/id982107779) app and login

## Terminal commands

1. Install the dependencies

    ```shell
    npm i -g expo
    npm i -g eas-cli
    ```

2. Connect the Expo account

    ```shell
    npx expo login
    ```

3. Create a new application

    ```shell
    cd path/where/create/app/
    npx create-expo-app@latest
    ```

    *the following commands must be run inside app folder*

4. Run and see changes in real-time on Expo Go mobile app (be careful to connect to the same PC network)

    ```shell
    npx expo start
    ```

5. Link the app to Expo project

    ```shell
    eas init --id <project id provided by Expo>
    ```

6. Build app for Android or/and ios

    ```shell
    eas build --platform android/ios/all
    ```
