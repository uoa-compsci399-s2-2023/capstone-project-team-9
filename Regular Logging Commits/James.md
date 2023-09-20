## Activity Log
- Took meeting notes. Stored in shared drive
- Prepared client meeting plan for next week; things to show/discuss with clients and details we should inform/update them about our progress

## E2E Testing on Expo
  
For our project, we are building an application using a [Managed workflow](https://docs.expo.dev/archive/managed-vs-bare/). In this instance, we use Expo's services and it handles most of the complexities for us. 

The current guide for E2E testing is in its very early stages, and was written in terms of a bare workflow project.

Many of the resources involve a bare workflow project or testing for iOS platforms. Our project's focus in on Android. The resources on Android seem unusable as it involves using Gradle files, as we're using Expo we don't have access to any Gradle files. Currently, there is no clear workaround solution based on the available resources

### Resources
- [possible iOS solution](https://stackoverflow.com/questions/54816994/is-it-actually-possible-to-make-detox-jest-tests-pass-with-a-react-native-app-ru/54834078#54834078)
- [possible iOS solution 2](https://blog.expo.dev/testing-expo-apps-with-detox-and-react-native-testing-library-7fbdbb82ac87)
- [Android Gradle example](https://github.com/expo/eas-tests-example/tree/main/android)

