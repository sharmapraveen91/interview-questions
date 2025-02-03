# Android & Kotlin Interview Questions

### 1. **Android Fundamentals**
   **a. What is the difference between `Activity`, `Service`, and `BroadcastReceiver` in Android? When would you use each of them?**

   **b. Explain the Android application lifecycle in detail. What are the key lifecycle methods, and how do you handle configuration changes like screen rotations?**

   **c. What is an `Intent` in Android? How do implicit and explicit intents differ? Provide an example of when to use each type.**

   **d. What is the difference between `SharedPreferences`, `SQLite`, and `Room` for data storage? In what scenarios would you prefer one over the other?**

   **e. How do you handle background tasks in Android? Explain `AsyncTask`, `Handler`, `IntentService`, and `JobScheduler`. Which one is most appropriate in modern Android development and why?**

---

### 2. **Kotlin Basics**
   **a. Explain the difference between `val` and `var` in Kotlin. What are the advantages of using `val`?**

   **b. What is the role of `companion objects` in Kotlin? Can you give an example where a companion object would be useful?**

   **c. In Kotlin, how does `null safety` work? What are the key differences between `nullable types`, `!!`, and `?.` operators?**

   **d. Explain Kotlin's `data` classes. What are the advantages of using a `data` class over a regular class? Can you override methods like `equals()` and `hashCode()` in a `data` class?**

   **e. How do extension functions work in Kotlin? Provide an example of when you would use an extension function in Android development.**

---

### 3. **Architecture and Design Patterns**
   **a. Explain the Model-View-ViewModel (MVVM) pattern. How does it differ from MVC and MVP? What are the benefits of using MVVM in Android apps?**

   **b. What is the role of `LiveData` and `ViewModel` in MVVM? How does `LiveData` handle lifecycle changes?**

   **c. How would you implement Dependency Injection in Android? Compare Dagger 2, Hilt, and Koin for DI in Android.**

   **d. What is the Single Responsibility Principle (SRP), and how does it affect your design choices when building Android applications?**

   **e. Explain how the Repository pattern works. How would you implement it in an Android app with Room and Retrofit for local and remote data sources?**

---

### 4. **UI/UX**
   **a. What is the difference between `ConstraintLayout` and `RelativeLayout`? When would you use `ConstraintLayout` over `RelativeLayout`?**

   **b. Explain the concept of `RecyclerView`. How would you create a custom layout for a `RecyclerView` item?**

   **c. What is `ViewBinding` in Android? How does it differ from `findViewById()`? What are the benefits of using `ViewBinding` over `Kotlin synthetics`?**

   **d. What are `CoroutineScope` and `Dispatchers.Main`? How do they interact with UI thread management in Android?**

   **e. How do you implement and use `DataBinding` in an Android application? What advantages does it provide over `findViewById()` and `ViewBinding`?**

---

### 5. **Coroutines and Concurrency**
   **a. What are Kotlin Coroutines, and how do they differ from traditional threading?**

   **b. How would you handle multiple concurrent tasks in an Android app using Coroutines? Can you explain the use of `async` and `await` with an example?**

   **c. What is the purpose of `Dispatchers.IO`, `Dispatchers.Main`, and `Dispatchers.Default`? When would you use each in Android?**

   **d. What is the `suspend` keyword, and how does it work in the context of coroutines?**

   **e. How do you handle exceptions in Kotlin coroutines? What happens if a coroutine fails?**

---

### 6. **Advanced Topics**
   **a. Explain the difference between `suspend` functions and `async/await`. When would you choose one over the other in Android development?**

   **b. What are `sealed classes` in Kotlin, and how are they useful in Android development? Can you give an example of how to use a `sealed class` to model different states in an app (e.g., loading, success, error)?**

   **c. How would you manage deep linking in Android? What steps would you take to support both `Universal Links` and `App Links` in your application?**

   **d. What is `WorkManager`, and how would you use it to manage background tasks that need to run periodically?**

   **e. Explain how `Memory Leaks` happen in Android. How can you avoid them when using Kotlin and working with views or contexts?**

---

### 7. **Networking and APIs**
   **a. Explain the role of `Retrofit` in Android. How do you set up a `Retrofit` instance and configure it for handling JSON data?**

   **b. What are `Interceptors` in Retrofit? How would you use them to log requests and responses in your app?**

   **c. Explain how you would handle authentication in Android apps, specifically with OAuth2 or JWT tokens. How would you store and manage tokens securely?**

   **d. What is the difference between `GET`, `POST`, `PUT`, and `DELETE` HTTP methods, and how would you map them to Retrofit requests?**

   **e. What is `OkHttp`? How does it integrate with Retrofit, and when would you use it directly instead of Retrofit for networking tasks?**

---

### 8. **Testing**
   **a. Explain how you would write unit tests in Android using `JUnit` and `Mockito`. Can you explain the concept of mock objects and why they are useful?**

   **b. What is the purpose of `Robolectric`? How does it differ from Espresso testing?**

   **c. How would you write UI tests with `Espresso`? What are some of the common challenges when testing UI components in Android?**

   **d. How would you test coroutines in an Android project? What tools or libraries would you use to test suspending functions?**

   **e. What is the role of `TestCoroutineScope` and `Dispatchers.setMain()` in unit testing with Kotlin coroutines?**

---

### 9. **Performance and Optimization**
   **a. How would you profile an Android application for performance issues? What tools would you use, and what metrics would you focus on?**

   **b. What are some common causes of UI jank in Android applications, and how would you fix them?**

   **c. What are `Memory Profiler` and `CPU Profiler` in Android Studio? How do you use them to debug and optimize an app?**

   **d. What is the difference between `Bitmap` and `Drawable` in Android, and how can you optimize image loading and memory usage?**

   **e. How would you optimize battery usage in an Android app? What are some best practices for minimizing battery drain in background tasks and services?**

---

### 10. **Modern Android Tools**
   **a. What is the role of Jetpack libraries in Android development? How do they help reduce boilerplate code?**

   **b. Explain `Hilt` in Android. How does it simplify dependency injection, and how is it different from using Dagger directly?**

   **c. What is `MotionLayout`? How would you use it to create complex animations in an Android app?**

   **d. Explain the concept of `Navigation Component`. How does it simplify app navigation and deep linking?**

   **e. How do you integrate Firebase (e.g., Firestore, Firebase Auth) in an Android app? What are the key components you would need to handle in a typical Firebase-based Android app?**

---
