Setup Instructions For Android Virtual Machine:
https://facebook.github.io/react-native/docs/getting-started.html#running-your-app-on-a-simulator-or-virtual-device


Notes:
-Download JRE 8 before installing
-DO run the chocolatey and follow the setup described on react docs when developing on windows machines, it will save you a lot of trouble editing PATHs and finding the correct versions of JDK.
-Always check which Android SDK is recommended to run React Native, the compiler will fail otherwise. 
-You can either run: create-react-native-app (but then you have to eject) or you can run: react-native init project-name, to have the "ejected" version from the start.
-Remember to run: react-native start, then run (on another command console): react-native run-android (after having the virtual android machine up).

