# Usage


## Run dev server

### Mobile device

Android:

```sh
$ yarn android
```

iOS (on macOS only):

```sh
$ yarn ios
```

### Web

```sh
$ yarn web
```

That will open two browser tabs:

- http://localhost:19002/ - Expo debugger
- http://localhost:19006/ - Your web app

In Expo, I clicked the Android emulator option and got this prompt:

```
Couldn't start project on Android: No Android connected device found, and no emulators could be started automatically.
Please connect a device or create an emulator (https://docs.expo.io/workflow/android-studio-emulator).
Then follow the instructions here to enable USB debugging:
https://developer.android.com/studio/run/device.html#developer-device-options. If you are using Genymotion go to Settings -> ADB, select "Use custom Android SDK tools", and point it at your Android SDK directory.
```

If you want to use the

```sh
$ yarn start
```

> Make sure your app is running in the simulator or on a phone connected via USB.


## Run tests

Warning - the default app is not setup right so Jest gets a syntax error.

```sh
$ yarn test
```
