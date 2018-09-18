## Lesson 5 Notes

### JDK

- Oracle's main toolkit to interacting with the java runtime environment, java virtual machine, and the java compiler

### Java Runtime Environment - JRE

- Includes the code behind all the variable types and built in functions like the `println()` function.
- Includes a Java Virtual Machine, (JVM_ which allows java code to run on any platform.
- Most OS's already have this installed, since java is so widely utilized.

### Java Compiler - JAVAC

- Compiles java code into computer readable bytecode.
- Translates into Bytecode, for the JVM to use.

### Java Virtual Machine - JVM

- Shows our console, and program outputs.
- Translates bytecode into machine code, binary, hex, etc.
- Translates bytecode into machine specific code, so it runs slightly differently on laptops vs desktops vs mobile, allowing cross platform functionality (in theory)

### Running programs in the command prompt

- we can run programs in the command prompt with the following commands:
	- `javac FileName.java` - this compiles the class with the java compiler.
		- any errors thrown here, are errors related to the syntax, or location
		- this creates a .class file, which is the compiled version of the source code.
	- `java HelloWorld` - runs the compiled code, outputting the file output.
		- only runs the COMPILED code, not the source code, very important distinction.

### Intellij

- IDE for JS apps, from here:  https://www.jetbrains.com/idea/
- cool basic IDE for JS projects, setup instructions here: https://www.jetbrains.com/help/idea/creating-and-running-your-first-java-application.html
- Important points to consider:
	- SDK: Frameworks which provide tweaks to the default VM / Compiler.
	- Templates: Starting points for Java projects.
	- Package: If we are creating an application for the web or for mobile, the base PACKAGE of the project needs to be changed, but for command line apps `com.company` works fine.
	- configurations: Under Run > Configurations:
		- Sets up the class.
		- set up locations for source code for the compiler, and the compiled code for the VM.
		- more here: https://www.jetbrains.com/help/idea/creating-and-editing-run-debug-configurations.html
	- Running program: 
		- running the program in the IDE returns an output in a console or us to debug, 