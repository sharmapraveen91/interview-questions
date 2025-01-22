# Python Interview Questions

## 1. **Core Python**

1. **Explain Python's Global Interpreter Lock (GIL) and its impact on multi-threading.**
   - **Explanation:** The GIL is a mechanism that prevents multiple native threads from executing Python bytecodes at once in CPython, which impacts multi-threaded performance.

2. **What are Python decorators and how do they work?**
   - **Explanation:** Decorators in Python are functions that modify the behavior of another function. They are often used for logging, access control, caching, etc.

3. **What are Python generators and how are they different from iterators?**
   - **Explanation:** Generators allow you to create iterators in a more concise way using the `yield` keyword. They are memory efficient compared to lists as they generate values one at a time.

4. **What is the difference between deep copy and shallow copy in Python?**
   - **Explanation:** A shallow copy creates a new object but doesn’t recursively copy objects found within it, whereas a deep copy creates a new object and recursively copies all nested objects.

5. **Explain the use of the `with` statement and context managers in Python.**
   - **Explanation:** The `with` statement is used to wrap the execution of a block of code within methods defined by a context manager. It is typically used for resource management like file I/O, network connections, etc.

---

## 2. **Object-Oriented Programming (OOP)**

1. **What is the difference between `@staticmethod`, `@classmethod`, and instance methods in Python?**
   - **Explanation:** `@staticmethod` doesn't take any reference to the instance or class, `@classmethod` takes the class as the first argument (`cls`), and instance methods take the instance as the first argument (`self`).

2. **How do Python's multiple inheritance and method resolution order (MRO) work?**
   - **Explanation:** Python supports multiple inheritance, and the MRO is the order in which base classes are looked up when searching for a method. The MRO can be inspected using the `.__mro__` attribute.

3. **What are metaclasses in Python?**
   - **Explanation:** A metaclass is a class of a class. It defines the behavior of a class, such as how it's instantiated, its methods, etc. You can define a metaclass by inheriting from `type` and overriding specific methods like `__new__` or `__init__`.

4. **Explain the difference between `__new__` and `__init__` in Python.**
   - **Explanation:** `__new__` is used to create a new instance of a class, while `__init__` is used to initialize that instance. `__new__` is only used in metaclasses or immutable types like `str` and `tuple`.

5. **What are Python's `super()` and how do you use it?**
   - **Explanation:** The `super()` function allows calling a method from a superclass from within a subclass. It helps in avoiding issues with method resolution order in the case of multiple inheritance.

---

## 3. **Data Structures and Algorithms (DSA)**

1. **How would you implement a priority queue in Python?**
   - **Explanation:** A priority queue can be implemented using `heapq` module, which provides an efficient way of maintaining a priority queue in a heap structure (min-heap by default).

2. **Explain the difference between `list`, `tuple`, and `set` in Python.**
   - **Explanation:** A `list` is mutable and ordered, a `tuple` is immutable and ordered, and a `set` is mutable but unordered. Sets are used for membership testing and eliminating duplicates.

3. **How would you reverse a string in Python?**
   - **Explanation:** You can reverse a string using slicing: `s[::-1]`. This is efficient and concise.

4. **How would you implement a linked list in Python?**
   - **Explanation:** A linked list can be implemented using a class for the node that holds data and a reference to the next node. You would define methods to insert, delete, and search nodes.

5. **Explain Python's `collections.Counter` and how it can be used.**
   - **Explanation:** `collections.Counter` is a subclass of `dict` used to count hashable objects. It provides methods like `.most_common()` and `.elements()` to work with counts of elements in iterables.

---

## 4. **Concurrency and Parallelism**

1. **How does Python handle concurrency and parallelism?**
   - **Explanation:** Python handles concurrency via multi-threading and multi-processing. While multi-threading is limited by the GIL in CPython, multi-processing uses separate memory spaces and can run tasks in parallel.

2. **What is the difference between `threading` and `multiprocessing` in Python?**
   - **Explanation:** `threading` is suited for I/O-bound tasks due to the GIL, while `multiprocessing` is better for CPU-bound tasks as it uses separate processes with independent memory spaces.

