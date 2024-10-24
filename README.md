# ProjectBuddle

Welcome to the **ProjectBuddle** React Native project!

# Prerequisites
Make sure you have the following tools installed on your development machine:
- Node.js (LTS version)
- npm or yarn
- React Native CLI
- Android Studio or Xcode for iOS development
- CocoaPods for iOS development (MacOS)

# Getting Started
## 1. Install Dependencies
Navigate to the root directory of the project and install the required dependencies:
npm install
or
yarn install

## 2. Running on Android
Ensure you have an Android emulator or a physical device connected. Then, run:
npx react-native run-android

## 3. Running on iOS
For iOS, make sure CocoaPods is installed, and then run the following commands:
cd ios/
pod install
cd ..
npx react-native run-ios

# Development Workflow
To start the React Native development server:
npm start

This will launch Metro, the bundler for React Native. It automatically updates the app in the simulator or device when code changes are saved.

# Building for Production
For Android:
cd android/
./gradlew assembleRelease

For iOS:
npx react-native run-ios --configuration Release

# Troubleshooting
- Metro Bundler is not starting or port is already in use: Kill the process running on port 8081 or specify a new port.
- Emulator not found: Make sure the emulator is installed and running, or connect a physical device.

For more detailed documentation, visit the React Native Documentation.
