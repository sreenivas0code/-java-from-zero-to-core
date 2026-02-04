# 📘 Java Programming – Session 01
## 🎯 First Java Program

---

## 📌 About This Session
This session introduces the **absolute basics of Java programming**.  
It explains how Java code is written, compiled, and executed.

This knowledge is required before learning:
- Keywords
- Data Types
- Access Specifiers
- Object-Oriented Programming

---

## 🔹 What is Java?
**Java** is a high-level, object-oriented, and platform-independent programming language.

### Characteristics
- Easy to read and write
- Uses Object-Oriented principles
- Runs on multiple operating systems
- Secure and reliable
- Automatic memory management

**Principle:**  
> Write Once, Run Anywhere (WORA)

---

## 🔹 Why Java is Platform Independent
Java does not depend directly on the operating system.

### Execution Pipeline
.java → javac → .class → JVM → OS


### Explanation
- Source code is compiled into **bytecode**
- Bytecode runs inside **JVM**
- JVM handles OS-level execution

✔ Same `.class` file works on all platforms

---

## 🔹 Java Environment Components Overview
Java environment consists of three core components:

- **JDK** → Development
- **JRE** → Execution
- **JVM** → Runtime engine

---

## 🧩 JDK (Java Development Kit)
Used when **writing and compiling** Java programs.

### Includes
- Java compiler (`javac`)
- JRE
- Debugging tools
- Development utilities

📌 Mandatory for developers

---

## 🧩 JRE (Java Runtime Environment)
Used when **running** Java programs.

### Includes
- JVM
- Core Java libraries

📌 Not required for coding, only for execution

---

## 🧩 JVM (Java Virtual Machine)
JVM executes Java bytecode.

### Responsibilities
- Converts bytecode to machine code
- Allocates and deallocates memory
- Performs garbage collection
- Provides security
- Ensures platform independence

⚠ JVM is platform dependent  
✔ Java is platform independent

---

## 🔹 First Java Program (Code)

```java
class FirstJavaProgram {
    public static void main(String[] args) {
        System.out.println("Hello Java");
    }
}```

---

# 🔍 Code Breakdown (Line-by-Line)

## 1. `class FirstJavaProgram`
- Defines a **class**
- Every Java program must have **at least one class**
- Class name must match the **file name**

**Example file name:**

---

## 2. `public static void main(String[] args)`
This is the **entry point** of a Java program.

### Keyword Explanation
- `public` → JVM can access this method from anywhere
- `static` → No object creation is required
- `void` → Method does not return any value
- `main` → JVM starts execution from this method
- `String[] args` → Used for command-line arguments

> ⚠ Without the `main()` method, a Java program **will not run**.

---

## 3. `System.out.println("Hello Java");`
Used to **print output** to the console.

### Internal Meaning
- `System` → Predefined Java class
- `out` → Standard output stream
- `println` → Prints the message and moves to the next line

---

## 🔹 How the Program Executes (Step-by-Step)
1. JVM loads the class into memory
2. JVM searches for the `main()` method
3. Execution starts from `main()`
4. Statements execute sequentially (top to bottom)
5. Output is displayed on the console

---

# EXAMPLES 

---

## 🌍 Real-World Problems Solved Using the First Java Program

Although the first Java program is simple, it forms the **base for solving real-world problems**.  
Every Java application—small or large—starts with this structure.

---

### 🏦 Problem 1: Display Banking System Startup Message
**Scenario:**  
A banking application displays a startup message when the system loads.

```java
class BankApp {
    public static void main(String[] args) {
        System.out.println("Welcome to Secure Bank System");
    }
}
```

---

### 🏫 Problem 2: College Management System Initialization

**Scenario:**  
A college management system prints system information when launched.

```java
class CollegeSystem {
    public static void main(String[] args) {
        System.out.println("College Management System Started");
    }
}
```
---

### 🏥 Problem 3: Hospital Application Status Check

**Scenario:**
A hospital application shows a status message when the application runs.

```
class HospitalApp {
    public static void main(String[] args) {
        System.out.println("Hospital Application is Running");
    }
}
```
---
### 💻 Problem 4: Software Installation Verification

**Scenario:**
After installing a Java-based application, a message confirms successful execution.

```
class InstallCheck {
    public static void main(String[] args) {
        System.out.println("Application Installed Successfully");
    }
}
```
---
### 📱 Problem 5: Mobile / Backend Service Startup Log

**Scenario:**
Backend services log messages when they start.

```
class ServerStart {
    public static void main(String[] args) {
        System.out.println("Server started on port 8080");
    }
}
```
---





