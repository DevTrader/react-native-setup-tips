#Setup Instructions For Android Virtual Machine:
https://facebook.github.io/react-native/docs/getting-started.html#running-your-app-on-a-simulator-or-virtual-device


##Notes:
1. DO run the chocolatey and follow the setup described on react docs when developing on windows machines, it will save you a lot of trouble editing PATHs and finding the correct versions of JDK.
2. Always check which Android SDK is recommended to run React Native, the compiler will fail otherwise. 
3. You can either run: create-react-native-app (but then you have to eject) or you can run: react-native init project-name, to have the "ejected" version from the start.
4. Remember to run: react-native start, then run (on another command console): react-native run-android (after having the virtual android machine up).
5. After making changes to your code you can press "R" twice on the android virtual machine and it will refresh with your changes.

