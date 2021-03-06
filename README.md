# Case Study: React Native

## Technology and Platform used for development
### Language and Basic Ideas
React Native is tool to build mobile apps. It can build Android app, IOS app and even Windows app. 
<br />
React Native only use JavaScript (JSX) to build mobile apps. As React, we can compose moblie UI using self-defined components.
<br /> But unlike web development in ReactJS, react native will not generate virtual DOM. It will only use the same fundamental UI building blocks as regular iOS and Android apps. Instead of using Swift, Kotlin or Java, we are putting those building blocks together using JavaScript and React.
<br />
React Native is fairly new, and becoming more popular.
<p align="center"><img src="https://github.com/ec500-software-engineering/case-study-heliatbu/blob/master/pics/react%20native.jpg" width="600"></p>

## Testing
Describe unit/integration/module tests and the test framework
### JavaScript

#### Jest
Jest tests are JavaScript-only tests run on the command line with node. Built by Facebook as well.

#### Flow test

### Android
#### Unit Tests
The Android unit tests do not run in an emulator.<br />It's a good idea to add an Android unit test whenever you are working on code that can be tested by Java code alone. 
#### Integration Tests

### IOS 
#### Integration Tests
React Native provides facilities to make it easier to test integrated components that require both native and JS components to communicate across the bridge. The two main components are RCTTestRunner and RCTTestModule. RCTTestRunner sets up the ReactNative environment and provides facilities to run the tests as XCTestCases in Xcode (runTest:module is the simplest method). RCTTestModule is exported to JS as NativeModules.TestModule.

## Software architecture

<p align="center"><img src="https://github.com/ec500-software-engineering/case-study-heliatbu/blob/master/pics/structure.png" width="700"></p>
Write the React code with building blocks of Native language, like Text, View, TextInput. Then render component to the Mobile phone for different platform.
 
## Data flow
Data Flow during app running:
All about state change and React life cycle. Combined with Redux (State Manager for React Project) 

## Compared with Flutter
<br>Language: React JS for React Native.Dart for Flutter. Dart is compiled using C/C++, so it’s closer to machine language and gives better native performance.
<br>Performance: Hard to say a winner
<br>Extensions and Community: React Native is little bit better


## Public feedback and Issuses
1、Since React Native is cross-platform developing tool, there are many bugs on different platforms existing remaining to fix.
<br/> 2、The support for old Android and IOS version is not good.

## Simple demonstration application
Very simple to do list app demonstrated with React Native.
<p align="center"><img src="https://github.com/ec500-software-engineering/case-study-heliatbu/blob/master/pics/demo.gif"></p>

