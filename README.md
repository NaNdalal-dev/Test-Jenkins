# Java Hello World

A foundational, minimalistic **Java application** that outputs "Hello, World!" directly to the console terminal. This project serves as a starting point to test local development environments, compilers, and runtimes.

---

## 🛠 Prerequisites

Before compiling or running this application, you must install the following software on your system:

* **Java Development Kit (JDK)**: Version 8 or higher is highly recommended. You can verify your installation by typing `java -version` in your command line terminal.

---

## 📂 Project Structure

```text
└── HelloWorld.java   # Core source code containing the primary main method entry point
```

---

## 🚀 Getting Started

Follow these step-by-step terminal instructions to clone, compile, and run the code locally on your machine.

### 1. Save the Source Code
Ensure you have a file named exactly `HelloWorld.java` matching the class structure:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

### 2. Compile the Program
Navigate into the exact directory containing your file via terminal. Run the standard compiler command to generate machine-readable bytecode:
```bash
javac HelloWorld.java
```
*Note: This command generates a separate file named `HelloWorld.class` inside the same directory.*

### 3. Run the Bytecode
Execute the newly compiled bytecode application using the Java Virtual Machine (JVM) launcher:
```bash
java HelloWorld
```

### 🎯 Expected Console Output
```text
Hello, World!
```

---

## 📝 Code Breakdown

* **`public class HelloWorld`**: Defines an accessible blueprint class named `HelloWorld` which strictly dictates the matching filename.
* **`public static void main`**: Serves as the global entry point function where execution loops begin.
* **`System.out.println()`**: Standard Java system output stream method configured to print strings down to the active terminal.

