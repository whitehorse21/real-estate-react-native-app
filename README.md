# React Native Real Estate Template

## Setup

1. Follow the instructions on the "React Native CLI Quickstart" tab of
   the [React Native setup instructions](
   https://reactnative.dev/docs/environment-setup).  These
   instructions fan out by host operating system (macOS, Windows,
   Linux) and target operating system (iOS, Android).  Follow
   whichever is appropriate.

2. Install the Javascript dependencies
   ```
   yarn install
   ```

3. Install iOS dependencies (iOS only)
   ```
   cd ios
   pod install
   ```
## Running

### Android (device or emulator)

Start an emulator or plug in your device, then:

`yarn run android`

If running on a device you must first:
  1. Enable USB Debugging on the device
  2. Run `adb reverse tcp:8081 tcp:8081` at the command line


### iOS Simulator

`yarn run ios`

This will start a simulator for you.
