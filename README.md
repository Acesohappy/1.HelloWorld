1. Java "Hello World" Program
   
Step 1: Install Java Development Kit (JDK)
Download and install the Java Development Kit (JDK) from Oracle's official website.
During installation, ensure that you set the JAVA_HOME environment variable and add JDK's bin folder to the system’s PATH.

Step 2: Open Your Text Editor or IDE
Use a text editor like Notepad++, VS Code, or a full IDE like IntelliJ IDEA or Eclipse.

Step 3: Write the Code
Open a new file and name it HelloWorld.java.
Write the following code in the file:
java

public class HelloWorld {
    public static void main(String[] args) {
        // Output the text to the console
        System.out.println("Hello, World!");
    }
}

Step 4: Save the File
Save the file as HelloWorld.java (note the .java extension).

Step 5: Compile the Program
Open Command Prompt or Terminal.
Navigate to the directory where the HelloWorld.java file is saved.
Use the javac command to compile the Java file:
bash

javac HelloWorld.java

Step 6: Run the Program
Once compiled, run the program using the java command:
bash

java HelloWorld

Step 7: Output
You should see the output:

Hello, World!
