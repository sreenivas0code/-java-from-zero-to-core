<u>🎯 Topic: First Java Program</u>


<u>📌 Session Overview</u>

In this session, we understand:

What Java is

Why Java is popular

Basic Java program structure

How the first Java program works

Role of JVM, JDK, and JRE

This session forms the foundation for all upcoming Java topics.


<u>🔹 What is Java?</u>

Java is a:

High-level programming language

Object-Oriented

Platform Independent

Secure & Robust

👉 Java follows the principle:

“Write Once, Run Anywhere (WORA)”


<u>🔹 Why Java is Platform Independent?</u>

Java code is not executed directly by the operating system.

<u>Execution Flow:</u>
Java Source Code (.java)
        ↓
Byte Code (.class)
        ↓
JVM (Java Virtual Machine)
        ↓
Operating System


<u>🔹 Java Environment Components</u>
<u>🧩 JDK (Java Development Kit)</u>

Used for developing Java programs

Contains:

Compiler (javac)

JRE

Development tools


<u>🧩 JRE (Java Runtime Environment)</u>

Used for running Java programs

Contains:

JVM

Core libraries


<u>🧩 JVM (Java Virtual Machine)</u>

Converts bytecode → machine code

Responsible for:

Memory management

Security

Platform independence


<u>🔹 Structure of First Java Program</u>

class FirstJavaProgram {
    public static void main(String[] args) {
        System.out.println("Hello Java");
    }
}



<u>🔍 Line-by-Line Explanation</u>

<u>🔸 class FirstJavaProgram</u>

Every Java program starts with a class

Class name should match the file name


<u>🔸 public static void main(String[] args)</u>

This is the entry point of Java execution.

Keyword	        Meaning
public	        Accessible from anywhere
static	        No object needed
void	        Returns nothing
main	        Execution starts here
String[] args	Command-line arguments


<u>🔸 System.out.println()</u>

Used to print output

System → predefined class

out → output stream

println → prints & moves to next line


<u>🔹 Program Execution Flow</u>

JVM looks for main() method

Statements execute line by line

Output is printed on the console


<u>⚠ Common Beginner Mistakes</u>

❌ Class name ≠ file name

❌ Missing main() method

❌ Wrong spelling (System, println)

❌ Case sensitivity issues


<u>💡 Key Takeaways</u>

Java program must have a class

Execution starts from main()

Java is platform independent

JDK ≠ JRE ≠ JVM


<u>🔗 Connection to Next Session</u>

In the next session, we will learn:

🔑 Java Keywords

📦 Data Types

🔐 Access Specifiers

➡ This session builds directly on the program structure basics learned here.


<u>📂 GitHub File Name</u>

Session-01-First-Java-Program.md






