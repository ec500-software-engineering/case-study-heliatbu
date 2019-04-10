# Case Study: React Native

## Technology and Platform used for development
### Language and Basic Ideas
React Native is tool to build mobile apps. It can build Android app, IOS app and even Windows app. 
<br />
React Native only use JavaScript (JSX) to build mobile apps. As React, we can compose moblie UI using self-defined components.
<br /> But unlike web development in ReactJS, react native will not generate virtual DOM. It will only use the same fundamental UI building blocks as regular iOS and Android apps. Instead of using Swift, Kotlin or Java, we are putting those building blocks together using JavaScript and React.
<br />
React Native is fairly new, and becoming more popular.

## Testing
Describe unit/integration/module tests and the test framework
### JavaScript
#### Jest
Jest tests are JavaScript-only tests run on the command line with node.
#### Flow test

### Android
#### Unit Tests
The Android unit tests do not run in an emulator.<br />It's a good idea to add an Android unit test whenever you are working on code that can be tested by Java code alone. 
#### Integration Tests

### IOS 
#### Integration Tests
React Native provides facilities to make it easier to test integrated components that require both native and JS components to communicate across the bridge. The two main components are RCTTestRunner and RCTTestModule. RCTTestRunner sets up the ReactNative environment and provides facilities to run the tests as XCTestCases in Xcode (runTest:module is the simplest method). RCTTestModule is exported to JS as NativeModules.TestModule.

## Software architecture
![](https://github.com/ec500-software-engineering/case-study-heliatbu/blob/master/pics/structure.png  | width=300)
## Defects

## Simple demonstration application

