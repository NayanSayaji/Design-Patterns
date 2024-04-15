# Repository Pattern

- The Repository Design Pattern is a set of `rules` and `practices` that make your software better. It’s like having a superpower in the world of software. It helps you keep your data organized and makes your software `flexible`, `easier to understand`, and `simpler to test`.

#### Let's break the ice of repository pattern in 3 parts :

- **`What ?`**
- **`Why ?`**
- **`How ?`**

## 1. `What` is The Repository Pattern actually ?

### Repository Design Pattern: Simplifying Data Access

- The Repository Design Pattern is a software design pattern that acts as an **`intermediary layer between an application’s business logic and data storage`**.
- Its `primary purpose` is to provide a **`structured and standardized way`** to **`access`**, **`manage`**, and **`manipulate data`** while abstracting the underlying details of data storage technologies.
- The Repository Design Pattern is a `blueprint for organizing and simplifying data access`, enhancing the efficiency and flexibility of software systems.

## 2. `Why` to implement The Repository Pattern
- repository pattern have two purposes **`first it is an abstraction of the data layer`** and **`second it is a way of centralising the handling of the domain objects`**.
- In many applications, the business logic accesses data from data stores such as databases, [SharePoint lists](<https://learn.microsoft.com/en-us/previous-versions/msp-n-p/ff649690(v=pandp.10)?redirectedfrom=MSDN#sharepoint-list-repositories>), or Web services. Directly accessing the data can result in the following:

```
- Duplicated code
- A higher potential for programming errors
- Weak typing of the business data
- Difficulty in centralizing data-related policies such as caching
- An inability to easily test the business logic in isolation from external dependencies
```

### **Objectives :**

**Repository pattern is use to achieve one or more of the following objectives :**

- You access the data source from many locations and want **to apply centrally managed, consistent access rules and logic**.
- You want to implement and centralize a caching strategy for the data source.
- You want to improve the code's maintainability and readability by **separating business logic from data or service access logic**.
- You want to use business entities that are strongly typed so that you can identify problems at compile time instead of at run time.


## 3. `How` to implement Repository Pattern 
- [Click here](./implementation-repo-pattern.md)