3. **How does Python's `asyncio` module work and how is it different from threads?**
   - **Explanation:** `asyncio` provides asynchronous I/O by using the event loop and coroutines. Unlike threads, `asyncio` runs on a single thread but can perform multiple I/O-bound operations concurrently.

4. **What are the benefits and challenges of using Python's `multiprocessing` module?**
   - **Explanation:** The main benefit of `multiprocessing` is that it bypasses the GIL, allowing true parallelism for CPU-bound tasks. However, it can be more resource-intensive due to process creation and inter-process communication (IPC).

5. **How can you handle exceptions in Python's `asyncio`?**
   - **Explanation:** Exceptions in asyncio can be handled by using `try-except` blocks within coroutines, and `asyncio.gather()` or `asyncio.wait()` can be used to handle multiple tasks and collect exceptions.

---

## 5. **Performance Optimization**

1. **How would you optimize the performance of a Python program?**
   - **Explanation:** Some strategies for optimizing Python code include using built-in functions and libraries (like `itertools`, `collections`), avoiding global variables, using list comprehensions, leveraging C extensions, and profiling with tools like `cProfile`.

2. **What is the difference between `deepcopy` and `copy` in Python in terms of performance?**
   - **Explanation:** `copy` creates a shallow copy (faster), while `deepcopy` recursively copies all objects (slower). Using `copy` when deep copying isn't necessary can significantly improve performance.

3. **What is memoization and how can it improve performance?**
   - **Explanation:** Memoization is an optimization technique where you store results of expensive function calls and reuse them when the same inputs occur again. This can be implemented using `functools.lru_cache`.

4. **How would you avoid memory leaks in Python?**
   - **Explanation:** To avoid memory leaks, avoid circular references, use weak references when needed, and ensure that you manage resources (like file handles, network connections) properly using context managers (`with` statement).

5. **What are Python's built-in performance profiling tools?**
   - **Explanation:** Python provides tools like `cProfile`, `timeit`, and `line_profiler` for measuring the performance of your code, identifying bottlenecks, and optimizing accordingly.

---

## 6. **Python Libraries and Frameworks**

1. **What is `Pandas` used for, and how does it improve data analysis in Python?**
   - **Explanation:** `Pandas` is a powerful library for data manipulation and analysis, offering fast, flexible data structures like DataFrames and Series to handle large datasets efficiently.

2. **How would you create and run a REST API in Python?**
   - **Explanation:** You can create a REST API using frameworks like `Flask` or `Django`. Flask provides a lightweight approach to creating web services, while Django comes with more built-in features for larger applications.

3. **What is `NumPy` and how is it used in Python?**
   - **Explanation:** `NumPy` is a powerful library for numerical computing in Python. It provides support for large multidimensional arrays, matrices, and a collection of mathematical functions to operate on these arrays.

4. **How would you use `Celery` for background task processing in Python?**
   - **Explanation:** `Celery` is a distributed task queue used for executing long-running tasks asynchronously. You can configure it to run tasks in the background and scale across multiple workers and servers.

5. **What is `SQLAlchemy` and how do you use it?**
   - **Explanation:** `SQLAlchemy` is a Python SQL toolkit and Object-Relational Mapper (ORM) that provides tools for interacting with databases using Python objects. It supports both high-level ORM queries and low-level database operations.

---

## 7. **Testing and Debugging**

1. **How do you debug a Python program?**
   - **Explanation:** You can use tools like `pdb` (Python Debugger), logging, or IDE features (like breakpoints) for debugging. Python's built-in `logging` module is useful for capturing detailed runtime information.

2. **What is the difference between unit testing and integration testing in Python?**
   - **Explanation:** Unit testing focuses on testing individual components in isolation, while integration testing checks if various components work together as expected.

3. **How do you mock external dependencies in unit tests?**
   - **Explanation:** You can use the `unittest.mock` module in Python to mock external APIs, database calls, or other services that the function under test depends on.

4. **What are pytest fixtures, and how are they used in Python?**
   - **Explanation:** `pytest` fixtures are a way to set up and tear down resources that tests might need. They help in managing state between tests and can be used for things like database connections, API clients, or configurations.

5. **How can you test asynchronous code in Python?**
   - **Explanation:** You can use the `pytest-asyncio` plugin along with `pytest` to test async code. This plugin allows you to write asynchronous tests with `async def` and run them with an event loop.

---