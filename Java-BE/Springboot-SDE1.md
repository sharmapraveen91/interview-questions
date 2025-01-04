# Interview Questions on Java Spring boot

## Round 1: Java Hands-on Coding and OOPs Concepts

### Easy Level
	1.	**Basic Java Concepts:**
	•	What is the difference between HashMap and Hashtable?
	•	Explain the final keyword in Java. Where can it be used?
	•	How does the equals() method differ from ==?
	•	Explain method overloading and overriding with examples.
    
	2.	**Basic Hands-on Problems:**
	•	Write a program to reverse a string without using built-in functions.
	•	Write a program to find the second-largest number in an array.
### Medium Level
	1.	**Java Collections and Streams:**
	•	How does HashMap handle collisions internally?
	•	Explain LinkedHashMap vs. TreeMap in terms of their internal working and use cases.
	•	What are the differences between Iterator and Spliterator?
	•	Demonstrate the use of Stream.map() and Stream.filter().
	2.	**OOPs Hands-on Problems:**
	•	Address Book: Write a program to manage a list of contacts. Include functionality to:
	•	Add a contact.
	•	Edit a contact.
	•	Delete a contact.
	•	Employee Management System: Implement classes for Employee and Department. Provide functionality to:
	•	Add an employee to a department.
	•	Sort employees by salary or department.
	•	ATM Machine Simulation: Write code that allows a user to:
	•	Deposit money.
	•	Withdraw money.
	•	Check their account balance.
	3.	**Exception Handling:**
	•	Write a program to handle custom exceptions for invalid user input in an ATM simulation.
	•	Explain the difference between throw and throws.
### Advanced Level
	1.	**Java Internals:**
	•	How does the hashCode() method impact the performance of HashMap?
	•	Why should we override both equals() and hashCode() when using custom keys in a map?
	•	What are weak references in Java, and where are they used?
	2.	**OOPs Hands-on Problems:**
	•	To-Do List: Implement a task manager that allows:
	•	Adding, editing, and marking tasks as complete.
	•	Sorting tasks by priority or due date using Comparator.
	3.	**Coding Problem:**
	•	Write a program to group an array of strings by their anagrams using Java Streams.
	•	Example Input: ["eat", "tea", "tan", "ate", "nat", "bat"]
	•	Expected Output: [["bat"], ["nat", "tan"], ["ate", "eat", "tea"]].

## Round 2: Spring Boot, Databases, Kafka/SNS/SQS

### Easy Level
	1.	**Spring Basics:**
	•	What is Spring Boot? How does it differ from Spring Framework?
	•	Explain the purpose of @RestController and @RequestMapping.
	•	What is the difference between @Component and @Bean?
	•	What is a BeanFactory and an ApplicationContext?
	2.	**Database Basics:**
	•	What is a primary key? How is it different from a unique key?
	•	What is the difference between INNER JOIN and LEFT OUTER JOIN?
	3.	**SNS/SQS Basics (if applicable):**
	•	What is SNS? What is SQS? How are they different?
	•	Explain use cases for SNS and SQS.
### Medium Level
	1.	**Spring Boot Concepts:**
	•	How does Spring Boot auto-configuration work?
	•	What is Dependency Injection? Explain the types of DI in Spring.
	•	What is @Transactional, and how does it work?
	•	How can you handle exceptions globally using @ControllerAdvice?
	2.	**Database Concepts:**
	•	Write a SQL query to:
	•	Find the second-highest salary in a table.
	•	Group employees by department and count the number of employees in each department.
	•	What is a foreign key? Explain with an example.
	•	Explain transaction isolation levels and their impact.
	3.	**Kafka Concepts:**
	•	Explain Kafka’s partitioning mechanism. How is message ordering achieved?
	•	What is consumer group rebalancing, and what causes it?
### Advanced Level
	1.	**Spring Boot Advanced Concepts:**
	•	Explain the @Conditional annotation. Provide a real-world example.
	•	Why doesn’t @Transactional work when a method is called within the same class?
	•	How would you implement caching in a Spring Boot application using @Cacheable? Explain cache eviction.
	2.	**Database Advanced Concepts:**
	•	How would you design indexes for a database table with high read traffic?
	•	Explain the differences between clustered and non-clustered indexes.
	•	Write a SQL query to fetch the top 3 employees by salary in each department.
	3.	**Kafka Advanced Concepts:**
	•	What happens to message ordering if there is a rebalance in a Kafka consumer group?
	•	How would you optimize Kafka for a high-throughput system with minimal message loss?

### Bonus: Real-Time Scenarios
	1.	**Scenario: Spring Boot**
	•	A REST API call takes too long to respond. How would you debug and improve its performance?
	2.	**Scenario: Databases**
	•	An application is experiencing deadlocks during transactions. How would you resolve this?
	3.	**Scenario: Kafka**
	•	A Kafka topic is losing messages. What steps would you take to identify and resolve the issue?
