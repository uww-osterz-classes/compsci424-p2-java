# UWW COMPSCI 424 Program 2 in Java

## Your notes for me

*If you have notes or messages for me, please put them here so I can see them.*

## About this repository and autograding

Use this template for Operating Systems Program 2 in Java.

Although GitHub Classroom autograding will not be used for this program, I would like you to use the following rules to make it easier to compile and run correctly. This template is set up with these rules in mind.

* **Your main class must be named `Program2`** because GitHub will use the run command `java Program2` to run your code. Other starter code files are included in this repository, but you can rename, modify, or combine those files as needed. 
* Your Java source code files (`.java` files) must be stored in the `app/src/main/java/compsci424/p2/java` directory within your project environment. The Gradle build system will compile all `.java` files in this directory when you issue a `gradle run` command. (On Windows, use backslashes '\\' instead of forward slashes '/'.)
* Your Java source code files must also include the package declaration `package compsci424.p2;`.

This template uses the Gradle build system to build and run your Java code. All of the major Java IDEs (Eclipse, IntelliJ, and NetBeans) support Gradle, and so does Visual Studio Code. You might need to install a Gradle plugin or change a "Build System" setting in your project settings to enable Gradle. Try it and see what happens.

You may use any standard Java class or feature that is supported in Java 17.

If you are encountering problems, please [email me](osterz@uww.edu) with a description of what's happening. I will look at your repository on GitHub to try to help you debug.

## Advice for Java programmers

This advice is also posted on the Program 2 page on Canvas. Updates, if any, will be posted there.

*   Use the standard Java [Thread class](https://docs.oracle.com/en/java/javase/15/docs/api/java.base/java/lang/Thread.html), and possibly the [Runnable interface](https://docs.oracle.com/en/java/javase/15/docs/api/java.base/java/lang/Runnable.html), to make your program multithreaded.
*   Java provides a built-in Semaphore class (`java.util.concurrent.Semaphore`) that you can use in this program. Read the [Javadoc for the Semaphore class](https://docs.oracle.com/en/java/javase/15/docs/api/java.base/java/util/concurrent/Semaphore.html) (Java 15) to figure out which method of the Semaphore class performs a P operation and which method performs a V operation.
*   My starter code includes a main class, another class for the producer thread's logic, and another class for the consumer thread's logic. There could also be other correct ways to structure this code.
