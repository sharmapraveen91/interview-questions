1. Kotlin Programming & Language Features (10 Questions)
	1.	What are the practical implications of Kotlin’s visibility modifiers like internal and private in multi-module projects?
	2.	How do safe calls (?.) and the Elvis operator (?:) help manage nullable types in Kotlin? Give real-world examples.
	3.	Why might you choose a data object over a data class in Kotlin? Provide a scenario.
	4.	When should you prefer lazy delegation over lateinit, and what are the key differences between them?
	5.	Describe how extension functions work in Kotlin. Can they override member functions?
	6.	In what scenarios would you use infix functions, and how do they improve readability?
	7.	Explain how inline, noinline, and crossinline functions affect performance and lambda behavior in Kotlin.
	8.	How does Kotlin enable access to type information at runtime using reified type parameters?
	9.	Describe delegation using by keyword. How would you implement a custom delegate?
	10.	What’s the functional difference between Kotlin’s Unit and Nothing types?

⸻

2. Object-Oriented Programming & Generics (5 Questions)
	11.	How do you achieve loose coupling in a Kotlin application, and why is it beneficial?
	12.	Compare covariance and contravariance with examples using Kotlin’s in and out keywords.
	13.	What’s the difference between declarative and imperative programming? How does Compose use declarative patterns?
	14.	In Kotlin, how do sealed interfaces differ from sealed classes in terms of flexibility and hierarchy?
	15.	When designing a generic repository class, how do type bounds and variance help enforce type safety?

⸻

3. Jetpack Compose UI (10 Questions)
	16.	How does recomposition work in Jetpack Compose, and what strategies can prevent unnecessary recompositions?
	17.	Explain the difference between remember and rememberSaveable with regard to state persistence.
	18.	How do side-effect handlers like LaunchedEffect, DisposableEffect, and SideEffect differ? Provide use cases.
	19.	Compose uses modifiers to style UI. How are they chained, and how do they affect performance?
	20.	How would you hoist state in a complex composable hierarchy? Why is this practice recommended?
	21.	Describe the process for building a custom slot-based composable and where it can enhance UI flexibility.
	22.	What tools and techniques help detect and fix performance bottlenecks in Compose UIs?
	23.	How do you ensure that your Compose UI is accessible to screen readers and users with disabilities?
	24.	Describe how TalkBack compatibility can be verified and improved in a Compose app.
	25.	How would you handle dynamic theming (e.g., dark/light mode) in Jetpack Compose?

⸻

4. Coroutines and Flow (10 Questions)
	26.	How does Kotlin Flow differ from LiveData in terms of data stream handling and use cases?
	27.	Compare StateFlow and SharedFlow—which one would you choose for a UI state vs an event bus?
	28.	What is backpressure, and how does Kotlin Flow mitigate it?
	29.	How would you use Flow operators like map, zip, and combine in real-time data processing?
	30.	In an emission from 1 to 10, how can you handle an error at 4 and resume with 5 in Flow?
	31.	What is the impact of Dispatcher.IO vs Dispatcher.Default in coroutine performance?
	32.	When would you use flowOn, withContext, or launchIn in coroutine-based programming?
	33.	Explain cold vs hot flows with real-life Android examples.
	34.	How do structured concurrency and coroutine scope management prevent memory leaks?
	35.	How do you implement retry logic with exponential backoff in a Flow-based API call?

⸻

5. Navigation in Compose (5 Questions)
	36.	How do you implement parameter passing between Composable screens using Jetpack Compose Navigation?
	37.	Describe how to clear the navigation stack and return to a specific screen without leaving intermediate screens.
	38.	How would you integrate deep linking into a Compose Navigation graph?
	39.	Explain how to test navigation behavior in Jetpack Compose.
	40.	How can you manage navigation in a multi-module Compose project while maintaining decoupling?

⸻

6. Networking and Data Handling (5 Questions)
	41.	How can you ensure authentication tokens are automatically added to every Retrofit API call?
	42.	Explain how you implement response caching using OkHttp’s cache policies.
	43.	How do you switch interceptors based on build types (Debug vs Release)?
	44.	When dealing with both GraphQL and REST, how do you design a network layer for minimal duplication?
	45.	How do you centralize error handling for all API failures and display consistent user-friendly messages?

⸻

7. Testing (3 Questions)
	46.	How do you effectively unit test suspend functions and flows in Kotlin using TestCoroutineDispatcher?
	47.	Compare MockK and Mockito—why might one be preferred in Kotlin-based projects?
	48.	How do you approach unit testing ViewModels in MVVM or MVI architecture?

⸻

8. Accessibility & Localization (2 Questions)
	49.	What techniques ensure your Android app supports RTL languages and handles layout mirroring correctly?
	50.	How do you ensure proper accessibility hierarchy and focus traversal in custom Compose layouts?
