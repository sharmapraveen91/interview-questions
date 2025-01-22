# React Native Interview Questions

## 1. **React Native Core Concepts**

1. **Explain how React Native differs from other mobile frameworks (e.g., Flutter, Xamarin). What are the key advantages and limitations of React Native?**
2. **How does the React Native bridge work? Can you explain how JavaScript communicates with native modules on iOS and Android?**
3. **What is the role of the `react-native` packager, and how does it handle bundling JavaScript code?**
4. **How does React Native handle layout rendering? Explain how `Flexbox` works in React Native and its differences with web development.**
5. **What are the different types of components in React Native? How do `Functional` and `Class` components differ, and when would you prefer one over the other?**

---

## 2. **State Management**

1. **How does React Native’s state management differ from React for web apps? What strategies do you use to manage state in large-scale applications?**
2. **Explain the role of `Context API` and `useReducer` in state management in React Native. How do they compare to traditional Redux?**
3. **What is the difference between `Redux` and `MobX` in React Native applications? How do you decide which one to use?**
4. **How do you manage asynchronous state changes in React Native, particularly when using APIs or background tasks?**
5. **What is the purpose of `useEffect` in React Native? How do you use it effectively to handle side effects such as API calls or event listeners?**

---

## 3. **Navigation**

1. **Explain the concept of navigation in React Native. What are the differences between `React Navigation` and `React Native Navigation` (from Wix)?**
2. **How do you implement deep linking in React Native? What is the role of the `Linking` API, and how can you handle dynamic deep link URLs?**
3. **How do you handle authentication flow (e.g., login, sign-up, session expiry) in React Native using `React Navigation`?**
4. **What is the role of `NavigationContainer` in React Navigation, and how do you define nested navigators (stack, tab, drawer) in a React Native app?**
5. **How do you implement dynamic screen transitions or custom animations between different screens in React Native navigation?**

---

## 4. **Native Modules and Bridging**

1. **What is a native module in React Native, and how do you create one for Android and iOS?**
2. **How do you bridge native code to JavaScript in React Native? Explain the process and provide an example of when you would need a native bridge.**
3. **Can you explain how to use native UI components from iOS or Android in React Native? Provide an example of integrating native views such as `UITextField` (iOS) or `EditText` (Android).**
4. **What are some common challenges faced when bridging between JavaScript and native modules, and how do you resolve them?**
5. **How does React Native handle asynchronous communication between JavaScript and native code? What is the role of `Promise` and `Callback` in bridging?**

---

## 5. **Performance Optimization**

1. **What are the common performance bottlenecks in React Native, and how do you address issues such as slow rendering or memory leaks?**
2. **How would you optimize a React Native app’s performance when it comes to large lists (e.g., `FlatList` or `SectionList`)?**
3. **Explain how to handle images efficiently in React Native. What techniques would you use to load images faster and reduce memory usage?**
4. **How do you reduce the bundle size of a React Native app? What steps can you take to optimize the JavaScript bundle during the build process?**
5. **What tools would you use for performance profiling in React Native? Explain how to use `React Native Performance Monitor` or third-party tools like `Flipper` to identify performance issues.**

---

## 6. **Error Handling and Debugging**

1. **What are some best practices for error handling in React Native, particularly with asynchronous operations and API calls?**
2. **How do you set up and use `Flipper` in React Native for debugging purposes? What features of Flipper are useful for development and troubleshooting?**
3. **Explain how you would handle exceptions in React Native, including unhandled promise rejections and native crashes.**
4. **What are the differences between `console.log`, `debugger`, and other debugging tools available in React Native? When would you use each?**
5. **How do you debug issues related to native code in React Native? What tools do you use for inspecting iOS/Android code?**

---

## 7. **Testing and Quality Assurance**

1. **What are the different types of testing you can perform in React Native, and how do you set up unit tests, integration tests, and end-to-end tests?**
2. **How would you set up Jest and Enzyme for unit testing in React Native? Can you give an example of testing a component or reducer in React Native?**
3. **What is the role of `Detox` in React Native testing, and how would you use it for end-to-end testing?**
4. **Explain how you would test API calls in React Native using mocking techniques and tools like `Axios` and `Jest`.**
5. **How do you handle UI testing in React Native? What are the best practices for writing tests for `TouchableOpacity`, `TextInput`, and other interactive components?**

---

## 8. **React Native Libraries and Ecosystem**

1. **Explain the difference between `React Navigation` and `React Native Navigation` in terms of performance, setup, and use cases.**
2. **What are some popular libraries used for animations in React Native, such as `react-native-reanimated` and `react-native-animated`? How do they improve performance over traditional `Animated` APIs?**
3. **How does `Redux` integrate with React Native, and what libraries or middleware do you use to manage side effects (e.g., `redux-saga`, `redux-thunk`)?**
4. **What is `Realm` and how does it compare with `SQLite` and `Core Data` for local storage in React Native?**
5. **How would you implement push notifications in React Native using `React Native Push Notification` or `Firebase Cloud Messaging (FCM)`?**

---

## 9. **Networking and API Integration**

1. **What is the `fetch` API in React Native, and how do you use it to make network requests? How does it compare to `Axios`?**
2. **Explain how to handle API pagination and infinite scrolling in React Native, especially with lists like `FlatList`.**
3. **How do you implement network status monitoring in React Native? Can you use the `NetInfo` API to handle offline and online states?**
4. **What are the best practices for securely storing sensitive data (e.g., API tokens, user credentials) in React Native?**
5. **How would you handle request retries, timeouts, and response caching in React Native? What libraries or techniques do you use to optimize network requests?**

---

## 10. **Native Code Integration and Native Modules**

1. **Explain how you would link a custom native module in React Native. What steps would you take for integrating native iOS and Android code?**
2. **What is `react-native link`, and how does it differ from manual linking of libraries and native modules?**
3. **How do you handle backward compatibility when integrating native code or libraries in React Native projects?**
4. **What is the process for creating and managing native UI components in React Native? Can you provide an example of using a native module to create a custom view?**
5. **How do you troubleshoot issues when native code doesn’t work as expected in React Native? What are some common debugging practices for native integration?**

---

## 11. **CI/CD in React Native**

1. **What tools and services would you use for setting up continuous integration (CI) and continuous deployment (CD) in React Native?**
2. **Explain how you would set up a pipeline for building and deploying React Native apps to iOS and Android using services like CircleCI, Jenkins, or GitHub Actions.**
3. **How do you manage different environments (e.g., development, staging, production) in React Native apps with respect to API URLs, feature flags, and other configurations?**
4. **What is the purpose of `Fastlane` in React Native, and how can it help automate tasks like building and distributing apps to stores?**
5. **How would you automate testing, building, and deploying React Native apps in a CI/CD pipeline? What are the challenges in React Native CI/CD setups, and how do you overcome them?**

---

## 12. **Security in React Native**

1. **What are the best practices for securing data storage in React Native? How do you securely store API keys or user data on the device?**
2. **How would you implement app signing and encryption to ensure the integrity and confidentiality of data in React Native apps?**
3. **Explain the concept of code obfuscation in React Native. How would you protect the JavaScript code from reverse engineering?**
4. **How do you ensure secure communication between a React Native app and the backend server? Can you explain how SSL pinning works in React Native?**
5. **What are some common security risks in React Native apps, and how would you mitigate threats like XSS, CSRF, or data leaks?**

---

