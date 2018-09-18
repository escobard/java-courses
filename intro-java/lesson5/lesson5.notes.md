## Lesson 5 Notes

### JDK

- Oracle's main toolkit to interacting with the java runtime environment, java virtual machine, and the java compiler

#### Java Runtime Environment - JRE

- Includes the code behind all the variable types and built in functions like the `println()` function.
- Includes a Java Virtual Machine, (JVM_ which allows java code to run on any platform.
- Most OS's already have this installed, since java is so widely utilized.

#### Java Compiler - JAVAC

- Compiles java code into computer readable bytecode.
- Translates into Bytecode, for the JVM to use.

#### Java Virtual Machine - JVM

- Shows our console, and program outputs.
- Translates bytecode into machine code, binary, hex, etc.
- Translates bytecode into machine specific code, so it runs slightly differently on laptops vs desktops vs mobile, allowing cross platform functionality (in theory)

#### Running programs in the command prompt

- we can run programs in the command prompt with the following commands:
	- `javac FileName.java` - this compiles the class with the java compiler.
		- any errors thrown here, are errors related to the syntax, or location
		- this creates a .class file, which is the compiled version of the source code.
	- `java HelloWorld` - runs the compiled code, outputting the file output.
		- only runs the COMPILED code, not the source code, very important distinction.
