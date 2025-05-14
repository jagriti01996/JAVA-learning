# JAVA-learning
JAVA learning content and code

Java File Naming Conventions
•	When writing a Java program, we should follow the below rules:
•	The file name must match with the public class name.
•	Java is case sensitive, so Geeks.java is not equal to geeks.java.
•	If a file has no "public" class, the file name can be anything but it should be matched with the primary class name.

```
// A Java program to print "Hello World" 
public class Geeks { 
    public static void main(String args[]) 
    { 
        System.out.println("Hello World"); 
    } 
}

// Output:"Hello World"
```
🧑‍💻 Is JavaScript platform-independent like Java?
✅ Yes, both JavaScript and Java are platform-independent, but they achieve it differently:
🔸 Java – "Write once, run anywhere"
Java code is compiled to bytecode.

Bytecode runs on the Java Virtual Machine (JVM).

The JVM is available for many platforms, making Java platform-independent.

✅ Platform independence is provided by the JVM layer.

🔸 JavaScript – Runs inside browsers or engines
JavaScript is not compiled to bytecode first (traditionally).

It runs inside a JavaScript engine, like:

V8 (Chrome, Node.js)

SpiderMonkey (Firefox)

JavaScriptCore (Safari)

These engines are built into browsers or environments like Node.js.

✅ Platform independence is provided by the browser or runtime environment.

⚖️ Comparison:
Feature	Java	JavaScript
Runs on	JVM	Browser or JS Engine
Output of compilation	Bytecode	Interpreted or JIT-compiled scripts
Platform independence	Via JVM	Via browser/runtime
Typical usage	Backend, Android, enterprise apps	Web apps, server-side (Node.js)

✅ So yes:
JavaScript is platform-independent — as long as there is a JavaScript engine (like in a browser or Node.js), it will run the same code on any OS or device.

| Feature                 | **Java**                       | **JavaScript (Node.js)**                |
| ----------------------- | ------------------------------ | --------------------------------------- |
| **Server-side support** | ✅ Yes (e.g., Spring Boot)      | ✅ Yes (via Node.js)                     |
| **API building**        | ✅ Widely used for REST APIs    | ✅ Very common for REST APIs             |
| **Speed**               | Very fast (compiled + JIT)     | Fast (event-driven, non-blocking I/O)   |
| **Enterprise usage**    | ✅ Dominates large companies    | Used more in startups and modern stacks |
| **Ecosystem maturity**  | ✅ Mature, stable, huge tooling | Modern, growing fast, lightweight       |
| **Learning curve**      | ⬆️ Steeper                     | ⬇️ Easier if you know JS already        |


💣 What is a Buffer Overflow?
A buffer overflow happens when a program tries to write more data into a fixed-size block of memory (buffer) than it can hold.

When this happens, the extra data spills into nearby memory, potentially:

Overwriting important variables

Crashing the program

Or even letting an attacker inject malicious code
![image](https://github.com/user-attachments/assets/bdfa6c59-8689-4b00-853a-4eda09248fa3)

