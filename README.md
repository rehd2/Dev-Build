# Welcome to custom expo dev Build

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app) with --template defaiult .
This not an app project, but can be excuted with the default `npx expo start command`

# NOTE: The UI is still the same template you'd get with the [`create-expo-app`](https://www.npmjs.com/package/create-expo-app)

This project is designed to save the time and much work when creating mobile apps that use libraries that needs native code,
This project works just like the expo dev client you'd create with `expo prebuild` and `expo run:android` or `expo run:ios` but without the need to run those commands every time you want to test your app per project everytime.

# The main idea is to have a single expo dev client that can be used across multiple projects, and that can be easily updated with new libraries and features without the need to create a new dev client every time.

Provides a stable base you can reuse for multiple projects, and that can be easily updated with new libraries and features without the need to create a new dev client every time.

## Whats included in this project?

```
├── @expo/vector-icons@15.1.1
├── @react-native-async-storage/async-storage@2.2.0
├── @react-native-firebase/app@23.8.6
├── @react-native-firebase/auth@23.8.6
├── @react-native-firebase/firestore@23.8.6
├── @react-native-firebase/messaging@23.8.6
├── @react-native-firebase/storage@23.8.6
├── @react-navigation/bottom-tabs@7.15.3
├── @react-navigation/elements@2.9.8
├── @react-navigation/native@7.1.31
├── @shopify/flash-list@2.2.2
├── @supabase/supabase-js@2.98.0
├── @types/react@19.1.17
├── axios@1.13.6
├── dayjs@1.11.19
├── eslint-config-expo@10.0.0
├── eslint@9.39.3
├── expo-av@16.0.8
├── expo-blur@15.0.8
├── expo-camera@17.0.10
├── expo-constants@18.0.13
├── expo-dev-client@6.0.20
├── expo-file-system@19.0.21
├── expo-font@14.0.11
├── expo-haptics@15.0.8
├── expo-image-picker@17.0.10
├── expo-image@3.0.11
├── expo-linear-gradient@15.0.8
├── expo-linking@8.0.11
├── expo-network@8.0.8
├── expo-notifications@0.32.16
├── expo-router@6.0.23
├── expo-secure-store@15.0.8
├── expo-sharing@14.0.8
├── expo-splash-screen@31.0.13
├── expo-sqlite@16.0.10
├── expo-status-bar@3.0.9
├── expo-symbols@1.0.8
├── expo-system-ui@6.0.9
├── expo-web-browser@15.0.10
├── expo@54.0.33
├── nativewind@4.2.2
├── react-dom@19.1.0
├── react-native-gesture-handler@2.28.0
├── react-native-reanimated@4.1.6
├── react-native-safe-area-context@5.6.2
├── react-native-screens@4.16.0
├── react-native-svg@15.12.1
├── react-native-web@0.21.2
├── react-native-worklets@0.5.1
├── react-native@0.81.5
├── react@19.1.0
└── typescript@5.9.3
```

## Installation and usage

1. Clone this repository
   `git clone https://github.com/rehd2/Dev-Build.git`

2. Install dependencies
   `npm install` or `yarn install`

3. Build the development client
   `npx expo prebuild`

4. Run the development client on your desired platform

- For Android: `npx expo run:android`
- For iOS: `npx expo run:ios`

5. Start the development server
   `npx expo start`

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo
