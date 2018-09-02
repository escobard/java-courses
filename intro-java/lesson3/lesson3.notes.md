# Lesson 3 - Functions

## Functions

### Sample function definition in Java

```
// function to print line
public void println(String x ){
	if(x == null){
		x = "null"
	}
	try{
		ensureOpen();
		textOut.write(x);
	}
	catch(IoException e){

	}
	newLine()
}


// function to print chorus, broken down with comments to explain syntax purpose

// this is an access modifier, defines who can access the declared function
// public acess means anyone can access the function
public 
	
	// this is called the return type, defines what the function is returning
	// the void return type means that nothing is being returned by the function
	void 
	
	//this is the function name, or what we use to call the function
	chorus(){
	// print out 1 line of chorus
	System.out.println("Once I had a love and it was a gas");
}
```

### Calling a function

```
// this can be called the same way in as in javascript, printing the chorus output

chorus();
```

### Function parameters

- The argument variable must be declared by type within the argument syntax
```
public void greeting(
	
	// this defines the type of the variable expected to be passed as an argument
	String 
	
	// this defines the name of the variable, which can be used within the function scope (like JS)
	location
	){
	System.out.println("Hello," + location);
}
```

### Multiple parameters